# LiveManager downloads

Installer builds of **LiveManager**, the VS Code extension for LiveServer / LSML development.
This repository holds downloads only (no source code).

**Latest release:** https://github.com/MayurDubey91/livemanager-downloads/releases/latest

## Install (Windows, recommended)

1. Install [Visual Studio Code](https://code.visualstudio.com/) (1.106 or newer) if you don't have it.
2. Download `LiveManager-Setup-<version>.exe` from the latest release.
3. Run it. It installs per user (no admin needed) and adds the extension to VS Code.
   - **Windows SmartScreen** may say "Windows protected your PC" because the installer isn't code-signed.
     Click **More info**, then **Run anyway**.
4. Restart VS Code (or run **Developer: Reload Window**). LiveManager shows up in the Activity Bar.

## Install the .vsix directly (any OS)

Download `livemanager-<version>.vsix`, then either
- in VS Code: Extensions view → `…` menu → **Install from VSIX…**, or
- from a terminal: `code --install-extension livemanager-<version>.vsix --force`

## Update

Install the newer release the same way; it replaces the old version.
