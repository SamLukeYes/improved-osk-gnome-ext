# improved-osk-gnome-ext

Makes Gnome's onscreen keyboard more useable.

Changes in this fork:
- Removed preferences because it doesn't work in GNOME 40
    - *Pull requests are welcomed to bring it back*
- Tweaks on default settings

## Installation

This extension is available as [gnome-shell-extension-improvedosk-git](https://aur.archlinux.org/packages/gnome-shell-extension-improvedosk-git/) on AUR

## FAQ

### Some symbols are missing...
The keyboard uses unicode characters, try installing ttf-symbola from AUR

### Do i need to enable the OSK in Gnome accessibility settings?
By default the keyboard will popup on touch input events. Enabling the keyboard in the accessibility settings just allows the OSK to popup on non touch input.

### Where to edit the settings without extension preferences?
Open `dconf-editor` and go to `/org/gnome/shell/extensions/improvedosk/`