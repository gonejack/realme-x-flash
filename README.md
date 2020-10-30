# Realme X Flashing ROMs

Custom ROMs:
```
PixelExpirence
https://forum.xda-developers.com/realme-x/development/rom-pixel-experience-plus-edition-t4066879

RevengeOS
https://forum.xda-developers.com/realme-x/development/11-revengeos-4-0-r-realme-x-t4165129

EvolutionX
https://forum.xda-developers.com/realme-x/development/rom-t4044901

Mokee
https://download.mokeedev.com/rmx1901.html

Official
https://www.realme.com/cn/support/software-update
```

Flash Steps:
```
1. unlock
https://c.realme.com/in/post-details/1247421596461694976

2. flash TWRP recovery
 2.1 volume down + power enter fastboot mode
 2.2 fastboot flashing unlock
 2.3 fastboot flash recovery twrp-3.4.0-0-RMX1901-mauronofrio.img
 2.4 fastboot reboot recovery
 2.5 flash the OF_avb_patcher_mauronofrio.zip inside TWRP for preventing TWRP lost.

3. flash roms with TWRP
 important: click Wipe Data button to clean data, or you will boot into recovery instead of system.
```
