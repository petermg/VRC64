

## REAL COMMODORE 64 (Virtually) - Oculus Go, Oculus Quest, Gear VR, (and possibly DayDream and cardboard? requires 3DoF controller)

### Install

See _Releases_ for APK Download.

* You need `adb` (from Android platform tools)
* You need _USB Debugging_ & _Unknown Sources_ turned on.

`adb install RealCommodore64_1.1.apk`


### Features

* Point and index-click to grab disks, insert disks into drive & press certain buttons on the keyboard
* Press back to switch viewpoint
* Turn a disk 180 degrees before inserting into the drive to access the B side
* Press F1 to boot disk in drive (top right button on keyboard)
* Press the power button on the monitor to reset
* Connect a real keyboard to type real text, or a gamepad to play games

### UPDATED INSTRUCTIONS:
### REQUIREMENTS:
Gamepad is REQUIRED. Keyboard is NOT required if games don’t require typing and are compatible with fastload, otherwise it IS required. The “physical” VR keyboard only has a few working keys, like SPACE, RETURN, etc., they glow when you point to them. Otherwise you will need a Bluetooth keyboard.
### INSTALL YOUR OWN GAMES:
There is a bat file that you can use to automatically name and load the ROM files correctly using your PC, and should be included in the ZIP file you got this APK in and also located in the assets folder of the apk.
You can manually load your own C64 games and apps in d64 format by placing them in the data folder of this app at “/sdcard/Android/data/com.C64VR.OPENPC/files/”
If copying the ROM files to the device yourself, remember that they require specific naming, and ARE case sensitive. Disk 1 side A would be named "1A.d64", Disk 1 side B would be "1B.d64", all the way to Disk 5.  You can also install a d64 ROM in the empty disk slot by naming it 00.d64, but it only loads when you first start up the app, once you load a disk in the drive, you cannot access the empty slot again until you restart this app. There are 5 disks, the first character of the filename corresponds to the disk number (1-5), the second character corresponds to the side of the floppy disk, A or B (i.e. 1A.d64, 1B.d64, 2A.d64, etc.). 
### LOADING DISKS:
Point and click on the disk to grab it, then point and click on the drive to load it.  This will load side A, simply flip it over and load it upside down for side B. Just click on the drive to remove the disk (although it will still appear loaded until you put in another one).
### RUNNING GAMES:
FASTLOAD is preloaded via the RETRO REPLAY freezer ROM (rr.bin). In order to load a game in the drive, click on F1 then on RETURN.  Some games need fastload DISABLED in order to load, in which case hit the RESET button (power button on the monitor) then select F3 (normal restart), then you will need to use a Bluetooth keyboard to manually type: [LOAD”*”,8,1] and then press RETURN. C64 key mappings are DIFFERENT than a normal keyboard! The character @ is ” and the character ] is * With Retro Replay you can format floppies to use as save disks: hit the POWER button on the monitor then F5 for UTILITIES.
Change Joystick Port:
To switch joystick ports click on the [INST DEL] button (located above the RESTORE button). The emulator starts on joystick port 2.
### ONSCREEN VICE KEYBOARD:
Click on the [RESTORE] button to bring up the VICE onscreen keyboard, however it is mostly useless for typing -most of the mappings are off. In order to click any buttons on the virtual keyboard you have to toggle on/off the onscreen mouse by hitting the BACK button on your controller, (or SELECT on the gamepad). It starts *far* OFFSCREEN past the lower RIGHT-HAND corner.  You have to use the DPAD on the gamepad to move the mouse.  Once you enabled it you have to move the mouse diagonally into the upper left direction of the screen until it becomes visible.  This is sometimes hit or miss, but is almost never needed unless you want to change system settings in the GUI (onscreen keyboard –> GUI). If you click on GUI, you MUST use the mouse to click on RESUME/RESTART/QUIT to get back (you can use D81 files, named as .d64, if you switch the drive type to 1581, but it defaults back to 1542 upon restarting). 

### Download here:
https://github.com/petermg/machineroom/releases

![Screenshot](https://github.com/petermg/machineroom/blob/master/screen03.jpg?raw=true "MODDED RELEASE-May 2020")
![Screenshot](https://github.com/petermg/machineroom/blob/master/screen04.jpg?raw=true "MODDED RELEASE-May 2020")
![Screenshot](/screenshot.jpg?raw=true "ORIGINAL RELEASE-August 2018")


