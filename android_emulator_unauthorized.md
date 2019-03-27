##Restart Server

In such a case, you can do all of the following in order to be assured that your emulator starts working again :
1. Go to cmd and type “adb kill-server”
2. Go to task manager and find “adb” in processes. If you find one,right click on it and click on end process tree.
3. In eclipse, go to Window>Android Virtual Device Manager, click on the AVD you want to launch, click on start and uncheck “Launch From Snapshot” and then click on launch.
That’s it! It will take a while and it should resolve your problem.

##Wipe Date

1. Simply “Wipe data” to fix this issue. 
2. If it doesn’t work, go to emulated device and enable developer options > enable usb debugging


##Android adb unauthorized
1. Delete .android/adbkey|adbkey.pub or just move the two file out .android folder；
2. Delete all avds in AVD Manager and then re-create；


