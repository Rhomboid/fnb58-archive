# FNIRSI FNB58 USB Tester

This is an unofficial archive of firmware, software, and manuals for the FNIRSI FNB58 USB Tester.

## Quick FAQ

### How do I upgrade the firmware?

1. Unzip the software somewhere on your PC. There is no installer, it acts like a portable application that you can place anywhere and just run.
2. Run the software, and connect a Micro USB cable to the PC.
3. Boot the FNB58 into bootloader mode: Hold down the 'middle' button (center press the back/forward toggle button) while powering the unit by plugging the Micro USB cable into the *top* port labeled PC.
4. The software should automatically recognize the device. Click on the 'System' tab, ensure that it says 'Operating mode: bootloader'.
5. Click on the 'open file' icon (yellow folder) and navigate to the .ufn file for the firmware you want to install.
6. Click the 'upgrade' icon (green recycle arrows) and wait.

### How to deal with PD detection loops?

The best way I've found is to power the unit from the PC port (top side Micro USB) when attempting to detect PD. This lets the tester remain powered while cycling the voltage of the USB C port, which seems more reliable than having to reboot.

