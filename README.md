Android TV Plugin for Cordova
==============================

Cordova plugin to add tags to the AndroidManifest.xml that'll let your Cordova app run on Google TV, Android TV and OUYA.

That's all it does (I just needed something to streamline this process for me).

This does not add the Leanback banner, you'll sadly have to do that yourself (for now).

If you want to interact with the controls on an Android TV or Google TV device just set events on the arrow keys like you would with a desktop web app.

For gamepad support on anything below Android 5.0, turn to this plugin: https://github.com/judax/cordova-plugin-gamepad

**Note:** For Ouya and Android TV the plugin was specifically set to be list your app as a game, if you want it to show up on an Ouya and Android TV as an app you'll have to replace the part in my plugin.xml file that says "tv.ouya.intent.category.GAME" with "tv.ouya.intent.category.APP" and the part that says 'android:isGame="true"' to false.

To-do
-------
* Set Android TV leanback banner from Cordova manifest.
* Set "isGame" from Cordova manifest.
* Set "uses gamepad" from Cordova manifest.
* Set app requirements from Cordova manifest (might make this into a separate plugin).

Install
-------

`cordova plugin add https://github.com/hughisaacs2/Cordova-Android-TV-Plugin.git`

Source
-------------
https://github.com/hughisaacs2/Cordova-Android-TV-Plugin

License
-------

This has been released under MIT license; see LICENSE for details.
