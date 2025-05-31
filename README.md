# Default godot project settings

The settings I want changed for every project.

## How apply settings

1. Copy the settings from the **settings** file and paste into **project.godot** file in root of your godot project.
2. Restart Godot

## How to update default settings file

1.  In Godot, go to Project Settings
2.  Hover over any setting to see the full name path of the setting, ex. `gdscript/warnings/untyped_declaration`
3.  Set the setting to your desired value
4.  Go to **project.godot** file, which contains all settings that have changed from the editor default. Copy that setting and paste into the **settings** file in this repository, making sure to include the header like `[debug]`
5.  Commit and push the changes
