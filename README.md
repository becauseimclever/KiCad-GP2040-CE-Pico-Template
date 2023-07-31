# KiCad-GP2040-CE-Pico-Template
Pico based template for KiCad projects

## Installation Instructions
Clone this repository into your user KiCad Templates folder. 

### Windows

By default (on Windows), KiCad uses `%userprofile%\Documents\KiCad\7.0\template` folder for user templates.

After cloning, you'll need to clone the submodules. `git submodule update --init`

### Linux

#### Arch

Find the version of Kicad being used on your system using `pacman -Q kicad` in your terminal. This version number will be used in the following step, replacing {VERSION} with yours. 

Example: kicad 7.0.6-1 -> {VERSION} = 7.0

```
cd ~/.local/share/kicad/{VERSION}/template/
git clone https://github.com/becauseimclever/KiCad-GP2040-CE-Pico-Template
cd KiCad-GP2040-CE-Pico-Template
git submodule update --init
```

## Update Template

#### Arch

```
cd ~/.local/share/kicad/{VERSION}/template/KiCad-GP2040-CE-Pico-Template
git pull origin master
git submodule update --remote
```

## Included Libraries

### [KiCad-RP-Pico](https://github.com/ncarandini/KiCad-RP-Pico)

A simple repository of files needed to add a 3D footprint of the Raspberry Pi Pico board to KiCad.

### [kiswitch](https://github.com/kiswitch/kiswitch)

A footprint library for most popular keyboard switches. 
