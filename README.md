# Tacky
_Tacky for Civilization 6 (Windows)_

 By Dean Carrano (dcarrano@gmail.com, https://github.com/dcarrano)
 
 "Underline" function by "wolf_II" from AutoHotkey Forums: https://www.autohotkey.com/boards/viewtopic.php?p=166660#p166660

Welcome to Tacky! This program is designed to make it easier for Windows users to name your tacks in _Sid Meier's Civilization 6_.

TL; DR: While _Civilization 6_ is running, press CTRL-SHIFT-T to bring up a menu to select tack names.

<h1>What Tacky Does</h1>

Before using Tacky to name a tack, make sure you've done the following in _Civilization 6_:
1. Go to the tack menu, select "Add Tack", and choose the location
1. In the resulting "Edit Map Tack" menu, select the icon you want for the tack
1. In the "Edit Map Tack" menu, place the cursor in the textbox as if you're about to type

Once Tacky runs, in order to make a selection, you can either:

* Click on the picture that represents the improvement or district;
* Click on the name of the improvement or district; or
* Use the appropriate shortcut key. To perform the shortcut, hold down ALT and press the underlined letter in the name of the improvement or district in the Tacky menu. For example, the shortcut for a farm is ALT-F. The shortcut for fishing boats is ALT-B. 
  * Some improvements/districts don't have shortcut keys assigned, but the great majority do.

You can use CTRL-TAB to switch between the "Improvements" and "Districts" menus (or, of course, simply click the appropriate tab).

Selecting a district type will send to _Civilization 6_ the name of the district (perhaps abbreviated), followed by a space, a dash, and another space. For example, if you choose an entertainment complex, the program will send the string "EntCom - ". You can then fill in the name of the associated city before entering.

If an improvement is selected and that improvement has no options, then its name will be sent and immediately entered. For instance, if you select "Lumber Mill", that is simply entered, since lumber mills have no additional options.

If an improvement is selected and that improvement contains further options, a submenu with the appropriate options will appear. Again, you can click the image, click the name, or press the shortcut key to select the option. Once you do so, a string containing both the improvement and the option will be sent and immediately entered. e.g., if you select "Camp" and then "Deer", the string "Camp - Deer" will be sent and entered.

<h1>Running Tacky</h1>

Tacky expects all files to be in the same directory. So, the easiest thing to do is simply unzip **tacky.zip** into a directory, and run it from that directory. If you insist on changing that, you can alter the "SetWorkingDir" variable at the beginning of the script.

Tacky was written with [AutoHotkey](https://www.autohotkey.com). As such, it requires Windows.

If you already have AutoHotkey installed, you can run **tacky.ahk** as a script. Alternatively, you can run the **tacky.exe** program, which doesn't require AutoHotKey.

IMPORTANT: Note that, because Tacky will re-route key combinations that you might otherwise use, **its menu will not appear unless _Civilization 6_ is already running**.

If you run the AutoHotkey version, press CTRL-SHIFT-T in order to activate the Tacky menu. 

If you run the executable while _Civilization 6_ is already running, the Tacky menu will appear as soon as you run the .exe. Otherwise, you can also press CTRL-SHIFT-T to activate it. 

But again, in either case, note that if _Civilization 6_ isn't running, Tacky will not function! The menu will not appear unless _Civilization 6_ is running!

<h1>Troubleshooting</h1>

Again, make sure that all files are in the same directory (unless you've edited the file to change this). If you're using the AutoHotkey version, make sure that your AutoHotkey is at least version 1.1.33.09, and that it's the Unicode version.

And again, before making your final selection in Tacky, make sure that you've called up the "Edit Map Tack" menu in _Civilization 6_ and have the cursor active in the textbox, as if you're about to type.

If you want to run the AutoHotkey version and have trouble with AutoHotkey itself, I can't help you with that. Possible solutions are:

* Make sure that your AutoHotkey executable (most likely found at _C:\Program Files\Autohotkey\Autohotkey.exe_) is set to run as administrator.
* Try to unzip to a drive other than C:, or somewhere else that is less likely to have restrictive Windows rules.
* Turn off User Account Control. 
