# Wisp

A free, native system monitor for macOS 26 and later.

## Release status

[Download Wisp.dmg](https://github.com/PhanithNY/wisp-releases/releases/latest/download/Wisp.dmg).
This repository hosts compiled releases and release notes. App source code is maintained separately.

## Features

- System CPU, memory, network activity and storage capacity.
- A menu bar dashboard and local CPU/memory history.
- Optional Dock icon: turn off **Show Dock icon** in Settings → Appearance to keep it hidden, including while windows are open. The preference is remembered after relaunch.
- Per-app activity and hardware readings where macOS and the hardware permit access.
- No accounts, advertising, telemetry or monitoring data uploads.

Sensor and process coverage varies by Mac and macOS version. Missing readings are shown as unavailable.

## Installation

Download `Wisp.dmg` from [Releases](https://github.com/PhanithNY/wisp-releases/releases), open it, and drag Wisp to Applications.

Install with Homebrew: `brew install --cask PhanithNY/tap/wisp`.

Wisp requires macOS 26 or later. Release packages are built for Apple silicon and Intel.

## Usage and updates

Wisp continues monitoring in the menu bar when you close its window or use ordinary Quit.
Choose **Wisp → Quit Wisp Completely** to exit before replacing or removing the app.
When the Dock icon is hidden, use the menu bar panel's power button to quit completely.
Launch at login is optional and off by default. Updates are installed manually or through Homebrew.

## Support and privacy

Report bugs through [Issues](https://github.com/PhanithNY/wisp-releases/issues). Include your macOS version and Mac model. Issues are public; omit private process names and other personal information.

Read the [privacy policy](PRIVACY.md). Wisp is free to download; this repository does not grant an open-source license to the app.
