# EPADD for Android

Official APK downloads for the Rural Agricultural Development Authority's Executive Performance, Accountability and Delivery Dashboard.

[**Download the latest Android APK**](https://github.com/duanehendricks/EPADD_RELEASE/releases/latest/download/epadd.apk) · [Release notes and checksums](https://github.com/duanehendricks/EPADD_RELEASE/releases/latest)

## Install

1. Download `epadd.apk` on your phone.
2. Open the download and allow installation from your browser or Files app when Android prompts.
3. Install, then sign in with your authorized EPADD account.

Requires Android 8.0 or newer. Updates are installed by downloading and opening the newer APK; future production versions use the same signing identity and retain app data during an in-place update.

## Moving from a QA/debug build

The first production release uses a new production signing certificate. Android cannot update an older QA/debug installation in place. Submit pending work and coordinate the transition before removing QA: uninstalling deletes local drafts, saved sign-in data and biometric setup. Do not uninstall to resolve a signing mismatch on later production updates; contact your administrator.

## Verify a download

Every release contains `SHA256SUMS.txt` and `release.json`, including the APK hash, version and signing certificate fingerprint. The production signing certificate SHA-256 is:

```text
82a3e7796d7544e4d3b22a443e105628a7f82483ad343b3e7ce19ace2a83721d
```

This public repository distributes APKs and release information. Application source and signing credentials are maintained separately. Physical-device acceptance for each release is coordinated by the EPADD administrator.