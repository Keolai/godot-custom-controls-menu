# Godot Custom Controls Menu

A basic menu to allow players to change game controls during runtime.

**Installation and Use**
<br/>
Download the files and add them into your godot project. Add your controls to the input map in your project settings with names (preferably in snake case) you want the player to see. The menu will use the input map to auto-populate the itself. Drag the `control_settings` scene into any scenes where you want to allow players to change their controls.
<br/>
<br/>
**Note**
<br/>
This asset does not have a disk saving functionality, **meaning that any changes to the input map are limited to the current instance of the game**. Disk saving functionality could be added to the `save_new_controls()` function in `scripts/settings.gd`. This asset has also only been tested with keyboard and mouse, modifications may need to be made for use with controlers. 
