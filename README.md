# Clueless for Windows

Public **releases-only** repo. The source stays private.

## Download

**[⬇ Clueless_0.2.1_x64-setup.exe](https://github.com/ACMAGI7/Clueless-windows-public/releases/download/v0.2.1/Clueless_0.2.1_x64-setup.exe)** — current build **v0.2.1** (a hotfix: files open on a PC again, and Macquarie's iLearn files download).

1. Download the installer above.
2. Run it. It installs to your **user folder**, so there is no administrator prompt.
3. Launch from the Start menu.

**Windows SmartScreen will warn you.** This build is not code-signed yet, so Windows shows *"Windows protected your PC"*. Choose **More info → Run anyway**. That warning is about the missing certificate, not about anything the app does.

> **Already have Clueless installed? Back up first.**
> Copy `%APPDATA%\com.refinery.clueless` somewhere safe before installing — paste that path straight into the File Explorer address bar.

**There is no auto-update on Windows yet.** Grab new builds from [Releases](https://github.com/ACMAGI7/Clueless-windows-public/releases).

### Requirements

- **Windows 11, 64-bit (x64).**
- **~8 GB free** — about 550 MB for the app, plus ~4.5 GB if you install the on-device AI model.
- **WebView2 runtime**, which the installer fetches automatically if your machine doesn't have it (Windows 11 ships with it).

### Checksum

```
SHA-256  d6ee82ff4d8602b004139b086dc672314451a41622c28bbbcc8b6c1c3ed6f505
         Clueless_0.2.1_x64-setup.exe
```
