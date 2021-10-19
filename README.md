Updated September 29,2021

# WickedOS
A android based operating system for Raspberry pi 4.

WickedOS is built on konstakangs lineage 17.1

WickedOS has everything you need to load your games and play. WickedOS will also be released on arcade punks loaded .  

## First Boot Setup 

1.You need a keyboard and mouse plugged in.

2.Press and hold F5 press reboot the recovery .

3.After reboot click "Install"

4.Find /sdcard/Tools/TWRP/resizePI4.zip 

5.This is resizing your the image to your SD card size . 

6.Swipe to install wait then reboot to system , 

## F.A.Q 

## What can this play?

Retroarch is the main emu used. So most normal retroarch cores .

N64, psp, dreamcast, and nds use standalone emulators/apps.  

N64 performance is very smooth . Most games function better than retropie. This is due to emus used that were designed for android low end phones 

Psp, dremcast and NDS performance is about the same as retropie . 

Sega Saturn performance is still quite slow and not worth the time really. Same currently with gamecube and wii.

This may change will update if it does .

## How do I add games ? 

## Large games or packs follow these instructions 

    1.Plug in keyboard press and hold f5. 
    
    2.Press reboot then recovery. 
    
    3.Plug your hardrive into a USB port. USB must fat32.
    
    4.Click mount the select USB.
    
    5.Go back to main menu.
    
    6.To go Advanced then file manager then find USB. 
    
    7.Find and enter folder you wish to copy and click select folder then copy.
    
    8.Select copy location.
    
    9. Click confirm . Repeat per game folder .
 
## Small games follow these instructions 

    1.Plug in USB drive.
    
    2.Plug in a mouse.
    
    3.Click and drag from top of screen twice. 
    
    4.Click settings icon .
    
    5.Click apps then all apps.
    
    6.Find files.  
    
    7.Find usb then your game and copy to desired location .
    
    note this will fail with larger files. 
    
## Hows this different from Konstakangs build ?

WickedOS has everything installed for ya. Retroarch, other emus, a retro frontend etc. Some of these apps are special versions or modified . 

In the future we will be attempting to  complying android ourselves. This if successful will be the biggest difference.  

## How to add android games ? 

From dig frontend open "Aurora Store". It is a normal app store and will install apps for you. 

## Where/When?

Shipped to Devil with best wifi to upload to Arcade Punks today .

## How to add Google Play store ? 

Download open_gapps-arm-10.0-pico-xxxxxxxx.zip and save it to your device’s internal storage or use an external USB driveBoot to TWRP recovery.

Install open_gapps-arm-10.0-pico-xxxxxxxx.zip from your selected storage

Wipe -> Factory reset!

Boot out of recovery.

See Konstakangs site for more about play store .

## Notes and comments 

Please see Konstakangs Website for more FAQ.

Tested many times so far so good . 

If you have problems please report to "Retro Devils Support" Facebook group. Konstakangs build is super solid, if thiers a issue its more than likely something we did .

This is open source project . Feel free to use and modify .

Other android build exist.

You can easily do this yourself to a extent. We built custom themes, used different apks etc. 




## Sources/Props/Credits

Konstakang. The reason this is possible. 

Website:  https://konstakang.com/devices/rpi4/LineageOS17.1/

Credits from Konstakangs site 

Peter Yoon and everyone who has contributed to android-rpibrobwind for bluetooth fixes

Roman Stratiienko and GloDroid project for graphics fixes

Eric Anholt for V3D graphics driver

Maxime Ripard for Pi 4 KMS driver

Google for Android Things platform

Android-x86 project

LineageOS team & everyone who has contributed to LineageOS 17.1
