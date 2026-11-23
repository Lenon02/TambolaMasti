# Tambola Masti – Manipuri RJ Edition

A starter Android app project for Tambola number calling.

## Features
- Random calls from 1 to 90 without repeats
- Number board and calling history
- Repeat and stop voice controls
- Voice language selection (Manipuri if an installed Android voice supports it, plus English India and Hindi)
- GitHub Actions workflow to build a debug APK in the cloud

## Build using GitHub on your phone
1. Create a GitHub repository named `TambolaMasti`.
2. Upload the contents of this ZIP to the repository (not the ZIP file itself).
3. Open the repository's **Actions** tab and allow GitHub Actions if asked.
4. Select **Build Android APK** and tap **Run workflow**, or push files to `main`.
5. When the run completes, open it and download the `tambola-masti-debug-apk` artifact.

## Important
This starter creates a **debug APK** for testing. A Play Store release needs a signed release build and a Play App Signing setup. Do not upload this debug APK as the final Play Store release.

Manipuri text-to-speech depends on whether the Android device/WebView has a compatible Manipuri voice installed. The app offers English (India) and Hindi fallbacks.
