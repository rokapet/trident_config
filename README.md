# Trident 300

This is the Klipper config of my Voron Trident 300 printer. The base of the config is the stock Voron Trident config, but there are many additional elements created by others, those I have just incorporated and use. Credit goes to the original authors.

The printer is entirely self sourced. The config at this point should be considered a work-in-progress. Prints fine though.

## Components
 - Raspberry Pi 4 with MainSailOS 32bit
 - BTT Octopus v1.1 (F446)
 - BTT TMC2209 v1.3
 - BTT EBB36 v1.2
 - BTT PiTFT50 v2
 - LDO frame
 - LDO steppers
     - LDO 42STH48-2504AC Speedy Power for XY
     - LDO Voron Trident Z-Motor kit for Z (3x LDO 42STH40-1684L300, Tr8x4)
     - LDO 36STH20-1004AHG for StealthBurner (CW2)
 - LDO rails
 - Mean Well RSP-200-24 power supply
 - PIF printed parts
 - Mellow NF-Crazy hotend (not standard for Trident, I know)
 - GDSTime fans
 - Gates GT2 belts
 - Powge idlers and pulleys
 - Fushi blue F695 bearings
 - PXKA GE5C spherical bearings
 - Keenovo 600W bed heater
 - Energetic PEI

## Mods
 - CAN bus (via Octopus CAN bridge and EBB36)
 - Umbilical
 - Tap (with PCB v2.4, lovin' it)
 - X and Y endstops relocation
 - Octopus powers Raspberry Pi via GPIO
 - Carrying handle
 - Magnetic corner clips for panels
 - Nozzle wipe and purge bucket (planned)
 - Case LEDs (planned)
 - Nevermore (planned)
