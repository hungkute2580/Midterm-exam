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

## Installation & Initialization
```sh
npm install
npx cap init MyApp com.example.myapp
npm install @capacitor/local-notifications @capacitor/share @capacitor/battery
npx cap sync
# Run on Android
npx cap add android
npx cap sync android
npx cap open android # Open Android Studio, select the device and press Run

# Run on iOS (Only on macOS)
npx cap add ios
npx cap sync ios
npx cap open ios # Open Xcode, select the device and press Run

# Note
- **Android**: Enable **USB Debugging** if running on a real device.
- **iOS**: Need to enable **Local Notifications** and **Share API** permissions in `Info.plist`.

# If you get an error, try:
npx cap sync
npx cap doctor
