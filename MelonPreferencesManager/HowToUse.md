## How to use

* Put the DLLs in your `Mods` folder.
* Start the game and press `F5` to open the Menu.
* You can change the keybinding under the `MelonPreferencesManager` category in the Menu, or by editing the file `UserData\MelonPreferences.cfg`.

[![](img/preview.png)](https://raw.githubusercontent.com/sinai-dev/MelonPreferencesManager/master/img/preview.png)

## Common issues and solutions

Although this tool should work out of the box for most Unity games, in some cases you may need to tweak the settings for it to work properly.

To adjust the settings, open the config file: `UserData\MelonPreferences.cfg`

Try adjusting the following settings and see if it fixes your issues:
* `Startup_Delay_Time` - increase to 5-10 seconds (or more as needed), can fix issues with the UI being destroyed or corrupted during startup.
* `Disable_EventSystem_Override` - if input is not working properly, try setting this to `true`.

If these fixes do not work, please create an issue in this repo and I'll do my best to look into it.