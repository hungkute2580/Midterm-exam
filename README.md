## Nguyen Quoc Hung - 22IT.B099
## Birthday Countdown - Capacitor App
# Introduction
The Birthday Countdown app is built with Capacitor to help users calculate the number of days left until the next birthday. The app also supports useful features such as local notifications, sharing results and displaying battery status.
# Key Features
Enter the date of birth in dd/mm format.
Calculate the number of days left until the next birthday.
Local notifications using Local Notifications.
Share countdown results using Share API.
Display the battery status of the device.
# Technology used
Capacitor (Core, Local Notifications, Share, Battery)
HTML, CSS, JavaScript
Runs on Android and iOS
# How to Run Capacitor App on Android & iOS

## Requirements
- **Node.js & npm** ([Download here](https://nodejs.org/))
- **Capacitor CLI** (`npm install -g @capacitor/cli`)
- **Android Studio** (Android)
- **Xcode** (iOS, macOS only)

# How to run Capacitor app on Android

## Requirements
- Node.js and npm (https://nodejs.org/)
- Capacitor CLI (install with `npm install -g @capacitor/cli`)
- Android Studio (https://developer.android.com/studio)

## How to run the app

1. **Clone repository**
```sh
git clone https://github.com/hungkute2580/Midterm-exam.git
cd Midterm-exam
```

2. **Install dependencies**
```sh
npm install
```

3. **Add Android platform** (if not already)
```sh
npx cap add android
```

4. **Sync project**
```sh
npx cap sync android
```

5. **Open project on Android Studio**
```sh
npx cap open android
```

6. **Run the app on the device/emulator**

- Click "Run" on Android Studio or use the command:
```sh
npx cap run android
```

## Note
- Check the connected device/emulator before running.

- If there is an error related to Gradle, check the Android Studio settings and update the appropriate SDK.

- For debugging, you can use `adb logcat` or Chrome's DevTools.

---
Wish you run the app successfully!
