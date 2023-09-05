# Hyprdotfiles
Collection of dot files for my Hyprland setup, full setup including a customised top and bottom waybar, 
wlogout with suspend & hibernate, wofi, an swww script to change wallpaper every 5 minutes, 
auto locking and screen power off and more. 

Everything is themed to look as coherent as possible.

## Install
Drop everything into ~/.config and reboot.

## Prerequisites
### Required
hyprland, swww, mako, terminator, swaylock, swayidle, wlogout, wofi, cliphist, slurp, swappy,
wl-paste, polkit-gnome-authentication-agent.
### Fonts
liberation-mono, nerd-font-symbol.
### Optional
easy-effects, blueman-applet, nm-applet, btop, rog-control-center (because I have an Asus laptop)

## Important
Since I have an Asus laptop I have added some specific software and binds to suit this weird POS.

The profile module for waybay requires asusctl to find and change power profiles, 
rog-control-center runs on launch and I have added some funky media key binds to make OSD work
for brightnessctl. While these things won't hurt a non asus device they also won't work either,
if you clone this repo and don't have an ASUS ROG or TUF machine then expect to have to make changes.
