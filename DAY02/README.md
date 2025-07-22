# 🐱‍💻 Installing Kali Linux on Oracle VirtualBox

This guide walks you through installing **Kali Linux**, a popular penetration testing OS, using **Oracle VirtualBox**, a free virtualization tool.

---

## 🔧 Step 1: Install Oracle VirtualBox

1. Go to the [VirtualBox download page](https://www.virtualbox.org/wiki/Downloads).
2. Download the version for your OS (Windows, macOS, Linux).
3. Run the installer and follow the setup wizard.
4. Once done, launch **Oracle VM VirtualBox**.

---

## 📦 Step 2: Download Kali Linux ISO

1. Visit: https://www.kali.org/get-kali/
2. Under “Installer Images”, choose 64-bit ISO.
3. Download the ISO file (approx. 3–4 GB).

---

## 🖥️ Step 3: Create a Virtual Machine (VM)

1. Open VirtualBox and click **"New"**.
2. Set:
   - **Name**: Kali Linux
   - **Type**: Linux
   - **Version**: Debian (64-bit)
3. Click **Next**.

---

## 🧠 Step 4: Assign RAM

- Recommended: **2 GB (2048 MB)** or more.
- Minimum: **1 GB (1024 MB)**

---

## 💾 Step 5: Create Virtual Hard Disk

1. Choose **"Create a virtual hard disk now"**
2. Type: **VDI (VirtualBox Disk Image)**
3. Storage: **Dynamically allocated**
4. Size: **20 GB** or more

---

## 🛠️ Step 6: Configure the VM

1. Select the new VM → click **Settings**.
2. Go to **System** → uncheck **Floppy** under boot order.
3. Go to **Display** → Increase **Video Memory** to **128 MB**.
4. Go to **Storage**:
   - Click **Empty** under “Controller: IDE”
   - Click the CD icon → **Choose a disk file**
   - Select the downloaded **Kali ISO**
5. Click **OK**

---

## 🚀 Step 7: Boot Kali Linux Installer

1. Start the VM.
2. Choose **Graphical Install**.
3. Follow installation steps:
   - Select language, region, keyboard
   - Set hostname (e.g., kali)
   - Create a new user + password
   - Partition disks (select **Guided - use entire disk**)
   - Finish partitioning → Yes to write changes

4. Allow Kali to install system files (takes a few minutes).

---

## 🌐 Step 8: Network & Desktop Setup

- Choose **"Yes"** to use network mirrors (for updates).
- Install **GRUB bootloader** when prompted.

---

## ✅ Final Step: Boot Into Kali

1. After installation completes, **shutdown** the VM.
2. In **Settings → Storage**, remove the ISO from the virtual drive.
3. Start the VM again — Kali should now boot to the **login screen**.

---

## 👤 Login Details

- Username: the one you created (e.g., `kali`)
- Password: the one you set
