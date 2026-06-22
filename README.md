<div align="center">

<img src="assets/qorelly.png" width="120" alt="Qorelly" />

# Qorelly for macOS

Multi-tenant business management for restaurants, spas, and retail — POS, quick service, full service, bookings, and more.

[![Latest release](https://img.shields.io/github/v/release/usecorehq/qorelly-releases?label=latest&sort=semver)](https://github.com/usecorehq/qorelly-releases/releases/latest)

### [⬇️ Download the latest release](https://github.com/usecorehq/qorelly-releases/releases/latest)

</div>

---

## Download

| Platform | Download | Requires |
| --- | --- | --- |
| **macOS** · Apple Silicon + Intel | [Qorelly-1.0.0-macOS.dmg](https://github.com/usecorehq/qorelly-releases/releases/download/v1.0.0/Qorelly-1.0.0-macOS.dmg) | macOS 10.15+ |
| **Windows** · x64 | [Qorelly-1.0.1-Windows-Setup.exe](https://github.com/usecorehq/qorelly-releases/raw/main/Qorelly-1.0.1-Windows-Setup.exe) | Windows 10+ |

## Install

### macOS

1. Download **`Qorelly-1.0.0-macOS.dmg`**.
2. Open the DMG and drag **Qorelly** into your **Applications** folder.
3. Launch Qorelly from Applications.

#### ⚠️ First launch: "Qorelly can't be opened"

This early build isn't notarized by Apple yet, so macOS will warn you the first time. It's expected and safe — pick whichever works:

- **Right-click** Qorelly in Applications → **Open** → **Open**.
- If it says **"Qorelly is damaged"** or won't open, run this in **Terminal**, then open normally:
  ```sh
  xattr -dr com.apple.quarantine /Applications/Qorelly.app
  ```
- Or go to **System Settings → Privacy & Security**, scroll down, and click **"Open Anyway"**.

You only need to do this once. A fully signed & notarized build (no warnings) is coming in **v1.0.1**.

### Windows

1. Download **`Qorelly-1.0.1-Windows-Setup.exe`**.
2. Run the installer and follow the setup wizard (this installs Qorelly and creates desktop & start menu shortcuts).
3. Launch **Qorelly** from your desktop or start menu.

## All releases

Browse every version and its changelog on the **[Releases page](https://github.com/usecorehq/qorelly-releases/releases)**.

---

<sub>© 2026 Qorelly. All rights reserved.</sub>
