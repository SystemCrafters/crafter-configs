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

### Ethan Carter Edwards ([@ethancedwards8](https://github.com/ethancedwards8))

I've been using Emacs for a few months and I'm working on moving to full config to org and exporting using tangle. I use Arch on my desktop and laptop but I'm learning Nix, and NixOS.

- **Emacs repo:** https://gitlab.com/ethancedwards/emacs-config
- **Dotfiles repo:** https://gitlab.com/ethancedwards8/dotfiles
- **Operating System:** Arch Linux, and I'm learning Nix/NixOS.
- **Software:** Emacs, bspwm on my desktop, SwayWM on my laptop, dmenu, bash, git bare repo for my dotfiles.
- **Keyboard:** The keyboard on my laptop and a Corsair K55 keyboard on my desktop. Hoping to build an Ergodox split keyboard soon.

### John Gormley ([@frogduckhybrid](https://github.com/frogduckhybrid))

A lot like emacs from scratch but working on making it more personal.

- **Config Repos:** https://github.com/frogduckhybrid/frogmacs
- **Operating System:** Pop OS
- **Software:** Emacs
- **Keyboard:** Fnatic Gear Rush

### Glen Jones ([@glencjones](https://github.com/glencjones))

Emacs DOOM with EXWM as the window manager, Mate or ssh. So this is great as I get to have the same
development environment remotely with out the need to carry a heavy notebook. I typically use my phone and
a ssh running in samsung-dex (on the phone), so a capable dev environment via ssh is important.

- **Config Repo:** https://github.com/glencjones/doom-exwm
- **Operating System:** Gentoo, one system to rule them all.
- **Software:** Gentoo(Linux), Windows, Doom, Emacs, EXWM or Mate, C++, Java, Scala, C#.
- **Keyboard:** Old IBM Buckling Spring :) keeps the family awake at night!

### Techmo ([@techmoerror220](https://github.com/techmoerror220))

I'm not a programmer, so I unashamedly copy other people's code, often creating havoc and spending endless hours trying to fix it. Started out with Kieran Healy's [Emacs Started Kit](https://github.com/kjhealy/emacs-starter-kit) tweaked to make it work with Debian Testing and EXWM. I have a basic `init.el` file and the rest of the configuration files are stored in Org Mode files and exported with Org Babel.

