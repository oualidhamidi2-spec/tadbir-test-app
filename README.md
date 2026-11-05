# Tadbir Test: the Android test app

The Android app of Tadbir's test environment (https://chantier-sync-pro-staging.vercel.app), for testers. It isn't on the Play Store yet.

## Install

1. On the Android phone, open this link and download the app:
   https://github.com/oualidhamidi2-spec/tadbir-test-app/releases/latest/download/tadbir-test.apk
2. Open the downloaded file. When Android asks, allow this browser to install apps.
3. A newer version installs over the old one and keeps you signed in.

The link always gives the newest version. Each release says what changed.

## Checking the file

Every version is signed with the same key. Its certificate's SHA-256 fingerprint is:

```
9A:9C:4F:71:C0:BF:85:55:B9:2C:45:F0:A0:DC:F2:88:5D:F3:E8:AB:C0:40:85:AC:C2:21:9D:E8:6A:5D:8C:CE
```

Android refuses an update signed with another key. Each release also gives its file's SHA-256.
