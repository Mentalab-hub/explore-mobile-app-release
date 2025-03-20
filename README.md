# Mentalab Explore Mobile App
The Mentalab Explore Mobile App is a cross-platform application designed to interface seamlessly with Mentalab’s ExG devices, enabling users to record and visualize biosignals in real time. 
Developed with portability and accessibility in mind, the app supports both iOS and Android platforms, allowing researchers and professionals to connect to Mentalab ExG devices via latest Bluetooth technology(BLE). 
Users can monitor, manage, and export data from EEG, ECG, EMG, and other bioelectrical signals directly from their mobile devices, making it an ideal tool for applications in neurofeedback, clinical research, and mobile health monitoring.

We also offer a flexible and cross platform mobile API for developers and reserachers. Please contact [mentalab support](mailto:contact@mentalab.com) for more documentation and technical details.

<p align="left">
    <img src="images/Homepage.jpg" alt="Homepage" width="300">
</p>

## Download and install
For any information or assistance, please contact support@mentalab.com and we will assist you further.

### Android:
- You can download the .apk file from here: [Android](https://github.com/Mentalab-hub/explore-mobile-app-release/releases/latest)

### iOS:
- Available on the [App Store](https://apps.apple.com/app/mentalab-explore/id6636486425)

## Features:

- Scan and connect to nearby Explore devices.
- Visualize real-time impedance data.
- Visualize ExG data and apply filters in real time.
- Record raw ExG data in csv format.
- Adjust device settings.
  
<p align="left">
    <img src="images/Impedance.jpg" alt="Impedance visualization" width="300">
</p>

<p align="left">
    <img src="images/ExG.jpg" alt="Exg visualization" width="300">
</p>

## Tests
Following are the devices we used to testing:

| Device            | OS version |
|-------------------|------------|
| Lenovo Tab M9     | Android 13 |
| Samsung S23 Ultra | Android 14 |
| Zenfone 10        | Android 14 |
| Pixel 7 Pro       | Android 15 |
| iPhone 13         | iOS 18     | 

### Recording Tests

Conducted on **Lenovo Tab M9 (Android 13)** for 2 hours:

- ✅ 16 channels at 500 Hz sampling rate
- ✅ 16 channels at 250 Hz sampling rate

## Known bugs:
- The following sampling rates are supported only in Android: 8 channels 1000Hz, 16 channels at 500 Hz, 32 channels at 250 Hz.
- When assigning channels in the impedance view and then disconnecting/reconnecting, the existing head montage remains instead of being cleared.
- The time window of the ExG visualization is not affected by changes in the sampling rate.


## Disclaimer:
The Mentalab Explore Pro app and hardware are intended strictly for research and educational applications.
