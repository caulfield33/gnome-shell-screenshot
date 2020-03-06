![Screenshot](https://raw.githubusercontent.com/OttoAllmendinger/gnome-shell-screenshot/master/data/screenshot.png)

Shortcut to create screenshots that can be opened, copied to clipboard or saved
to disk.

This extension is based on
[gnome-shell-imgur](https://github.com/OttoAllmendinger/gnome-shell-imgur/).

## Installation

### Via extensions.gnome.org

The latest reviewed version can be found at
[GNOME Shell Extensions](https://extensions.gnome.org/extension/1112/screenshot-tool/)

### Via github.com

The latest development version can be installed manually with these commands:

```sh
git clone https://github.com/OttoAllmendinger/gnome-shell-screenshot.git
cd gnome-shell-screenshot
make install
```

Then go to https://extensions.gnome.org/local/ to turn on the extension or use
gnome-tweak-tool.

## Known Issues

### Clipboard stops working in Gnome 3.20

On Gnome 3.20, the clipboard stops working after the lock screen appears.

See https://github.com/OttoAllmendinger/gnome-shell-screenshot/issues/4

As a workaround, restart the shell: `Ctrl-F2` `r` `Enter`. The clipboard
should work again afterwards.

### To Text
Before use 'To Text' button you need to install `Pillow`, `pytesseract` and `cv2`
User this command to install all required packeges `pip3 install pytesseract Pillow opencv-python`

## Contributors

* https://github.com/RaphaelRochet, https://github.com/peetcamron -- French translation
* https://github.com/gsantner -- German translation
* https://github.com/pkomur, https://github.com/orschiro, https://github.com/MartinPL -- Polish translation
* https://github.com/amivaleo, https://github.com/Fastbyte01 -- Italian translation
* https://github.com/ge0rgecz -- Czech translation
* https://github.com/dirosis -- Greek translation
* https://github.com/AlexGluck, https://github.com/alex-volga -- Russian translation
* https://github.com/trinaldi -- Portuguese (Brazil) translation
* https://github.com/alex-volga -- Ukranian translation
* https://github.com/iamhefang -- Simplified Chinese translation
* https://github.com/Mavrikant -- Turkish translation
* https://github.com/Burday -- Bulgarian translation

Also see contributors for
[gnome-shell-imgur](https://github.com/OttoAllmendinger/gnome-shell-imgur/).

## Tip Address

Bitcoin tip address 1Nh2msr4uwSxTz4Na6DUBj4cEtP5VrjPAg

