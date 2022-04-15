# Mac OS Configuration Compendium

Just a place to keep useful config files and tips for setting up Mac OS.

## Karabiner

A complete PC Style Karabiner-Elements config file, optimized for external keyboards, can be found [here](.config/karabiner/karabiner.json).

Remember to turn on Karabiner-Elements for all devices, give `Input Monitoring` permissions to `karabiner_observer` and `karabiner_grabber`.

**NOTE: It's ideal to temporarily disable Karabiner while using the embedded Terminal within VS Code.**

## Keyboard Shortcuts

### Move caret between words with Ctrl+Left/Right

Under `System Preferences > Keyboard > Shortcuts`, make sure to disable Mission Control's `Move left a space` and  `Move right a space` shortcuts if you want to be able to use Ctrl+Left and Ctrl+Right to navigate between words.

In **iTerm2**, make sure to switch `Preferences > Profiles > Keys > Key Mappings` to `Natural Text Editing`.

### Move window between screens with Cmd+Shift+Left/Right

Under `System Preferences > Keyboard > Shortcuts > App Shortcuts` add mappings like `Move to ASUS VG249` and  `Move to VW246` and bind them to Cmd+Shift+Left/Right. 

**Make sure the name of the displays matches the one that is detected by the system.**