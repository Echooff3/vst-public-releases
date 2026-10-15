# Plug-in downloads

Installers for plug-ins by Echooff3.

## Wild Card

A turntable scratch instrument for the Hercules DJControl Starlight (VST3,
CLAP and a standalone app for macOS 11+, Intel and Apple Silicon). No
controller? Drag the record with the mouse.

| Build | Version | Download | SHA-256 |
|---|---|---|---|
| Unsigned | 0.1.0 | [Wild-Card-macOS.pkg](https://github.com/Echooff3/vst-public-releases/raw/main/unsigned/Wild-Card-macOS.pkg) | `3123272177abf9646d14e33d4d63da18aaf09ada9304c9f81819b264f13bf65b` |

### Installing an unsigned build

These builds aren't signed with an Apple Developer ID yet, so macOS blocks
the installer the first time:

1. Open `Wild-Card-macOS.pkg`; macOS says it can't verify the developer.
2. Open **System Settings ▸ Privacy & Security**, scroll down and click
   **Open Anyway** next to the message about Wild-Card-macOS.pkg.
3. Run the installer. It puts the plug-ins in `/Library/Audio/Plug-Ins`
   and the app in `/Applications`.

To check the download first: `shasum -a 256 Wild-Card-macOS.pkg` should
print the SHA-256 above.
