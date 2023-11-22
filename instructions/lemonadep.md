# Before start flashing…..
- Backup all your data to any external source.
- Update your device to OOS 13.1
- Gapps included so no need to flash/sideload GApps

# Clean Flash:
- Extract recovery package zip
- Reboot to bootloader & connect your phone to PC
- Double click on flash.bat
- Reboot to recovery & Factory reset > Format data/factory reset
- Back to recovery home page & tap > Apply update > Apply from ADB
- Now sideload rom using command adb sideload <rom_filename>.zip
- Now reboot to system.

# Rom Update/Dirty flash:
- Reboot to recovery
- Apply update > Apply from ADB
- Open command prompt & sideload rom using command adb sideload <rom_filename>.zip
- Reboot

