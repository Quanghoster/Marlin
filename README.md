# Marlin 3D Printer Firmware

## Marlin 1.1 for AnyCubicPrusa i3
This code modified the Prusa codebase configuration to work on the Anycubic Prusa i3

The mods focus the following files.
Configuration.h
Configuration_adv.h
pins_RAMPS.h

## Warning
I'm working on updating my printer to use TMC2130 stepper drivers.
There is currently a conflict between the MC2130 library and the 1.1.x main branch so this repo is currently working off the Marlin 1.1bugfix branch.
This will move back to the main branch once fixed.
