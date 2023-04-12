# patch-nerd-fonts
Regular fonts are patched using `font-patcher` script from [**NERD FONTS**][1]
and `fontforge` from [**FONT FORGE**][2]. Function of this script is to automate
downloading and installing packages, python modules, programs and scripts
necessary for font patching.

### Note: This script only works on **debian** and **debian derivatives**.


# Prerequisites
This is **zsh** script, thus **zsh** shell must be present on the system.


# Installation
Clone this repo. In repo there is script `patch-fonts` which does all the
heavy lifting.


# Usage
If you run `./patch-fonts` script available commands will be shown:

```
usage:
  patch-fonts COMMAND

commands:
  patch      - patch a font
  install    - install already patched font
  restore    - restore previously backed up fonts

  setup      - install neccesary programs/modules (pkg, python ...)
  check      - check if all neccesary programs/modules are installed
  clean      - remove packages which were installed by this script

note:
  command names can be abbrevated: inst, pa, ...
```

By running above commands you can:

 - install, check for presence or uninstall necessary
   packages, modules and scripts
 - patch regular font
 - install patched font onto the system
 - restore previously installed fonts 

Below are shown examples of commands execution.


## setup

![setup process](media/setup.gif)

## patch

![patch process](media/patch.gif)

## install

![install process](media/install.gif)

## restore

![restore process](media/restore.gif)

## check

![check-ok process](media/check-ok.gif)
![check-fail process](media/check-fail.gif)

## clean

![clean process](media/clean.gif)

[1]: https://github.com/ryanoasis/nerd-fonts
[2]: https://github.com/fontforge/fontforge

