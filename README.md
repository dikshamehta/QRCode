# QR Code Scanner Android App

## Overview
This is a simple Android application that allows users to scan QR codes using their device's camera. The app utilizes the **ZXing** library to handle QR code scanning and displays the scanned result in a new activity.

## Features
- Scan QR codes using the device camera.
- Display the scanned QR code content on a new screen.
- Simple and easy-to-use interface.

## Dependencies
Make sure to include the ZXing library in your `build.gradle` file:

```gradle
dependencies {
    implementation 'com.journeyapps:zxing-android-embedded:3.6.0'
}
```

## How to Run
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Open the project in **Android Studio**.
3. Build and run the app on an emulator or a physical device.
4. Click on the **Scan QR Code** button to scan a QR code.
5. The scanned result will be displayed on a new screen.

