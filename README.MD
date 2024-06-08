# DayNight-KMP
![DayNight-KMP](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/poster.png)
DayNight-KMP is a demo version of Dark & Light Theme with Trandational Sun & Moon UI. It contains the Container UI & Switch UI Too. It uses the `day-and-night-switch` Library.

## Mobile Screen Shots
| ![Screenshot 1](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/1.png) | ![Screenshot 2](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/2.png) ||
| --- | --- |

## Desktop Screen Shots

| ![Screenshot 1](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/3.png) | 
| --- |
| ![Screenshot 2](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/4.png) | 

## Web Screen Shots
| ![Screenshot 1](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/5.png) | 
| --- |
| ![Screenshot 2](https://github.com/KhubaibKhan4/DayNight-KMP/blob/master/assests/screenshots/6.png) | 

## Before running!
 - check your system with [KDoctor](https://github.com/Kotlin/kdoctor)
 - install JDK 17 or higher on your machine
 - add `local.properties` file to the project root and set a path to Android SDK there

### Android
To run the application on android device/emulator:  
 - open project in Android Studio and run imported android run configuration

To build the application bundle:
 - run `./gradlew :composeApp:assembleDebug`
 - find `.apk` file in `composeApp/build/outputs/apk/debug/composeApp-debug.apk`
Run android simulator UI tests: `./gradlew :composeApp:pixel5Check`

### Desktop
Run the desktop application: `./gradlew :composeApp:run`
Run desktop UI tests: `./gradlew :composeApp:jvmTest`

### iOS
To run the application on iPhone device/simulator:
 - Open `iosApp/iosApp.xcproject` in Xcode and run standard configuration
 - Or use [Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile) for Android Studio
Run iOS simulator UI tests: `./gradlew :composeApp:iosSimulatorArm64Test`

### Wasm Browser (Alpha)
Run the browser application: `./gradlew :composeApp:wasmJsBrowserDevelopmentRun --continue`
Run browser UI tests: `./gradlew :composeApp:wasmJsBrowserTest`

