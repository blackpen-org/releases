# BlackPen — Releases

Official release artifacts and auto-update feed for the BlackPen desktop app.

## Download

**[Latest release →](https://github.com/blackpen-org/releases/releases/latest)**

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `BlackPen_x.y.z_aarch64.dmg` |
| macOS (Intel) | `BlackPen_x.y.z_x64.dmg` |
| Windows x64 | `BlackPen_x.y.z_x64-setup.exe` |

## Install notes

- **macOS**: DMGs are currently ad-hoc signed and not notarized. On first launch, right-click the app → Open, or allow it under System Settings → Privacy & Security.
- **Windows**: the NSIS installer is currently unsigned; SmartScreen may warn — choose "More info" → "Run anyway". Installs per-user (no admin needed).

## Auto-update

The app checks this repo's latest release (`latest.json`) on startup and updates in-app. Update packages are signed (minisign) and verified before install.

## Channels

- `vX.Y.Z` — stable releases (marked Latest; picked up by auto-update)
- `beta-X.Y` — pre-releases (manual download only; not an auto-update channel)

Source code lives in a private repository; this repo hosts distribution artifacts only. Issues and feedback welcome here.
