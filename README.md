# Tadbir: the Android app

The Android app of Tadbir (https://tadbirapp.net). It isn't on the Play Store yet.

## Install

1. On the Android phone, open this link and download the app:
   https://github.com/oualidhamidi2-spec/tadbir-test-app/releases/latest/download/tadbir.apk
2. Open the downloaded file. When Android asks, allow this browser to install apps.
3. A newer version installs over the old one and keeps you signed in.

The link always gives the newest version. Each release says what changed. Each release also carries the same file as `tadbir-test.apk`, the address this page gave before.

## Coming from Tadbir Test

Until 8 November 2026 this page gave "Tadbir Test", the app of Tadbir's test environment (package `com.chantiersyncpro.app.test`). Tadbir is another app (package `com.tadbirapp.app`): it installs next to Tadbir Test instead of over it. Sign in to Tadbir, then remove Tadbir Test.

## Checking the file

Every version of Tadbir is signed with the same key. Its certificate's SHA-256 fingerprint is:

```
D0:55:A3:04:E9:16:17:49:09:EF:28:2E:5E:24:F8:7E:13:96:4D:53:95:04:6D:DF:B9:F2:8D:F2:6E:E3:77:B5
```

Android refuses an update signed with another key. Each release also gives its file's SHA-256.

Tadbir Test (up to version 15) was signed with another key, `9A:9C:4F:71:C0:BF:85:55:B9:2C:45:F0:A0:DC:F2:88:5D:F3:E8:AB:C0:40:85:AC:C2:21:9D:E8:6A:5D:8C:CE`.
