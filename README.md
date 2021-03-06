# AIVehicleExtension for Farming Simulator 2017

## Testing
**It would be greate if everybody would retest the issues she/he created and close issues that are resolved. Thanks!**

## Status
Minimum patch level is Farming Simulator 2017 patch 1.3.1, but patch 1.4 is supported as well. I only test it with patch 1.4.4.
The core path finding engine ("AutoSteeringEngine") is working now and most turn maneuvers seem to work quite well. 
I moved many settings into a new settings GUI. 

#### New User Interface
The idea behind the new user interface is to move as many settings as possible into new settings dialog. This dialog uses standard elements. Only those options needed for visualization or intermediate action are still available in the head up display (HUD).

#### New Input Binding
I changed the input binding. Main reason is that keys 5 and 6 are used for the radio. This is the new setting:
- H: Start or stop the hired worker
- Left shift + H: Open the new settings dialog
- Left control + H: Open the head up display
- Left alt. + H: Enable or disable automatic steering
- Left alt. + V: Raise or lower all tools
- Left alt. + 6: Swap side

## Motivation
I do not like maps with rectangular fields. But driving a combine harvester plus the tractor with trailer is a bit tedious in SP mode. 

## Description
The Mod is installed easily in the mod folder. 
It is automatically added in all AIVehicles. 
Thus the combine threshes automatically in circles around the field.

## How to
The AutoCombine Hud is opened with the key 5. The helper starts normally using the H key.
Warning: You must turn on the alternative helper only in Hud. 
The button is in the 2nd Row far left. Is there a quadrilateral, then only the normal helper is on.

## Developer version
Please be aware you're using a developer version, which may and will contain errors, bugs, mistakes and unfinished code. 

You have been warned.

If you're still ok with this, please remember to post possible issues that you find in the developer version. 
That's the only way we can find sources of error and fix them. 
Be as specific as possible:

* tell us the version number
* only use the vehicles necessary, not 10 other ones at a time
* which vehicles are involved, what is the intended action?
* Post! The! Log! to [Gist](https://gist.github.com/) or [PasteBin](http://pastebin.com/)

## Credits
* Stefan Biedenstein
