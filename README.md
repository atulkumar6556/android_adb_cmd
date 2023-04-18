# android_adb_cmd
android adb shell commands


## INSTALL APP AS SYSTEM APP-


        adb start-server
        
------------------------------------------------------------ 
        
        adb remount
------------------------------------------------------------ 
        adb push yourapk.apk /system/priv-app/yourapk.apk
------------------------------------------------------------ 
        
        adb shell chmod 644 /system/priv-app/yourapk.apk
------------------------------------------------------------ 
        
        adb reboot
        
