# Halo Walk 360: Intimate

This repository contains a minimal Android app that presents a cinematic, intimate 360° walking experience in a local WebView-based scene.

## Run locally

1. Open the project in Android Studio.
2. Let Gradle sync.
3. Choose an Android emulator or a connected device.
4. Run the app.
5. Build an APK from Build > Build Bundle(s) / APK(s) > Build APK(s).

## Files

- `app/src/main/assets/halo_walk_360_intimate/` contains the immersive HTML/CSS/JS scene.
- `app/src/main/java/com/zyngaa/halowalk360/MainActivity.java` loads the scene in a full-screen WebView.

## Notes

This environment does not expose a native Android build toolchain, so an APK binary cannot be generated directly here. The project is set up so that the APK can be produced locally from Android Studio in a standard Android development environment.
