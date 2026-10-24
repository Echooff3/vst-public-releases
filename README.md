# Plug-in downloads

Installers for plug-ins by Echooff3 (Trilsoft). Each is a universal macOS
11+ package (Apple Silicon and Intel), signed with a Developer ID and
notarized by Apple, so it opens without warnings.

| Plug-in | Version | Download (always the latest) |
|---|---|---|
| Wild Card | 0.1.0 | [Wild-Card-macOS.pkg](https://github.com/Echooff3/vst-public-releases/releases/download/wildcard-latest/Wild-Card-macOS.pkg) |
| Conceal-N-Strike | 0.1.0 | [Conceal-N-Strike-macOS.pkg](https://github.com/Echooff3/vst-public-releases/releases/download/conceal-n-strike-latest/Conceal-N-Strike-macOS.pkg) |
| MIDI Fart Sniffer | 0.1.1 | [MIDI-Fart-Sniffer-macOS.pkg](https://github.com/Echooff3/vst-public-releases/releases/download/midi-fart-sniffer-latest/MIDI-Fart-Sniffer-macOS.pkg) |
| Bruno | 0.1.0 | [Bruno-macOS.pkg](https://github.com/Echooff3/vst-public-releases/releases/download/bruno-latest/Bruno-macOS.pkg) |

All versions and SHA-256 checksums: [Releases](https://github.com/Echooff3/vst-public-releases/releases).

Installing: open the .pkg, then rescan plug-ins in your DAW. The installer puts
the VST3 in `/Library/Audio/Plug-Ins/VST3`, the CLAP in `/Library/Audio/Plug-Ins/CLAP`,
the Audio Unit in `/Library/Audio/Plug-Ins/Components` and the standalone app in
`/Applications` (MIDI Fart Sniffer and Bruno also add a Max for Live device in
`/Library/Application Support/Trilsoft/<plug-in name>`). Open the plug-in
and enter your activation code.

## Older unsigned build


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
