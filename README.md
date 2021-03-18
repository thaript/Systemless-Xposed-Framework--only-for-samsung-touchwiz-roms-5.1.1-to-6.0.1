# Systemless Xposed Framework only for samsung touchwiz roms 5.1.1 to 6.0.1

Please install my modified [XposedInstaller(3.1.5)](https://www.mediafire.com/file/hjqcrr68a9tqvsl/XposedInstaller_3.1.5-Magisk.apk/file) to properly detect Systemless Xposed.

YOU NEED TO INSTALL SUDO HIDE FROM XPOSED INSTALLER TO PASS SAFETY NET TEST

SOMETIMES THIS SHOWS AS XPOSED INSTALLED BUT NOT ACTIVATED

DON'T WORRY YOU CAN ACTIVATE ANY XPOSED MODULE FROM  MODULE MENU 100% WORKING

IF YOU HAVE ANY BOOT LOOP ISSUES PLEASE DOWNLOAD XPOSED MODULE DISABLER FROM HERE AND FLASH THROUGH TWRP

THEN ENTER TO MAGISK REMOVE THIS MODULE AND ACTIVATE OTHER MODULES AND REBOOT

XPOSED MODULE DISABLER (https://www.mediafire.com/file/9r8gcwnfor236zk/Magisk_Modules_Disabler%2540Edzamber.zip/file)

The APK is signed by ravo89's personal key, you might need to uninstall other versions before installing it.

The binaries are identical to builds downloaded from official links of wanam (https://androidfilehost.com/?w=profile&uid=95784891001615489), with the exception that `app_process*` is patched with the following command:

`sed -i 's:/system/xposed.prop\x0:/sbin/xposed.prop\x0\x0\x0:g' app_process*`

This module most likely will never get any updates in the future, since @rovo89 seems to have stopped development. This module is here for historical reasons.
So I modified this to samsung touchwiz devices 5.1.1-6.0.1
thari.pt

FURTHER IF YOU NEED ANY MODIFICATIONS OR HELP
email
thari.pt2@gmail.com

BLOG
https://techworld9x.blogspot.com

Youtube
https://m.youtube.com/c/TechWorldthaript

FB
https://m.facebook.com/attygallep
