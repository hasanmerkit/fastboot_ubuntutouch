# 📱🐧 Ubuntu Touch Fastboot ROM - Poco X3 NFC (surya)

**Source / Kaynak:** [teteos.net](https://www.teteos.net/d/685-ubuntu-touch-2404-rom-for-poco-x3-nfc-surya)

An offline-installable fastboot ROM of Ubuntu Touch (24.04), designed to be flashed directly without the UBports Installer.

> ⚠️ **Warning:** Proceed at your own risk. Flashing this ROM will wipe your data and carries a risk of bricking your device. 

## ✨ Features
* **Auto-RW for Root:** Automatically remounts `/` as read/write when switching to the `ROOT` user.
* **Pre-installed Tools:** Includes essential dev packages like `waydroid`, `git`, `gcc`, `cmake`, `nano`, and various extraction tools out of the box.
* **APT Packages:** Updated as of 29.05.2026.

## 🚀 Installation
1. Ensure your device **bootloader is unlocked**.
2. Boot the phone into fastboot mode.
3. Execute `flash_all.sh` (Linux/Mac) or `flash_all.cmd` (Windows).

*Note: If you plan to revert to Android later, avoid flashing "MiUi Global V14.0.2.0.SJGMIXM" directly. Flash "MiUi Indo V14.0.2.0.SJGIDXM" or "MiUi Global V12.0.9.0.QJGMIXM" first to prevent boot issues.*
