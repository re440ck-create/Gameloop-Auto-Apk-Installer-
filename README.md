# 🛠️ Gameloop Auto APK Installer (ADB) v1.0.0

A simple, fast, and automated tool to bulk-install `.apk` files directly onto Gameloop via ADB.

---

## 📋 Step-by-Step Guide

1. **Initialize Emulator System Files**
   Install any app from the built-in Store (such as **QQ**) and launch it once so the emulator generates all required Android system files and ADB components.

2. **Prepare the Folder**
   Place the `install_apks.bat` script inside the same folder where your `.apk` files are stored.

3. **Run the Script**
   Keep the Gameloop emulator running, then double-click `install_apks.bat` to launch the automated process.

4. **Monitor Progress**
   Wait for the script to test the ADB connection and inject the packages. A summary report will display the final installation status upon completion.

---

## 📌 Usage Instructions

* **Universal Compatibility:** Works with all versions and builds of Gameloop (32-bit & 64-bit).
* Keep Gameloop open in the background to ensure ADB connection stability during injection.
* To install new `.apk` files in the future, simply place them in the same directory and execute the script again.
