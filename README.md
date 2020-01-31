# living-goods-KE-Linux-Ubuntu-Script
Living Goods App installation Script for Linux(Ubuntu), Also the LG Training App &amp; Go Launcher

Rename apps as follows;

Living Gooods Live App --------->lg_v3.apk\
Living Gooods Training App ----->training_lg.apk\
Go Launcher -------------------->go_launcher.apk\

as shown below

![alt text](https://github.com/tonnykirwa/living-goods-KE-Linux-Ubuntu-Script/blob/master/folder.png "Folder containing apps")\

lg_script.sh should be in the same folder as the apps above. While inside the said folder, open the terminal type the following;

```./lg_script.sh```
or
```sudo sh lg_script.sh```

# How to install ADB & Fastboot on Ubuntu
ADB or Android Debug Bridge, is a command line utility that let’s us control an android device from the computer itself. It’s part of Google Android SDK & can be used to run shell commands or to copy the files to & from the device & also to install or remove the applications from device.

Fastboot is basically a diagnostics mode that is used to modify the Android file system from computer when the android device is in bootloader mode. It’s an alternative to recovery mode & is normally used to perform updates or to perform installations.

Installation
To install both the ADB & Fastboot, execute the following command from the terminal

# sudo apt-get install android-tools-adb android-tools-fastboot

Once the installation has been finished you can check the ADB version by running the following command,

adb version


