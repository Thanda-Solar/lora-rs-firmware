# LoRa-RS Firmware Hub

Public releases for **Thanda LoRa Remote Switch (LRS)** firmware and **FieldOps Control** desktop packages.

- [Latest release and downloads](https://github.com/Thanda-Solar/lora-rs-firmware/releases/latest)
- [All releases](https://github.com/Thanda-Solar/lora-rs-firmware/releases)
- [Website, manuals and installation guidance](https://lora.thanda.solar/)

This repository moved from `warwickchapman/lora-rs-firmware` to `Thanda-Solar/lora-rs-firmware`. GitHub redirects the old repository, release and download URLs. Leave the former repository name unused to preserve those redirects.

## Release assets

Each release lists its available assets and release notes. Current releases provide:

- Regional firmware binaries and matching `.upgrade.json` manifests: `433_za`, `433_eu` and `915_us`.
- macOS portable ZIP packages for Apple Silicon and Intel.
- Windows MSI and portable ZIP packages.
- Linux DEB, RPM and AppImage archives.

ZA and EU profiles use 433 MHz; the US profile uses 915 MHz. Select the firmware profile for your installation. Use the published Control application and the manual for installation and upgrade instructions.

If a release provides `SHA256SUMS.txt`, verify downloads with `sha256sum -c SHA256SUMS.txt` on Linux or `shasum -a 256 -c SHA256SUMS.txt` on macOS.

Development source is private. Customer documentation and downloads are available through the public links above.
