# FSLogix Profile Cleaner – releases

Binary releases (installers and update packages) of **FSLogix Profile Cleaner** for

* Windows x64 (`win-x64`)
* macOS on Apple Silicon (`osx-arm64`)

This repository contains **no source code**. It hosts GitHub Releases only: installers, portable packages,
update packages (Velopack), update feeds, release notes and `SHA256SUMS.txt`. Intel Macs are not supported.

## Install

| Platform | Download |
|---|---|
| Windows x64 | `FSLogixProfileCleanerApp-win-x64-stable-Setup.exe` (per-user, no administrator rights) or `…-Portable.zip` |
| macOS Apple Silicon | `FSLogixProfileCleanerApp-osx-arm64-stable-Setup.pkg` or `…-Portable.zip` |

The packages are **not code-signed or notarized** yet. Windows SmartScreen and macOS Gatekeeper warn on first start
(macOS: right-click → Open, or *System Settings → Privacy & Security → Open Anyway*).

Installed copies update themselves (Settings → Updates in the app): the app checks this repository anonymously,
downloads the update package after your confirmation and verifies its size and hash before installing.
Beta builds are published as pre-releases (`x.y.z-beta.N`) and are only offered on the Beta channel.

Verify a download against `SHA256SUMS.txt` of the same release.
