# ThinkCentre-M900-hackintosh
[![11](https://img.shields.io/badge/macOS-11-red.svg)]()
[![12](https://img.shields.io/badge/macOS-12-blueviolet.svg)]()
[![13](https://img.shields.io/badge/macOS-13-yellow.svg)]()
[![14](https://img.shields.io/badge/macOS-14-orange.svg)]()
[![download](https://img.shields.io/badge/Download-latest-success.svg)](https://github.com/corpGibbron/ThinkCentre-M900-hackintosh/releases/latest)


![lenovo-tc-m900-sff-intel6000-1587705261](https://github.com/corpGibbron/ThinkCentre-M900-hackintosh/assets/99252438/a5511ad8-8f8a-49be-b489-c601e5a6ba82)


ThinkCentre M900 Hackintosh EFI.

Please have basic information about OpenCore, information about your hardware.
Do not point a finger at me if you mess up and brick your device I won't be responsible for any data loss or any other type of loss.

You can find how to setup a USB here: https://dortania.github.io/OpenCore-Install-Guide/installer-guide/

You can find the BIOS settings here: https://dortania.github.io/OpenCore-Install-Guide/config.plist/skylake.html#cleaning-up

# Basic Requirements
CPU: i5-6400

Storage: SSD 

RAM: 4GB AND ABOVE

BIOS settings **[This is crucial and if not like shown in the OpenCore Guide you won't be able to boot into your USB]**

# Reccomended Hardware
CPU: i7-6700 3.40GHZ

Storage: NVME m.2 SSD

RAM: 16GB

Master at OpenCore

# Please don't consider downloading this EFI and using if you're too lazy to build your own!!


# Installation 

1. Plug in your desired USB into the machine
2. Keep pressing F12 on your keyboard until Boot Menu pops up
3. Select the USB you've made
4. Navigate to it and press enter 
5. Now, where many users get confused press space bar and you'll find YOURUSB(external)(dmg) boot option in the OpenCore boot menu.
6. Wait until the recovery loads
7. Go to Disk Utility
8. Select your disk and format it as APFS and GUID partition Table.
Something like this:
![image](https://github.com/corpGibbron/ThinkCentre-M900-hackintosh/assets/99252438/054225ff-bb83-4f12-998f-1fa4e2402623)
9. Now that you've erased the disk as APFS you can click on install macOS Monterey and wait until it installs.
10. Boom! You're ready to setup macOS and use it!

# Credits
Thanks to:

Apple (macOS)

Acidanthera (OpenCore, VirtualSMC, Lilu, WhateverGreen and a lot more)

Dortania (Opencore Install Guide, Opencore Legacy Patcher)

chris111 (Wireless-USB-Big-Sur-Adapter)
