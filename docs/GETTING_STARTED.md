# Getting Started

Everything you need to take any project from this organization and run it, on your computer or on a real Huawei watch.

New to HarmonyOS? Read straight through. Already have DevEco Studio working? Jump to [Opening a project](#3-opening-a-project).

## Contents

1. [Accounts and requirements](#1-accounts-and-requirements)
2. [Installing DevEco Studio](#2-installing-deveco-studio)
3. [Opening a project](#3-opening-a-project)
4. [Previewer and emulator](#4-previewer-and-emulator)
5. [Run on a Smart Wearable](#5-run-on-a-smart-wearable)
6. [Run on a Sportwatch](#6-run-on-a-sportwatch)
7. [hdc command reference](#7-hdc-command-reference)
8. [Working with an AI assistant](#8-working-with-an-ai-assistant)

Something failing at any point? See [Troubleshooting](TROUBLESHOOTING.md).

---

## 1. Accounts and requirements

| What | Why | Where |
|---|---|---|
| Huawei Developer account | Required to sign apps and use AppGallery Connect | https://developer.huawei.com/consumer/en/ |
| Identity verification | Required before you can create certificates and profiles | Developer console, Account and Verification |

Verification can take a day or two. Start it now and install the IDE while you wait.

DevEco Studio runs on Windows and macOS, both Intel and Apple Silicon. Check the current requirements in the [official install guide](https://developer.huawei.com/consumer/en/doc/harmonyos-guides/ide-software-install), they change between releases. In practice you want 16 GB of RAM or more, and around 100 GB of free disk if you plan to use emulators.

There is no official Linux build. On Linux you can build and sign with the HarmonyOS Command Line Tools, but generating signing material needs Windows or macOS at least once.

A physical watch is optional. You only need one for sensors, NFC, the digital crown, Wear Engine, health data and real performance measurements.

## 2. Installing DevEco Studio

1. Download the installer from the [DevEco Studio page](https://developer.huawei.com/consumer/en/deveco-studio/).
2. Run it and accept the defaults. DevEco Studio bundles the HarmonyOS SDK, Node.js, `hvigor`, `ohpm` and the emulator, so there is nothing else to install separately.
3. On first launch, if it asks about importing settings, choose **Do not import settings**.
4. Click **Diagnose** on the welcome screen. It checks your environment and tells you what to fix. Do not skip this, it saves hours later.
5. Sign in with your Huawei ID using the avatar in the top right corner. Device deployment and automatic signing both depend on it.

<!-- Suggested screenshot: welcome screen with the Diagnose button highlighted -->

### SDK versions

**Settings / Preferences → SDK** lists the installed versions.

Every project states the SDK and IDE version it was built with, in its own README under **Tech Stack** (some projects call it **Technology → Stack**):

```
Frameworks: HarmonyOS SDK 6.0.0
Tools: DevEco Studio 6.0.0
```

Keep at least those versions installed. A version mismatch is the most common reason a freshly cloned project refuses to build.

## 3. Opening a project

```bash
git clone https://github.com/Explore-In-HMOS-Wearable/<project-name>.git
cd <project-name>
```

**File → Open**, then select the **project root**, not a sub-folder. You are in the right place if the folder contains:

| Platform | Look for |
|---|---|
| Smart Wearable | `build-profile.json5`, `oh-package.json5`, `AppScope/`, `entry/` |
| Lite Wearable | `entry/src/main/config.json` and a `js/` source folder |

Opening `entry/` by mistake gives you a project that looks fine but never builds. Avoid paths with spaces or non-ASCII characters, the toolchain does not always handle them.

The first open triggers a dependency sync (`ohpm install`) that can take several minutes.

### Project structure (Smart Wearable)

```
<project>/
├── AppScope/
│   └── app.json5              # bundleName and app level config
├── entry/
│   ├── src/main/
│   │   ├── ets/
│   │   │   ├── entryability/  # UIAbility entry point
│   │   │   └── pages/         # Index.ets and other pages
│   │   ├── resources/         # images, strings, colors
│   │   └── module.json5       # permissions, device types
│   └── build-profile.json5
├── build-profile.json5        # signing configs, SDK versions
├── oh-package.json5           # dependencies
└── hvigorfile.ts              # build tasks
```

Note `bundleName` in `AppScope/app.json5`. You need it later if you sign manually.

## 4. Previewer and emulator

**Previewer:** open a page file (`Index.ets`, or `index.hml` for Lite Wearable) and click **Previewer** in the right sidebar. It hot reloads as you type and is the fastest way to work on layout, styling and round screen adaptation. It cannot give you sensors, NFC, Bluetooth, Wear Engine or health data.

**Emulator:** **Tools → Device Manager**, create a device, then **Launch**. The system image downloads on first run. Wearable coverage varies by DevEco Studio release. If your version offers no watch profile, use the Previewer for UI and a physical watch for everything else.

## 5. Run on a Smart Wearable

You do this setup once per device. After that, running any new project is a single click.

### Step 1: Enable developer mode on the watch

1. Go to `Settings → About`.
2. Tap **Software version** repeatedly, 5 to 7 times, until developer options are enabled.
3. Go to `Settings → System → Developer options`.
4. Enable **HDC debugging** and **Debug via Wi-Fi**.
5. The Wi-Fi debugging screen shows an address such as `192.168.1.42:5555`. You need it next.

<!-- Suggested screenshot: watch showing the Wi-Fi debugging address -->

### Step 2: Connect

Put both devices on the same network. Corporate and guest Wi-Fi often block device to device traffic, so a hotspot from your computer is the reliable option.

In DevEco Studio: **Tools → IP Connection**, type the `IP:port` from the watch, click connect. The device should show as **Online** and appear in the device selector at the top right.

```bash
# terminal equivalent
hdc tconn 192.168.1.42:5555
hdc list targets
```

### Step 3: Get the UDID

```bash
hdc shell bm get --udid
```

Copy the hex string. You need it to register the watch as a debug device.

### Step 4: Sign the app

A HarmonyOS app cannot be installed on a real device unless it is signed, and the device must be listed in the profile used to sign it.

**Option A, automatic (recommended)**

**File → Project Structure → Signing Configs → Debug**, tick **Automatically generate signing**. While you are signed in with your Huawei ID, DevEco Studio creates the key, certificate and profile and registers the connected device. This works for most projects here.

Use Option B when the project needs restricted permissions, when you have reached the certificate limit on your account, or when the bundle name is already registered to another app.

**Option B, manual**

| # | Where | Action |
|---|---|---|
| 1 | DevEco Studio | **Build → Generate Key and CSR**, create a `.p12` keystore, then a `.csr` |
| 2 | AGC, Certificates | New **Debug** certificate, upload the `.csr`, download the `.cer` |
| 3 | AGC, App IDs | New App ID, type *HarmonyOS App*. The package name must match `bundleName` in `AppScope/app.json5` |
| 4 | AGC, Devices | Add device, type *Smart watch*, paste the UDID from step 3 |
| 5 | AGC, Profiles | New **Debug** profile, select the App ID, certificate and device, download the `.p7b` |
| 6 | DevEco Studio | **Project Structure → Signing Configs → Debug**, untick automatic signing, point the fields at the `.p12`, `.cer` and `.p7b` |

AppGallery Connect: https://developer.huawei.com/consumer/en/service/josp/agc/index.html

A package name that does not match `bundleName` is the classic cause of an install time signature failure.

📖 [Signing configuration](https://developer.huawei.com/consumer/en/doc/harmonyos-guides-V5/ide-signing-V5) and [Debugging a HarmonyOS app](https://developer.huawei.com/consumer/en/doc/agc-harmonyapp-debugharmonyapp)

### Step 5: Run

Select the watch in the device selector, select the `entry` module, then press **Run** to install and launch, or **Debug** to attach breakpoints. Runtime output goes to the **Log** panel, or `hdc shell hilog`.

## 6. Run on a Sportwatch

Repositories prefixed with `sportwatch-` target Lite Wearable devices running HarmonyOS LiteOS. They are written in JavaScript with HML markup and CSS, and configured through `config.json`.

```
<project>/
└── entry/src/main/
    ├── config.json            # deviceType is liteWearable
    └── js/MainAbility/
        ├── app.js             # global logic and lifecycle
        ├── common/            # images and shared services
        ├── i18n/              # en-US.json, zh-CN.json
        └── pages/index/
            ├── index.hml      # layout
            ├── index.css      # style
            └── index.js       # interaction
```

1. Open the project root and let it sync. The device type in `config.json` tells the IDE which toolchain to use.
2. Open `pages/index/index.hml` and click **Previewer**. This is the primary development loop for Lite Wearable: layout, styling, page routing and most interaction logic are all verifiable here.
3. For a full application run, launch the Lite Wearable simulator from **Tools → Device Manager**, if your DevEco Studio version provides one.
4. To deploy to a physical sport watch, the device must expose developer and debug mode. If it does, follow [steps 1 to 5 above](#5-run-on-a-smart-wearable) exactly as written.

Device support differs by model. Each project README has a **Constraints and Restrictions → Supported Devices** section listing what that sample was verified on. Treat it as the source of truth for that project.

### Building for both platforms

The [Adapter Project](https://github.com/Explore-In-HMOS-Wearable/adapter-project) provides wrapper libraries with one API surface across both platforms, plus a generator:

```bash
node generator.js gen-smart lite-app smart-app
```

It converts a Lite Wearable project into a Smart Wearable JS project, handling configuration and file layout. It covers features common to both platforms, and currently supports Smart Wearable JS projects rather than ArkTS. The recommended workflow is to build the Lite Wearable version first and generate the Smart Wearable one from it.

## 7. hdc command reference

`hdc` is the HarmonyOS device connector, the equivalent of `adb`. It ships inside the SDK:

| OS | Typical path |
|---|---|
| Windows | `C:\Users\<user>\AppData\Local\OpenHarmony\Sdk\<version>\toolchains` |
| macOS | `~/Library/OpenHarmony/Sdk/<version>/toolchains` |

Add that folder to your `PATH` to call `hdc` from anywhere.

```bash
# connection
hdc list targets                          # devices currently visible
hdc tconn 192.168.1.42:5555               # connect over Wi-Fi
hdc kill && hdc start                     # restart the hdc server when it gets stuck

# device
hdc shell bm get --udid                   # UDID for device registration
hdc shell param get const.product.model   # model name

# app lifecycle
hdc install ./entry-default-signed.hap
hdc uninstall com.example.myapp
hdc shell aa force-stop com.example.myapp

# logs
hdc shell hilog                           # live log stream
hdc shell hilog -r                        # clear the log buffer

# files
hdc file send ./local.txt /data/local/tmp/
hdc file recv /data/local/tmp/remote.txt ./

# screenshot, useful on watches with no screenshot gesture
hdc shell screencap -p /data/local/tmp/shot.png
hdc file recv /data/local/tmp/shot.png ./shot.png
```

To wrap a screenshot in a watch device frame, use the [Mockup Generator](https://explore-in-hmos-wearable.github.io/mockup-generator/).

## 8. Working with an AI assistant

If you develop with Claude, Claude Code or another assistant that supports skills, install the wearable samples skill so the assistant can search this catalog instead of writing HarmonyOS code from memory:

```bash
unzip skill/hmos-wearable-samples.skill -d ~/.claude/skills/
```

With the skill installed, "is there a sample that reads heart rate on the watch" returns the repository name and URL, and the assistant will flag when you are mixing up Smart and Lite Wearable APIs.

The skill carries project descriptions, not source code. When you want working code, clone the repository it points you to.

---

## Official documentation

| Topic | Link |
|---|---|
| DevEco Studio download | https://developer.huawei.com/consumer/en/deveco-studio/ |
| Installing DevEco Studio | https://developer.huawei.com/consumer/en/doc/harmonyos-guides/ide-software-install |
| Signing configuration | https://developer.huawei.com/consumer/en/doc/harmonyos-guides-V5/ide-signing-V5 |
| Debugging a HarmonyOS app | https://developer.huawei.com/consumer/en/doc/agc-harmonyapp-debugharmonyapp |
| AppGallery Connect | https://developer.huawei.com/consumer/en/service/josp/agc/index.html |
| Huawei Developer Forum | https://forums.developer.huawei.com/forumPortal/en/home |
