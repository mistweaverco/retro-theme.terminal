# retro-theme.terminal

A simple, yet beautiful kitty terminal theme.

```sh
git clone git@github.com:mistweaverco/retro-theme.terminal.git /tmp/retro-theme.terminal
mkdir -p $HOME/.config/kitty/themes/retro-theme
cp -pr /tmp/retro-theme.terminal/.config/kitty/* $HOME/.config/kitty/themes/retro-theme
```

Add this to your kitty config:

```
background_image $HOME/.config/kitty/themes/retro-theme/wallpaper-retro-4k.jpg
background_image_layout cscaled
background_tint 0.95

include themes/retro-theme/retro-theme.kitty.conf
```
