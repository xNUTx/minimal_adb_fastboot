Quick ADB / Fastboot installer for OS X and Linux (minimal_adb_fastboot)
====================

Last updated: 14.03.2015 | adb version: 1.0.32
------------------------
Installs the adb and fastboot binaries for OS X and Linux.

Do the following steps:
- Download the zip
- unzip it
- Start the shell script with ./install.sh
- Finished

Changelog:
---------------
- 1.0	| 15.11.2014 Initial release
- 1.1	| 16.11.2014 Script can now be called from everywhere
- 1.1.1	| 23.11.2014 Name change due to name confict with other adb installer.
- 1.2	| 10.03.2015 Updated adb and fastboot binaries to platform-tools v22, adjusted script because binaries change without version number incremention.
- 1.2.1 | 13.03.2015 Improved version check by adding a hash-check to compare installed and delivered bin. 
- **2.0.0 | 14.03.2015 Added Linux support!** (experimental, feedback very welcome!)

Support Thread:
----------------
Official support thread on xda: http://forum.xda-developers.com/android/general/adb-fastboot-binaries-os-x-inclusive-t2941205
Please open an issue if you experience any problems and feel free to fork and improve this script, I would be happy if you made a push request with your improvements!

Installer Package (legacy):
------------------
**PLEASE NOTE:** The package caused more problems than it did solve, and I think everybody 
who uses adb / fastboot can install the binaries with my script. 
*The installer package WILL NOT be supported anymore, please use the script!*


I also made an installer package (mpkg), which simply moves the binary files into /usr/bin/.
This Package is not signed, which means you have to start it by right-clicking on the mpkg file and select "Open...".

You can find the newest version (Quick Installer Package 1.0, adb version 1.0.32) here:
Download: https://github.com/simmac/minimal_adb_fastboot/releases/download/1.1.1/Quick_ADB-Fastboot_Installer.mpkg
