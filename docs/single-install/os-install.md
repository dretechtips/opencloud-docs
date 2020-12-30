# Recommended Operating System Installation

The programs will be running on [TrueNAS CORE OS](https://www.truenas.com/truenas-core/) which is based on FreeBSD. For more information please visit the website to see the requirements of this OS.

## Why TrueNAS CORE?
TrueNAS has an excellent web GUI to manage storage. TrueNAS CORE also runs FreeBSD jails, which allows for containerization of software. Containerization is necessary in this situation because there's a lot of components that could potentially break and thus isolating each one would prevent problems from getting out of hand.

## Required Hardwares
- USB Pen Drive
- A second USB Pen Drive, Small SSD or Hard Drive
- Machine with at least 8GB of RAM and a fairly modern CPU
- A single or multiple Hard Drives and or SSDs

## 1. Flashing to USB

**WINDOWS**

Use [Rufus](https://rufus.ie/) with default settings to flash the ISO onto a USB stick

**MacOS/Linux/BSD**

Find USB Drive
```bash
# MacOS
diskutil list
# Linux / BSD
lsblk
```

Flash ISO into USB Drive
```bash
# Wipes USB drive
mkfs.ext4 [DEVICE_PATH]
# Flashes ISO into USB drive
dd if="[ISO_PATH]" of="[DEVICE_PATH]" status="progress"
```

## 2. Flash ISO from USB TO USB/SSD
TrueNAS CORE can be installed on a hard drive, however it should be installed on a small SSD or a high quality USB stick with a minimum capacity of 16GB. Boot into the first USB with the flash ISO. Insert the second USB drive if a second USB drive will be the installation target. Insert the admin username and password. Select the second drive for installation and reboot once finished. While rebooting take out the first drive.

## Detailed Installation
https://www.youtube.com/watch?v=GjalxUIu4MA
