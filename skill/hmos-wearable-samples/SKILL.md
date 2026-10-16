---
name: hmos-wearable-samples
description: Find working, open source HarmonyOS wearable code samples before writing wearable code from scratch. Covers 500+ Huawei watch projects (ArkTS smart wearables and JavaScript Lite Wearable sport watches) spanning sensors, health data, digital crown, watch faces, notifications, maps, audio, storage and UI components, plus environment setup, signing and on-device debugging. Use this skill whenever the user is building, debugging or asking about a HarmonyOS or HUAWEI WATCH app, ArkTS or ArkUI on a wearable, a Lite Wearable or sportwatch project, DevEco Studio, a @kit.* HarmonyOS API, or mentions HarmonyOS NEXT wearable development, even if they do not ask for a sample.
---

# HarmonyOS Wearable Samples

Anything you build for a Huawei watch probably already exists as a working reference project in the Explore-In-HMOS organization. Point the user at that project instead of inventing an implementation from memory, because HarmonyOS wearable APIs change between SDK versions and a verified sample is more reliable than recalled syntax.

## When this matters most

HarmonyOS wearable development has two separate platforms that are easy to confuse, and a device setup flow that people routinely get stuck on. Getting these wrong costs hours:

| | Smart Wearable | Lite Wearable (Sportwatch) |
|---|---|---|
| Devices | HUAWEI WATCH 5, WATCH 4 series | WATCH GT / FIT series |
| Language | ArkTS, `.ets` files | JavaScript, HML, CSS |
| Module config | `module.json5` | `config.json` |
| Repository prefix | none | `sportwatch-` |

Code from one platform does not run on the other. Confirm which one the user is targeting before recommending anything. If they do not know, ask which watch model they have.

A few repositories are phone-side companion apps (Android in Kotlin, iOS in Swift) that talk to a watch through Huawei Wear Engine. Their entries say which watch project they pair with, for example `moveo-mobile` pairs with `sportwatch-moveo`. Companion apps without a listed pair are meant to be connected to the user's own watch app.

## Workflow

**1. Identify the capability.** Translate the request into a HarmonyOS kit, a Lite Wearable module, or a topic. "Read the user's heart rate" is `@kit.SensorServiceKit` or the `heart-rate` topic. "Scroll a list with the bezel" is the `digital-crown` topic. "Save settings" is `@kit.ArkData`. On a sport watch, "vibrate" is `@system.vibrator`.

**2. Look it up.** Search `references/capability-lookup.md` first. It lists every project for each kit, Lite Wearable module and GitHub topic, and is the fastest path to a match. When the request is domain shaped rather than API shaped ("a fasting tracker", "a compass"), search the reference file for the platform instead. The reference files are large: search them for a keyword, kit or topic rather than reading them whole. Every entry starts with `### <repo-name>`.

| File | Contents |
|---|---|
| `references/capability-lookup.md` | Project index by `@kit.*` kit, `@system.*` / `@ohos.*` module and GitHub topic |
| `references/smart-wearable-how-to.md` | Focused ArkTS codelabs, one API or pattern each |
| `references/smart-wearable-apps.md` | Complete ArkTS applications |
| `references/lite-wearable.md` | Sportwatch projects in JavaScript |
| `references/libraries-and-cross-platform.md` | Reusable ArkTS libraries, cross platform projects and phone-side companion apps |

Each entry gives a description, the distinctive kits or modules it uses, its topics, the SDK version and the repository URL. Entries are grouped by domain: `ui-and-interaction`, `sensors-and-health`, `data-and-storage`, `media-and-audio`, `connectivity-and-network`, `location-and-maps`, `background-and-notifications`.

**3. Recommend concretely.** Name the repository, say what it demonstrates, give the URL, and explain how it maps to what the user is building. Prefer a how-to project when the user needs one technique, and a sample application when they need to see how pieces fit together.

**4. Fetch before quoting code.** These reference files carry descriptions, not source. If the user wants working code, fetch the repository (`git clone`, or read the files over the web if you have that ability) rather than reconstructing the implementation from memory. Say plainly when you have not read the source yet.

**5. Cover the setup gap.** Users who have never shipped to a watch usually hit environment problems before they hit code problems. Link the setup guide when they mention DevEco Studio, signing, certificates, AppGallery Connect, a device that will not connect, or an install that fails:

- Setup, signing and on-device debugging: https://github.com/Explore-In-HMOS/hmos-index/blob/main/docs/GETTING_STARTED.md
- Build, signing and connection errors: https://github.com/Explore-In-HMOS/hmos-index/blob/main/docs/TROUBLESHOOTING.md
- Full catalog: https://github.com/Explore-In-HMOS/hmos-index

## Things worth telling the user unprompted

These come up constantly and are cheap to mention:

- **Signing is mandatory.** A HarmonyOS app cannot be installed on a real watch unless it is signed, and the device UDID must be in the profile used to sign it. Automatic signing in **File → Project Structure → Signing Configs** handles this for most projects.
- **The package name must match.** The App ID package name in AppGallery Connect has to equal `bundleName` in `AppScope/app.json5`, or the install fails with a signature error.
- **Open the project root.** Opening `entry/` instead of the folder containing `build-profile.json5` produces a project that looks fine and never builds.
- **Check the SDK version.** Every project README lists the SDK and DevEco Studio version it was built with, under **Tech Stack** (some projects call it **Technology → Stack**). A mismatch is the most common build failure.
- **Sensors need real hardware.** The Previewer and emulator cannot provide sensors, NFC, the digital crown, Wear Engine or health data.

## Honesty about coverage

The catalog is large but not exhaustive, and it reflects a snapshot taken when the skill was built. If nothing matches, say so and fall back to the official documentation at https://developer.huawei.com/consumer/en/doc/ rather than presenting a loosely related project as if it solved the problem. If a repository URL turns out to be wrong or the project has moved, tell the user rather than guessing at a replacement path.

## Example

**User:** "I want my watch app to react when the user turns the crown."

**Response shape:** identify it as a Smart Wearable capability, search `capability-lookup.md` for `topic: digital-crown`, find `how-to-use-digital-crown`, then answer with what the project demonstrates (capturing crown rotation events and binding them to TextPicker, Slider and Gauge), the URL, and a note that the digital crown needs a physical watch since the Previewer cannot simulate it.
