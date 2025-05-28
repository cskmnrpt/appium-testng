# Instructions

This repository contains two tests, with one set to fail and also capture a screenshot. The results are automatically reported to Qase.

In the `qase.config.json` file, please update with your project code and API token.

## Dependencies

### Install Appium

- Install Node.js (if not already installed)
- Install Appium using npm:

  ```bash
    npm install -g appium
  ```

- Verify the installation:

  ```bash
    appium -v
  ```

### Install Android driver

- Install the Android driver using npm:
  ```bash
  appium driver install uiautomator2
  ```

- Verify the installation:
  ```bash
    appium driver list --installed
    ```

### Install Android Studio

- Download and install Android Studio from the official website: [Android Studio](https://developer.android.com/studio)
- Install the Android SDK and necessary tools using the SDK Manager in Android Studio.
- Set up the Android emulator
    - Open Android Studio and go to "AVD Manager" (Android Virtual Device Manager).
    - Create a new virtual device with the desired configuration (e.g., Pixel 9, API level 30).
    - Start the emulator.

## Run tests

Appium server automatically starts when you run the tests and connected to the device.
