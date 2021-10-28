command to open link in browser
1.working
 adb shell am start -a android.intent.action.VIEW -d http://www.stackoverflow.com
2.not working
 adb shell pm grant com.android.chrome android.permission.READ_EXTERNAL_STORAGE
3.automate install app 
    https://stackoverflow.com/questions/53157208/automated-installation-of-an-apk-from-the-google-play-store

    adb shell am start -a android.intent.action.VIEW -d 'market://details?id=com.yourpackagename'

    adb shell input tap <x> <y> (Default: touchscreen)

    eg --> https://play.google.com/store/apps/details?id=com.facebook.lite


4. find x and y cordinate --> https://www.youtube.com/watch?v=PqgDvAAaTgA

5. permission 

https://www.cnblogs.com/johnnyzen/p/14676376.html