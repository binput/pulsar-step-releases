# Pulsar Step — releases

Installers and signed update manifests for **Pulsar Step** (Windows 10/11 x64).
This repository holds release binaries only; there is no source code here.

- Download the latest `PulsarStep-Setup-<version>.exe` from **Releases**.
- Per-user install, no administrator rights needed. The installer is not code-signed, so
  Windows SmartScreen may show "Unknown publisher".
- `latest.json` + `latest.json.sig` are used by the app's updater. The app only installs an
  update whose manifest carries a valid Ed25519 signature and whose installer matches the
  signed SHA-256 checksum.

Pulsar Step automates keyboard input in a game. Automating input may break the game's or
Roblox's rules and can put your account at risk. Use at your own risk.

Copyright (C) 2026 Star. All rights reserved.
