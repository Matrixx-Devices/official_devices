<img src="https://raw.githubusercontent.com/Matrixx-Devices/official_devices/14.0/images/installation.png" />

# Before start flashing...
- I recommend you to use Matrixx aosp recovery. Use custom recovery at your own risk.


## Gapps variant

**Clean flash:**

1.) Download The Boot , Dtbo  And Vendor_boot Images  

2.) Connect To Pc

3.) Reboot To Fastboot  (  Press  Both Power_button_key + Vol_down_key)

4.) fastboot flash boot boot.img

5.) fastboot flash vendor_boot  vendor_boot.img

6.) fastboot flash dtbo dtbo.img 

7.) fastboot reboot recovery

8.)Select Wipe Data/factory Reset & Confirm

9.) Select 'apply Update' From Adb

10.) adb sideload  Rom_Name.zip

11.) Select Wipe Data/factory Reset & Confirm

12.) After Installation Complete, Reboot System.


**Dirty flash:**

1. Reboot to recover by holding power button and volume up simultaneously

2. In the recovery menu select Apply update through ADB

3. adb sideload Rom*.zip(or drag down the rom zip to cmd)

4. After installation complete, Reboot system.