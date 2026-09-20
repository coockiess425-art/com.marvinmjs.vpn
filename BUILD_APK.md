# Build MarvinMJS

Requirements:
- Android Studio with Android SDK Platform 36 installed
- JDK 17+ (Android Studio's bundled JDK is recommended)
- Internet access for Gradle/Maven dependencies

Open this directory in Android Studio, allow Gradle sync to finish, then run:

```bash
./gradlew assembleDebug
```

The debug APK is produced at:

`app/build/outputs/apk/debug/app-debug.apk`

For a release APK, configure an Android signing key in Android Studio and use `assembleRelease`.

The bundled SA WireGuard files are templates. Replace their placeholder keys and endpoint with a server you own or are authorized to use before connecting.
