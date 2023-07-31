# KiCad-GP2040-CE-Pico-Template
Pico based template for KiCad projects

## Installation Instructions
Clone this repository into your KiCad Templates folder. 

### Windows

By default (on Windows), KiCad uses `%userprofile%\Documents\KiCad\7.0\template` folder for user templates.

After cloning, you'll need to clone the submodules. `git submodule update --init`

### Linux

#### Arch

```
cd /usr/share/kicad/template/
git clone https://github.com/becauseimclever/KiCad-GP2040-CE-Pico-Template
cd KiCad-GP2040-CE-Pico-Template
git submodule update --init
```

## Included Libraries

### [KiCad-RP-Pico](https://github.com/ncarandini/KiCad-RP-Pico)

A simple repository of files needed to add a 3D footprint of the Raspberry Pi Pico board to KiCad.

### [kiswitch](https://github.com/kiswitch/kiswitch)

A footprint library for most popular keyboard switches. 
