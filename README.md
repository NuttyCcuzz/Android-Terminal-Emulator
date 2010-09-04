#Android Terminal Emulator

Android Terminal Emulator is a terminal emulator for communicating with the built-in Android shell. Emulates a reasonably large subset of Digital Equipment Corporation VT-100 terminal codes, so that programs like "vi", "Emacs" and "NetHack" will display properly.

This code is based on the "Term" application which is included in the Android source code release. It's provided as a separate project for the convenience of developers who do not want to deal with installing and building the whole Android source tree.

Although this program does not include a built-in ssh client, it can be used with command-line-based ssh tools such as dropbear.

Got questions? Please check out the [FAQ](http://github.com/jackpal/Android-Terminal-Emulator/wiki/Frequently-Asked-Questions) before emailing or adding an issue. Thanks!

##Recent updates:

1.0.15:

Fix Swype IME backspace key.

1.0.14:

Fixed crash that sometimes occurred when rotating portrait to landscape.

1.0.13:

You can now use the volume-up or volume-down key as the control key. This is especially useful on phones that lack any other hard keys, such as the Samsung Galaxy S. Thanks to Todd Musall for writing and contributing this feature!

1.0.12:

By popular demand, implement a work around for determining the visible portion of the terminal screen when the soft keyboard is visible. Should work for portrait and landscape, and with or without status bar. Whew!

1.0.11:

reset everyone's status bar to 'on'. If they want the status bar off, they have to set the preference again. I did this because the soft keyboard works better if the status bar is on. People who upgraded to 1.0.9 had the status bar automatically turned off, which broke their soft keyboard. Now it should work again. (Software development is hard!)

1.0.10:

default the status bar to "on", because turning the status bar off causes the app to become a "full screen" app, and the IME system doesn't resize the view for full screen apps.

1.0.9:

show/hide status bar preference.
toggle soft keyboard menu item.

1.0.8:

longpress to copy/paste.

1.0.5:

Add Internet and SD Card permissions to allow apps run from the emulator to access
the Internet and write to the SD card.
