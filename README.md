# Android CameraX Auto Beauty Camera

Real-time beauty camera native Android app using:
- **CameraX 1.3.4** for modern, lifecycle-aware preview & analysis pipelines
- **CyberAgent GPUImage 2.1.0** with custom GLSL bilateral edge-preserving smoothing
- **Google ML Kit Face Detection 16.1.7** for accurate facial contours & feature tracking
- **Material Design 3** toggle button and animated intensity slider

## How to Build the APK
Run in your terminal:
```bash
./gradlew assembleDebug
```
The generated APK will be at:
`app/build/outputs/apk/debug/app-debug.apk`

Install to connected phone:
```bash
adb install -r app/build/outputs/apk/debug/app-debug.apk
```
