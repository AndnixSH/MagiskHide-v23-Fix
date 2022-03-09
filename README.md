# MagiskHide v23 fix

![](https://i.imgur.com/gaALGAW.png)

I was very confused why MagiskHide was crashing/not launching on both phone and emulator, the icon would get a little bit bigger, highlighted (like the screenshot above), darkened out, greyed out whatever.... Reinstalling Magisk entirely or creating new emulator instance did not help. I used HTTP Tooklit to log the network traffics and I just discovered it was literally downloading 24.1 stub APK instead 23.0. Now I know wrong version of stub APK will lead to crash. Since Magisk allows you to change channel, I have hosted magisk v23 files on my server and it has fixed MagiskHide

How to fix?

The fix is very easy

First, open Setting in the Magisk app. Change Update Channel to Custom Channel. Click on Custom Channel and add this url

`https://repo.andnixsh.com/magisk-v23/stable.json`

![](https://i.imgur.com/iRk3QED.png)

![](https://i.imgur.com/eYqNjJd.png)

Click OK

Uninstall broken Magisk hide app and try to hide the Magisk App again via the Magisk settings. The app should be able to hide now

Here is the proof. The app is called Settings

![](https://i.imgur.com/FhzzuIv.png)

**I know there is a better module for Magisk 24 and above. Magisk v23 can still be used for emulators running 7.1 and devices that CANNOT use Magisk v24 and above**

I have provided Magisk v23 files so you can understand how Update channel works. You can host them on your server as well