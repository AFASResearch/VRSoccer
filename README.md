# AFAS Virtual Reality foosball

![AFAS VRSoccer](https://github.com/AFASResearch/VRSoccer/blob/master/vrsoccer.png)

Play VR foosball with Google cardboard! A sample VR project to get started with cardboards & VR. 

* Use the hole in the cardboard to control the game with your finger. 
* You can even play foosball against others on this original AFAS foosball table.
* Double tap spawns another ball.
* Look at the rod to control the rod in the game.

This is intended as a sample project, it is not ready for any production usage :)
We have many TODO's left, which might be implemented someday, or not.
You are welcome to fork and built your own version. Send us pull requests!

Currently Android is working. The APK can be downloaded here:  [VRSOCCER-armv7-es2](Build/Android_ETC2/VRSOCCER-armv7-es2.apk).
The iOS version is currently not working, but you can send an email to d.verweij@afas.nl to get updates as we are awaiting a bug fix in the engine.

You would have assumed that we enabled HTML5, but we didn't. Maybe in the future :)

# Instructions for development

* Install Unreal Engine 4.13. The easiest way is through the [Epic Games software](http://www.epicgames.com).
* Also make sure that you have the [Android SDK](http://docs.unrealengine.com/latest/INT/Platforms/Android/GettingStarted/1/index.html).
* Clone this repository.
* Open the project (VRSOCCER.uproject) in the Unreal Editor.

# Known TODO's

* Control the game with a wii controller or with air gestures (requires camera in cardbox to work).
* Network play.