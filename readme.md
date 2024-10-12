# Android Mirroring (v2.7) - SVECTOR

# PREVIEW


<br>
<img src="https://firebasestorage.googleapis.com/v0/b/svector-cloud.appspot.com/o/files%2FScreenshot%202024-10-12%20at%206.57.47%E2%80%AFPM.png?alt=media&token=14a4a94e-c149-4aeb-b546-00dda10b7537" width="370" height="460" alt="Android Mirroring"  />


# Overview 

<img src="https://firebasestorage.googleapis.com/v0/b/svector-cloud.appspot.com/o/files%2Ficon.svg?alt=media&token=c43dc2e0-e203-4f3d-8c4e-41e0efdb99f8" width="128" height="128" alt="Android Mirroring" align="right" />

**Android Mirroring** is a powerful application that allows you to mirror your Android device's screen and audio to your computer. It supports USB and wireless connections, enabling seamless interaction using your keyboard and mouse.

## Key Features
- **Lightweight and fast performance**
- **High frame rates**: 30~120fps, based on device capability
- **High resolution**: Up to 1920×1080 or higher
- **Low latency**: 35~70ms
- **Non-intrusive**: No installation required on the Android device

## Download and Installation

### Step 1: Download
1. **Visit the official website** at [SVECTOR Android Mirroring](https://calculus.svector.co.in/f/cZsxVf) to download the ZIP file.
2. Click on the **Download** button for the latest version (v2.7) to start downloading the ZIP file.

### Step 2: Extract the ZIP File
1. Once the download is complete, locate the downloaded ZIP file in your `Downloads` folder or the designated download location.
2. Right-click on the ZIP file and select **Extract All** (or use an extraction tool like WinRAR or 7-Zip).
3. Choose a destination folder where you want to extract the files and click **Extract**.

### Step 3: Installation on macOS
1. **Open Terminal**.
2. **Navigate to the extracted folder**:
   ```bash
   cd path/to/extracted-folder
   ```
3. **Install the application**:
   ```bash
   sudo ninja -Candroid-mirroring-mac install
   ```
4. **Run the application**:
   ```bash
   android-mirroring
   ```

### Note for Windows Users
Windows support is currently under development.

## Wireless Connection Setup
To connect wirelessly, ensure that your Android device and computer are on the same Wi-Fi network. Follow these steps:

1. **Connect** your Android device to your computer via USB.
2. **Enable USB debugging** on your Android device.
3. In the Terminal, execute the following command:
   ```bash
   adb tcpip 5555
   ```
4. **Disconnect** the USB cable.
5. **Find your Android device's IP address** (you can find it in the device’s Wi-Fi settings).
6. **Connect** to your device using the command below, replacing `your-ip-address` with the actual IP:
   ```bash
   adb connect your-ip-address:5555
   ```
7. **Launch Android Mirroring**:
   ```bash
   android-mirroring
   ```

## Support
For support, feature requests, or inquiries, please contact us at [support@svector.co.in](mailto:team@svector.co.in).

## License
Copyright © 2024 SVECTOR. All rights reserved. Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0). Unauthorized copying, reproduction, or distribution is prohibited.
