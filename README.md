# Rule 34 Android App
An app to browse https://rule34.xxx on Android by using Cordova.

# License
This project is licensed under the same license as Cordova which is the [Apache-2.0](./LICENSE) license.

# Building
This project uses Apache Cordova to generate an Android Gradle project and compile a debug APK.

## Requirements
- Node.js  
- Cordova CLI (`npm install -g cordova`)  
- Java JDK 11 or 17  
- Android SDK  

---

## 1. Install dependencies
```bash
npm install
```

## 2. Generate the Android Gradle project
```bash
cordova platform add android
```

This creates the full Gradle project under `platforms/android/`.

---

## 3. Build a debug APK
```bash
cordova build android --debug
```

The APK will be located at:
```
platforms/android/app/build/outputs/apk/debug/app-debug.apk
```

- SSMG4


