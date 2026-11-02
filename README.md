# DentAxis APK Releases

Public update channel for the DentAxis Android app.

- **Download the latest APK** from [Releases](https://github.com/MohOneX/DentAxis-APK-Releases/releases)
- The app checks this repo for updates automatically
- Source code stays in a private repository

## Install

1. Download `DentAxis-x.y.apk` from the latest release
2. Allow install from unknown apps if Android asks
3. Open the APK

## For maintainers

Each release must:

1. Increase `versionCode` in the app build
2. Include `versionCode: N` as the first line of the release notes
3. Attach a release-signed `.apk` (same signing key every time)