- **Config Repo:** https://github.com/techmoerror220/.emacs.d
- **Operating System:** GNU Debian Testing
- **Software:** Emacs, Polybar, Redshift
- **Keyboard:** The small, programmable, mechanical and ortholinear [Atreus keyboard](https://atreus.technomancy.us/) by the great [Technomancy](https://technomancy.us/list) with noisy Matias switches and the Colemak layout.

### Ilja Kocken ([@japhir](https://github.com/japhir))

I've been building up my dotfiles since at least April 2015. It's a lot of copy-pasted stuff that I clean up thorgoughly every now and then when new understanding hits me. I'm mainly a scientist who does his data analysis in R using org-mode literate programming and ess.

- **Config Repo:** https://github.com/japhir/ArchConfigs
- **Operating System:** Arch Linux
- **Software:** [emacs](https://www.gnu.org/software/emacs/), [evil](https://github.com/emacs-evil/evil), [org-mode](https://orgmode.org/), [evil-org-mode](https://github.com/Somelauw/evil-org-mode), [org-roam](https://www.orgroam.com/), [ess](https://ess.r-project.org/), [sway](https://swaywm.org/), [waybar](https://github.com/Alexays/Waybar/), [wofi](https://hg.sr.ht/~scoopta/wofi), [mako](https://github.com/emersion/mako), [zsh](https://grml.org/zsh/) , [fzf](https://github.com/junegunn/fzf), [alacritty](https://github.com/alacritty/alacritty), [firefox](https://firefox.org/) using [vim-vixen](https://github.com/ueokande/vim-vixen/releases/tag/0.30), [org-capture](https://github.com/sprig/org-capture-extension). 
- **Keyboard:** Filco Majestouch 2 mechanical keyboard, US layout with caps remapped to ctrl and right alt as compose-key.

### Chris Hayward ([@chayward1](https://github.com/chayward1))

I'm a student who's been trying to configure my entire operating system programatically for the last year. After playing around with NixOS and Guix, I came to the conclusion that the distribution, and even the operating system you use is just a boot loader for Emacs. Based heavily on the System crafters tutorials, and takes some inspiration from Doom Emacs. So far it supports a VirtualBox VM, an installation on hardware (Acer Nitro AN515), and a fleet of Raspberry Pi's.

- **Config Repo:** https://github.com/chayward1/dotfiles
- **Operating System:** Agnostic
- **Software:** babel, org-roam, org-roam-server, hugo, reveal.js
- **Keyboard:** Raspberry Pi 400 Personal Computer with CAPS / CTRL swapped

### Pavel Korytov ([@SqrtMinusOne](https://github.com/SqrtMinusOne))

My journey in Software Development had begun in 2016. There is some evidence that I was a normal person back then, but I'm not quite convinced. I started building my dotfiles a few years later and gradually switched to keyboard-driven applications, especially i3 & Emacs. My Emacs config is somewhat focused on web development, LaTeX & org mode (especially literate programming), but has all kinds of stuff from all kinds of sources and still just the beginning of my path here.

- **Config Repo:** https://github.com/SqrtMinusOne/dotfiles
- **Operating System:** Manjaro Linux
- **Software:** Emacs, i3 + polybar, rofi, fish, tmux, notmuch, Firefox + Tridactyl, mpd + ncpmcpp, newsboat
- **Keyboard:** Genius Scorpion K220, RU/US layout. I have to switch the layouts all the time, especially in LaTeX documents, because for some reason Bolsheviks abandoned the idea of replacing Russian Cyrillic letters with Latin ones

### Dustin Lyons ([@dustinlyons](https://github.com/dustinlyons))

Like many software engineers, I've had a few "lightbulb" moments during my career that changed my course forever. First, it was vim and the idea that editors could have modes beyond insert. Then it was functional programming, avoiding state-related bugs with less indirection. Roam kicked off a "forever change" in how I take and organize notes for faster lookup. If I think about it, I'm chasing these moments as they significantly propel my productivity or quality of work forward.

[I left a job](https://www.slideshare.net/Lightbend/how-credit-karma-makes-realtime-decisions-for-60-million-users-with-akka-streams-and-actors) in the Bay Area and moved to a quieter part of the country with my family. As I was searching for a way to have proper vim bindings writing networked notes (i.e., Roam), I discovered org-roam, which eventually opened up the world of Emacs (thanks [David!](https://www.youtube.com/playlist?list=PLEoMzSkcN8oPH1au7H6B7bBJ4ZO7BXjSZ)) and Guix. HUGE lightbulb. We all know Emacs is life but have you tried Guix? The ability to reason about your OS using Scheme, with transactional rollbacks and virtualenv-all-the-things, gives you super powers.

I'll be actively building out my guix-config over the next several months. Check out my repo below to follow along!

- **Config Repo:** https://github.com/dustinlyons/guix-config, https://github.com/dustinlyons/dotfiles
- **Operating System:** GNU Guix
- **Software:** emacs, openbox, rofi, zsh, org-roam, brave, alacritty, polybar, picom, thunar, dunst
- **Keyboard:** GMMK PRO with Gateron Ink Black v2's and EBPT White-on-Black keycaps

## How to Add Your Config

You can easily **edit this page by [clicking here](https://github.com/SystemCrafters/crafter-configs/edit/master/README.md)** without the need to clone the repository or create a fork.  Feel free to fork and clone if you prefer, though :)

Copy the example block below and paste it in the "Crafters" section above at the end of the list then fill in the sections to match other entires you see in this file.  **Feel free to file issues with suggestions** for other sections to be added!

### Name ([@username](https://github.com/username))

[Give a brief description of your setup and anything you feel is interesting about it!]

- **Config Repo:** [A link to your configuration repo wherever it is hosted]
- **Operating System:** [This can just be Windows, macOS, or Linux, or it could be your specific Linux distribution]
- **Software:** [The list of software you use in your configuration]
- **Keyboard:** [Keyboard type/model/layout, Key re-mappings etc.]
