BroadcomCM kernel auto-maker menu.
==================================

This script should be in android/kernel/samsung/bcm21553-common/BCMKAMM

Quick Summary:
--------------
 * This script is used to build a kernel for all the BroadcomCM devices using a common source. Due to all the devices have a common source and different modules, this script will identify each of the device you select and build a working zImage for each. This menu will also include an option to pack the ramdisk automaticly before zImage is done.
 * Our kernel are included on GPL License, so this Menu will be also open sourced and everyone can contribute to help us.

Quick Setup:
--------------
 * This script should be with *kernel* and *ramdisk* folder. 
 * Inside *kernel* folder you should have *common* and *modules_device* folders.
 * Inside *ramdisk* folder the Ramdisk files.
 * Open *menu* file and follow instructions.

TO-DO List:
-----------
 * Be able to start the script.
 * Be able to select your defconfig on the Menu.
 * Automaticly make a 'make clean' to ensure a good zImage will be build.
 * Create an option to go through menuconfig and save your changes.
 * Be able to rename modules_device to modules and make sure build of zImage does not fail.
 * When zImage is done, be able to copy into the ramdisk section.
 * Start the script were ramdisk will be packed or not.
 * Ensure everything is working.

Credits (alfabetical):
----------------------
 * Bieltv.3.
 * Lopicl.00.
 * Spacecaker.
