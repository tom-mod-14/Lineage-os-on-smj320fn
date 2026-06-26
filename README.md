# Lineage-os-on-smj320fn
# LineageOS 14.1 Installation Guide for Samsung Galaxy J3 2016 (SM-J320FN)

This guide explains how to install Unofficial LineageOS 14.1 (Android 7.1.2) on the Samsung Galaxy J3 2016 (SM-J320FN). 

> ⚠️ **WARNING:** This process will wipe all data on your phone. Make a backup before proceeding. Proceed at your own risk.

## 💾 Download Required Files
All necessary files (Odin, TWRP, LineageOS ROM, and Google Apps) are hosted and maintained in this working mirror:
👉 **[Google Drive Folder Link](https://drive.google.com/drive/u/0/mobile/folders/1C_kKI_V_3gYtCjWfArFauA0ysDqu6LhC?usp=sharing)**

---

## 🛠️ Step-by-Step Instructions

### Step 1: Preparation & Download Mode
1. On your phone, remove your **Google Account** to avoid FRP lock.
2. Enable **Developer Options** (Go to Settings > About Phone > Tap *Build Number* 7 times).
3. Open Developer Options and enable **USB Debugging** and **OEM Unlock** (if present).
4. Power off the phone completely.
5. Boot into **Download Mode** by pressing and holding simultaneously: `Volume Down + Home + Power`.
6. Press `Volume Up` on the warning screen to confirm.
7. Connect the phone to your PC via USB.
8. Open **Odin** as Administrator on your PC. Ensure the `ID:COM` box in the top-left turns blue (device detected).

### Step 2: Flashing TWRP Recovery
1. In Odin, click on the **AP** button and select the downloaded `twrp-3.7.0_9-0-j3xlte.tar` file.
2. Go to the **Options** tab in Odin and **uncheck "Auto Reboot"**.
3. Click **Start** and wait until the progress bar on the phone finishes and Odin shows a green **"PASS"** message.
4. Unplug the phone, **remove the battery**, and put it back in.

### Step 3: Formatting and File Transfer
1. Boot into **TWRP Recovery** by holding down: `Volume Up + Home + Power`.
2. As soon as the Samsung logo appears, **release the Power button** but keep holding the others.
3. Once in TWRP, swipe to allow modifications.
4. Go to **Wipe** > **Format Data**, type `yes` and confirm.
5. Connect the phone to the PC. The internal storage will now appear empty.
6. Copy the LineageOS `.zip` file and the GApps folder/files from your PC to the phone's internal storage.

### Step 4: Flashing the ROM & GApps
1. In TWRP, go to **Install**, select the LineageOS `.zip` file, and swipe to flash.
2. Once finished, go **Back**, select the GApps file, and flash it.
3. After both are installed, tap **Wipe Cache/Dalvik**.
4. Tap **Reboot System** and wait for LineageOS to boot up.

---
Enjoy your fast, clean, and de-bloated smartphone! 🚀
