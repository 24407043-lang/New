# How to Install Auto Beauty Camera (.APK)

### Method 1: Direct Install on Android Phone
1. Tap **Download .APK** in the studio to download `AutoBeautyCamera.apk`.
2. Transfer or download the APK file onto your Android device.
3. Open your device's **Files** or **Downloads** app.
4. Tap **AutoBeautyCamera.apk**.
5. When prompted with *Install Unknown Apps*, go to **Settings** and toggle **Allow from this source**.
6. Tap **Install** to complete the installation.
7. Launch the app and grant the **CAMERA** permission when prompted.

### Method 2: Install via ADB (Android Debug Bridge)
If your phone is plugged in with USB debugging enabled:
```bash
adb install -r AutoBeautyCamera.apk
```

### Method 3: Compile Fresh APK from Source
```bash
./gradlew assembleDebug
```
The generated APK file will be located at:
`app/build/outputs/apk/debug/app-debug.apk`
