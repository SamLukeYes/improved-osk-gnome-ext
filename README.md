# improved-osk-gnome-ext

Makes Gnome's onscreen keyboard more useable.

Changes in this fork:
- ~~Removed preferences because it doesn't work in GNOME 40~~ Fixed! (thanks [@nick-shmyrev](https://github.com/nick-shmyrev))
- Tweaks on default settings

## Installation

This extension is available as [gnome-shell-extension-improvedosk-git](https://aur.archlinux.org/packages/gnome-shell-extension-improvedosk-git/) on AUR. Only this installation method is supported at this moment. Maybe I'll test and figure out a more convenient way to install this extension later.

## FAQ

### Some symbols are missing...
The keyboard uses unicode characters, try installing `ttf-symbola` from AUR.

### Do i need to enable the OSK in Gnome accessibility settings?
By default the keyboard will popup on touch input events when physical mouse isn't available. Enabling the keyboard in the accessibility settings just allows the OSK to popup on non touch input and/or when physical mouse is available.
