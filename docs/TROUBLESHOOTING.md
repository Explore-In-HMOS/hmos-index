# Troubleshooting

Grouped by where things break. If your symptom is not listed, the Huawei Developer Forum is the fastest place to ask: https://forums.developer.huawei.com/forumPortal/en/home

## Contents

- [Opening and syncing](#opening-and-syncing)
- [SDK and API errors](#sdk-and-api-errors)
- [Device connection](#device-connection)
- [Signing and installation](#signing-and-installation)
- [FAQ](#faq)

---

## Opening and syncing

| Symptom | Cause | Fix |
|---|---|---|
| Sync hangs or fails on first open | `ohpm` cannot reach the registry | Check your network and proxy, then **File → Sync and Refresh Project** |
| Project structure not recognised | You opened a sub-folder | Reopen the folder containing `build-profile.json5`, or `config.json` for Lite Wearable |
| Odd build errors after switching branches | Stale build cache | **Build → Clean Project**, then rebuild |
| Unicode or path errors during build | Spaces or non-ASCII characters in the project path | Move the project somewhere simple such as `D:\dev\project` |
| Previewer will not start | Previewer process stuck | Restart DevEco Studio, then run **Diagnose** from the welcome screen |

## SDK and API errors

| Symptom | Cause | Fix |
|---|---|---|
| `compileSdkVersion X is not supported` | Installed SDK older than the project needs | Install the SDK version listed in the project README, or update DevEco Studio |
| An imported `@kit.*` module cannot be resolved | That kit is not in your SDK version | Update the SDK to the version in the project README |
| Previewer renders blank | Runtime error on the page | Restart the Previewer, then read the log panel |

Downgrading a project's SDK version usually means rewriting the API calls that changed. Updating the IDE is almost always the shorter path.

## Device connection

| Symptom | Cause | Fix |
|---|---|---|
| Watch does not appear after IP connection | Wi-Fi debugging off, or the devices are on different subnets | Toggle **Debug via Wi-Fi** off and on, confirm both are on the same network, reconnect |
| Connection drops after a few minutes | The watch got a new DHCP address, or it went to sleep | Reserve a static IP for the watch on your router, and keep the watch awake while debugging |
| `hdc: command not found` | Toolchain not on `PATH` | Add the SDK `toolchains` folder to `PATH`, see [hdc command reference](GETTING_STARTED.md#7-hdc-command-reference) |
| `hdc list targets` is empty while DevEco Studio sees the device | Two hdc servers competing | Run `hdc kill`, then reconnect |

## Signing and installation

| Symptom | Cause | Fix |
|---|---|---|
| Install fails with a signature or verification error | The device is not in the profile | Re-register the UDID in AppGallery Connect, regenerate the `.p7b`, reconfigure Signing Configs |
| `signDebugShell FAILED` or `validateDebugSigning` | Wrong file in the wrong field, or wrong password | Recheck the `.p12`, `.cer` and `.p7b` assignments and the store and key passwords |
| App installs but is rejected at launch | `bundleName` differs from the App ID package name | Align `AppScope/app.json5` with the App ID, then regenerate the profile |
| Automatic signing is greyed out | Not signed in, or the account is not verified | Sign in with your Huawei ID and complete identity verification |
| Cannot create another certificate | Certificate limit reached on the account | Revoke an unused certificate in AppGallery Connect |

---

## FAQ

**Do I need to clone the index repository?**
No. Each project is a standalone repository, so clone only the one you want.

**Can I develop on Linux?**
There is no official DevEco Studio build for Linux. You can build and sign with the HarmonyOS Command Line Tools, but generating signing material requires Windows or macOS at least once.

**Do I need a physical watch?**
Not for UI work. You do need one for sensors, NFC, the digital crown, Wear Engine, health data and real performance measurements.

**Can I run a Smart Wearable project on a sport watch, or the reverse?**
No. They are different platforms with different frameworks. Check for the `sportwatch-` prefix. If you need both, build the Lite Wearable version first and generate a Smart Wearable JS project from it with the [Adapter Project](https://github.com/Explore-In-HMOS/adapter-project). The generator only works in that direction.

**The project targets a newer SDK than mine. What now?**
Update DevEco Studio. That is almost always faster than porting the project backwards.

**Where do I report a problem?**
Broken links or outdated instructions in these guides go to the index repository. A bug in a specific sample goes to that sample's own repository.
