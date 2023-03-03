# If you have an old version installed, and you don’t want to lose your data, how you install a new .apk file?
If you have an old version of an Android app installed on your device and you want to install a new version of the app without losing your data, you can use the following steps:

1. Download the new version of the app: Download the new version of the app in the form of an APK file.

2. Connect the device to your machine: Use a USB cable to connect the device to your machine. Make sure that USB debugging is enabled on the device.

3. Install the new version of the app: Use the Android Debug Bridge (ADB) tool to install the new version of the app on the device. To do this, open a terminal or command prompt and navigate to the directory where the Android SDK is installed. Then, use the following ADB command:

            adb install -r <path-to-apk-file>
      
      The <code>-r</code> flag indicates that the app should be installed and the existing data should be kept.

      For example:

            adb install -r app.apk

4. Test the app: After installing the new version of the app, it is important to test it to ensure that it is functioning correctly and that your data has been preserved. This might involve manually interacting with the app and verifying that it behaves as expected, or using automated testing tools and frameworks to execute a series of tests on the app.

Overall, using ADB to install a new version of an Android app while preserving the existing data can be a convenient and efficient way to update an app on a device, particularly during the development and testing process.
