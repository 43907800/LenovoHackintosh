## macOS Mojave & High Sierra 
### Hackintosh your Lenovo Ideapad 310-14IKB

![alt text](https://raw.githubusercontent.com/29satnam/LenovoHackintosh/master/Screenshot.png)

- Clover Config file:

https://github.com/RehabMan/OS-X-Clover-Laptop-Config

- Kexts:

1. https://github.com/lvs1974/IntelGraphicsFixup

2. https://github.com/vit9696/Lilu

3. https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/

4. https://www.tonymacx86.com/resources/voodootscsync-4-core.285/

5. https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch/tree/master/kexts/AppleBacklightInjector.kext


- Installation:

Prepare Installation Media using mentioned Kexts and Clover file.

Use fake ig-platform-id for installation like 0x12345678

- Post Installation:

Step 1: Use the same fake ig-platform-id for first boot like 0x12345678

Step 2: Install Clover to your macOS drive.

Step 3: Paste kexts to EFI drive and S/L/E

Step 4: Rebuild cache

Step 5: Reboot using default ig-platform-id i.e., 0x591b0000


- Brightness fix:

Step 1: https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightinjector-kext.218222/ 
Step 2: https://www.tonymacx86.com/threads/fixing-brightness-with-custom-edid.219413/ 
Step 3: https://bitbucket.org/RehabMan/os-x-acpi-battery-driver/downloads/  

- TouchPad Multi-Gesture fix:

http://forum.osxlatitude.com/index.php?/topic/1948-elan-focaltech-and-synaptics-smart-touchpad-driver-mac-os-x/

- Battery Status Fix

Step 1: https://www.tonymacx86.com/threads/guide-how-to-patch-dsdt-for-working-battery-status.116102/
Step 2: https://github.com/RehabMan/OS-X-ACPI-Battery-Driver

- Power Management

https://github.com/Piker-Alpha/ssdtPRGen.sh

- Wireless

Replace chip with a BCM94352Z

If you've got same Laptop model you can just simply use the EFI folder posted above.

- Fix Sleep/Wake display glitch:

Fix: https://www.tonymacx86.com/threads/solved-intel-hd-620-high-sierra-sleep-wake-problem.233174/page-4#post-1637263

