# MapaAurHum - Android App (Decompiled)

This repository contains the decompiled source of the **MapaAurHum** Android application.

## App Info

| Field | Value |
|-------|-------|
| App Name | MapaAurHum |
| Package | com.mapaaurhum |
| Version | 1.0.1 (Build 12) |
| Min SDK | Android 6.0 (API 23) |
| Target SDK | Android 15 (API 35) |
| Framework | Flutter |

## Permissions

- INTERNET, ACCESS_NETWORK_STATE
- CAMERA
- RECORD_AUDIO
- READ/WRITE_CONTACTS
- READ/WRITE_EXTERNAL_STORAGE
- CALL_PHONE
- POST_NOTIFICATIONS
- VIBRATE, WAKE_LOCK

## Tech Stack

- **Flutter** (cross-platform UI framework)
- **Firebase** (FCM push notifications, messaging)
- **ML Kit** (OCR / text recognition - Devanagari & Latin scripts)
- **Google Sign-In**
- **flutter_inappwebview** (in-app browser)
- **YouTube Player**
- **image_picker**, **camera**

## Structure

```
assets/flutter_assets/      # Flutter UI assets, images, fonts
assets/mlkit-google-ocr-models/  # ML OCR models
res/                        # Android resources
lib/                        # Native libraries (.so)
AndroidManifest_decoded.xml # Decoded app manifest
```

## Note

This is a reverse-engineered decompilation for recovery/reference purposes.
The Flutter Dart source code is compiled into `lib/arm64-v8a/libapp.so` and cannot be recovered as text without a Dart snapshot decompiler.
