Compiled firmware with correct RGB settings and 2 extra buttons added to OLED screen layout.

Instructions:

To get into bootselect mode easily start by booting into web configurator.
This can be done by holding START while plugging in the USB into PC.
Enter the webconfigurator at http://192.168.7.1/
Select REBOOT in the top left corner and choose BOOTSELECT.
In your windows explorer a new disk drive LABELED RPI-RP2 will be available.
Drag and drop the flash_nuke file into the drive. (the flash_nuke will act as hard reset settings).
The controller will reboot itself and the RPI-RP2 disk drive will be available again.
Drag and drop the newest UF2 firmware file into the drive.
After this the controller will automatically reboot with new firmware.


I know 0.7.6 added major feature (XBOX Passthrough) but it had a big bug causing DPAD + SOCD sliders to not function on the Open_CoreK1 so I skipped this firmware.

This has been fixed as of recent so I updated the firmware to 0.7.7 RC1


As of right now version is based on GP2040-CE 0.7.7 RC1

I will try to keep it updated with major firmware releases which add major bugfixes/features/improvements.

Dont expect me to update small releases/non big feature updates.
If it ain't broke dont fix it.

Heres my repository to see changes made to GP2040-CE firmware: https://github.com/dangk1/GP2040-CE
