# Newflix2 Launcher APK

A simple Android app that opens your browser directly to Newflix2.

## How to Build

### Automatic (GitHub Actions)
1. Push this repo to GitHub
2. Go to Actions tab
3. Run "Build APK" workflow
4. Download the APK from Artifacts

### Manual (Android Studio)
1. Open this folder in Android Studio
2. Build > Build Bundle(s) / APK(s) > Build APK(s)
3. Find APK in `app/build/outputs/apk/debug/`

## Configuration

Edit the URL in `app/src/main/java/com/newflix2/launcher/MainActivity.java`:
```java
private static final String NEWFLIX2_URL = "https://your-url-here.com";
```
