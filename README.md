# System Crafter Configurations

This repository is a collection of configurations created by the System Crafters community!  If you've got a dotfiles repo containing configurations for different applications you use, feel free to [add yourself to this page](#how-to-add-your-config) by sending a PR.

## Crafters

### David Wilson ([@daviwil](https://github.com/daviwil))

I've developed a whole system configuration based around Emacs, EXWM, and Guix which gets shared between multiple machines.  My configuration files are mostly stored in Org Mode files and exported with Org Babel.

- **Config Repo:** https://github.com/daviwil/dotfiles
- **Operating System:** GNU Guix
- **Software:** Emacs, Guix, Vimb, Polybar, Dunst, mpv, GNU Stow
- **Keyboard:** Since I'm a ThinkPad fan, I use the [ThinkPad Compact USB Keyboard](https://www.amazon.com/Lenovo-ThinkPad-Compact-Keyboard-TrackPoint/dp/B00F3U4TQS/ref=sr_1_3?crid=1P0R7L5JJA8CG&dchild=1&keywords=thinkpad+usb+keyboard&qid=1604238423&sprefix=thinkpad+usb+keyboard%2Caps%2C-1&sr=8-3)

### Jens Schneider ([@jensac](https://github.com/JensAc))

My system configuration is based on Arch Linux, i3wm and rofi. The important config files are simply stored as plain text with some comments here and there. Feel free to copy, if you find something useful. 

- **Config Repo:** https://github.com/JensAc/dotfiles
- **Operating System:** Arch Linux
- **Software:** i3wm, i3status, Rofi, Emacs, Alacritty, Fish
- **Keyboard:** [Ultimate Hacking Keyboard](https://ultimatehackingkeyboard.com/). A masterpiece of hard- and software. 

### Erik Lundstedt ([@erik.lundstedt](https://gitlab.com/Erik.Lundstedt))

I recreated window swalowing in awesomeWM for kitty and vivaldi webbrowser (wip)
awesomeWM needs you to move/symlink one of the files in awesome/settings/screens.lua* to awesome/custom/screens.lua as i use diferent settings on different devices with different screens(laptop is single screen and thinkpad has a bigger top-bar as it's a touch-screen)

- **Config Repo:** https://gitlab.com/Erik.Lundstedt/dotconfigfiles 
- **Operating System:** debian bullseye/sid
- **Software:** doom-emacs, awesomeWM, kitty, zsh with oh-my and powerline, and some others i dont use a lot
- **Keyboard:** swedish keyboard layout but I am not using the extra keys, I use alt-tab for some in-program things that might conflict when using a desktop enviroment as I bound super-tab to switch-window<<<<<<< patch-1

### Kavin ([@kavin25](https://github.com/kavin25))

My setup is a lot similar to the emacs from scratch playlist. I have added some stuff for my own comfort. It's all made in Org Mode and exported with Org Babel.

- **Config Repo:** https://github.com/kavin25/emacs_config
- **Operating System:** MacOS
- **Software:** Emacs
- **Keyboard:** Macbook Air 2017 default keyboard.

### Ethan Carter Edwards ([[@ethancedwards8](https://github.com/ethancedwards8))

I've been using Emacs for a few months and I'm working on moving to full config to org and exporting using tangle. I use Arch on my desktop and laptop but I'm learning Nix, and NixOS.

- **Emacs repo:** https://gitlab.com/ethancedwards/emacs-config
- **Dotfiles repo:** https://gitlab.com/ethancedwards8/dotfiles
- **Operating System:** Arch Linux, and I'm learning Nix/NixOS.
- **Software:** Emacs, bspwm on my desktop, SwayWM on my laptop, dmenu, bash, git bare repo for my dotfiles.
- **Keyboard:** The keyboard on my laptop and a Corsair K55 keyboard on my desktop. Hoping to build an Ergodox split keyboard soon.

### John Gormley ([@frogduckhybrid](https://github.com/frogduckhybrid))

A lot like emacs from scratch but working on making it more personal.

- **Config Repos:** https://github.com/frogduckhybrid/frogmacs
- **Operating System:** Arch Linux
- **Software:** Emacs (EXWM)
- **Keyboard:** Fnatic Gear Rush

### Name ([@glencjones](https://github.com/glencjones))

Emacs DOOM with EXWM as the widow manager, Mate or shh. So this is great as I get to have the same
development environment remotely with out the need to carry a heavy notebook. I typically use my phone and
a ssh running in samsung-dex (on the phone), so a capable dev environment via ssh is important.

- **Config Repo:** https://github.com/glencjones/doom-exwm
- **Operating System:** Gentoo, one system to rule them all.
- **Software:** Gentoo(Linux), Windows, Doom, Emacs, EXWM or Mate, C++, Java, Scala, C#.
- **Keyboard:** Old IBM Buckling Spring :) keeps the family awake at night!

## How to Add Your Config

You can easily **edit this page by [clicking here](https://github.com/SystemCrafters/crafter-configs/edit/master/README.md)** without the need to clone the repository or create a fork.  Feel free to fork and clone if you prefer, though :)

Copy the example block below and paste it in the "Crafters" section above at the end of the list then fill in the sections to match other entires you see in this file.  **Feel free to file issues with suggestions** for other sections to be added!

### Name ([@username](https://github.com/username))

[Give a brief description of your setup and anything you feel is interesting about it!]

- **Config Repo:** [A link to your configuration repo wherever it is hosted]
- **Operating System:** [This can just be Windows, macOS, or Linux, or it could be your specific Linux distribution]
- **Software:** [The list of software you use in your configuration]
- **Keyboard:** [Keyboard type/model/layout, Key re-mappings etc.]
