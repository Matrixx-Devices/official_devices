<img src="https://raw.githubusercontent.com/Matrixx-Devices/official_devices/14.0/images/installation.png" />

# Before start flashing...
- Backup all your data to any external source
- If using custom rom, Make sure you're using OOS 12 base
- If you're on OOS, update to OOS 12
- Gapps included so no need to flash/sideload GApps

# Clean Flash:
- Download recovery image
- Reboot to bootloader & connect your phone to PC
- type command ```fastboot flash recovery recovery.img```
- Reboot to recovery & Factory reset > Format data/factory reset
- Back to recovery home page & tap > Apply update > Apply from ADB
- Now sideload rom using command ```adb sideload <rom_filename>.zip```
- Now reboot to system.

# Rom Update/Dirty flash:
- Reboot to recovery
- Apply update > Apply from ADB
- Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
- Reboot
