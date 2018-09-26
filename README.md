# macOS Mojave & High Sierra 
##### Hackintosh your Lenovo Ideapad 310-14IKB

## Specifications
2.71 GHz Intel Core i5 7200 Processor, Intel HD Graphics 620 1536 MB Graphics, 8 GB 2133 MHz DDR4 Memory, 120GB Kingston SSD, 1TB WD 5400RMP HDD and BCM94352Z NGFF M.2 Wifi/Bluetooth

## What's not working
1. iMessage
2. Brightness Save on restarts

##  Screenshot

![alt text](https://raw.githubusercontent.com/29satnam/LenovoHackintosh/master/Screenshot.png)

## Clover Config file
https://github.com/RehabMan/OS-X-Clover-Laptop-Config

## Kexts
1. https://github.com/lvs1974/IntelGraphicsFixup
2. https://github.com/vit9696/Lilu
3. https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/
4. https://www.tonymacx86.com/resources/voodootscsync-4-core.285/
5. https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch/tree/master/kexts/AppleBacklightInjector.kext

## Installation
1. Prepare Installation Media using mentioned Kexts and Clover file.
2. Use fake ig-platform-id for installation and bootup: 0x12345678

## Post Installation
1. Use the same fake ig-platform-id for first boot like 0x12345678
2. Install Clover to your macOS drive.
3. Paste kexts to EFI drive and S/L/E
4. Rebuild cache
5. Reboot using default ig-platform-id i.e., 0x591b0000

## Brightness fix
1. https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightinjector-kext.218222/ 
2. https://www.tonymacx86.com/threads/fixing-brightness-with-custom-edid.219413/ 
3. https://bitbucket.org/RehabMan/os-x-acpi-battery-driver/downloads/  

## TouchPad Multi-Gesture fix
- http://forum.osxlatitude.com/index.php?/topic/1948-elan-focaltech-and-synaptics-smart-touchpad-driver-mac-os-x/
- Or you can simply pair up a Magic Trackpad and that will open up the settings of Trackpad in System Prefrences and you can setup according to your needs.

## Battery Status fix
1. https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/
2. https://github.com/RehabMan/OS-X-ACPI-Battery-Driver

## Power Management
https://github.com/Piker-Alpha/ssdtPRGen.sh

## Wireless
https://www.aliexpress.com/item/WiFi-Wireless-Network-Card-BCM94352Z-NGFF-M-2-Wifi-Bluetooth-4-0-06XRYC-DW1560-802-11AC/32810080278.html?spm=a2g0s.9042311.0.0.14b74c4dUhR2Ql

## Fix Sleep/Wake display glitch:
https://www.tonymacx86.com/threads/solved-intel-hd-620-high-sierra-sleep-wake-problem.233174/page-4#post-1637263


## Important Note
If you've got exactly same Laptop model, you can just simply use the EFI zip posted above and if you have even a slightly different model this isn't for you.
