Introduction
------------
Appirater is an android library based off the original Appirater By Arash Payan [Appirater iPhone] [appirater]. The goal is to 
create a cleanly designed App Rating prompt that you can drop into any android app that will help remind your users to 
review your app on the android Market.

![screenshot](https://raw.github.com/sbstrm/appirater-android/development/screenshot.png)

Like it's iPhone counterpart the code is released under the MIT/X11, so feel free to modify and share your changes with 
the world.

Getting Started (Eclipse)
-------------------------
1. Include the AppiraterAndroid library in your project.  Under your projects preferences -> Library section just click add and select the appirater-android library. 
2. Copy the /res/values/appirater-settings.xml from the AppiraterAndroid library in to your projects /res/values/ folder and adjust the settings to your preference.
3. Add Appirater.appLaunched(this); to the onCreate method in your main Activity.

Getting Started (Maven)
-----------------------
1. Install the library to you local repository using `mvn clean install`
2. Add the library as a dependency to your app:

	```
	<dependency>
	    <groupId>com.sbstrm</groupId>
	    <artifactId>appirater</artifactId>
	    <type>apklib</type>
	    <version>1.0</version>
	</dependency>
	```

3. Copy the /res/values/appirater-settings.xml from the AppiraterAndroid library in to your projects /res/values/ folder and adjust the settings to your preference.
4. Add Appirater.appLaunched(this); to the onCreate method in your main Activity.



Upgrading to 1.1+
----------------
Users upgrading to 1.1+, please remove your old /res/values/settings.xml file from your application and add follow step 2 under "Getting Started" above.

License
-------
Copyright 2011-2013 [sbstrm] [sbstrm].
This library is distributed under the terms of the MIT/X11.

While not required, I greatly encourage and appreciate any improvements that you make
to this library be contributed back for the benefit of all who use Appirater.

Credits
-------
Orginal iPhone Appirater and translations By [Arash Payan] [arash]

Gradient button style by [Folkert Jongbloed] [folkert]

Also, thanks to [Chris Hager] [chrishager] who created AppRater for android

[appirater]: https://github.com/arashpayan/appirater/
[sbstrm]: http://sbstrm.co.jp
[arash]: http://arashpayan.com/
[folkert]: http://www.dibbus.com/2011/02/gradient-buttons-for-android/
[chrishager]: https://github.com/metachris/android-apprater
