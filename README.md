# AvironRower
The github repo for all things related to hacking Aviron rowing machines

## Information

Most rowing machines pruduced by Aviron Active feature an android tablet runing their App which interfaces with the machine and tracks your statistics. Most run either android 7 or 10. 

Aviron secures the multimedia features such as Netfix or Paramount+ beind their membership which offers other things such as workout videos. In reality, the only thing preventing users from accessing Netflix etc. is their app interface. There have been multiple ways to get around the Aviron app through the settings app etc, but most have been patched.

## Files

The Files for the patched apks are above (Not yet avalible).

The APK files for the Aviron app are avalible at https://apk-prod.update.rowaviron.com with an archive above. Theoretically theese could be used to patch the apk or reinstall it on a regular android system.

The OTA (over the air) firmware files are avalible at https://os-prod.update.rowaviron.com with an archive above. Theoretically theese could be used to install a custom recovery and OS on the board.

## Board

The tablet runs on a Rockchip 3399 (RK3399), which seems to be common for embedded systems like this.

The FCC report, which includes photos of the board, is avalible at https://fcc.report/FCC-ID/2ASJ3-ATS1 with an archive above. **Note that the USB-A port and Micro SD slot are not present on production models.**

The board features a micro-usb port which can be used via ADB (see below). This port cannot be accessed without opening up the tablet.

## ADB

to be completed