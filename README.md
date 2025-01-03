# Trident 300

This is the Klipper config of my Voron Trident 300 printer. The base of the config is the stock Voron Trident config, but there are many additional elements created by others, those I have just incorporated and use. Credit goes to the original authors.

The printer is entirely self sourced. ~~The config at this point should be considered a work-in-progress.~~ Prints fine. More than 300 hours and counting...

## Components
 - Raspberry Pi 4 with MainSailOS 32bit
 - BigTreeTech electronics
     - BTT Octopus v1.1 (F446)
     - BTT TMC2209 v1.3
     - BTT EBB36 v1.2 (heatsink on MCU and TMC chip as well)
     - BTT PiTFT50 v2
 - LDO frame
 - LDO steppers
     - LDO 42STH48-2504AC Speedy Power for XY
     - LDO Voron Trident Z-Motor kit for Z (3x LDO 42STH40-1684L300, Tr8x4)
     - LDO 36STH20-1004AHG for StealthBurner (ClockWork2)
 - LDO rails
 - Mean Well RSP-200-24 power supply
 - PIF printed parts
 - Mellow NF-Crazy hotend (not standard for Trident, I know)
 - Keenovo 600W bed heater
 - Energetic PEI printing surface
 - GDSTime fans
 - Gates GT2 belts
 - Powge idlers and pulleys
 - Fushi blue F695 bearings
 - PXKA GE5C spherical bearings

## Mods
 - CAN bus (via Octopus CAN bridge and EBB36)
 - Umbilical
 - Tap with PCB v2.4 (loving it)
 - X and Y endstops relocation
 - Raspberry Pi is powered by ~~Octopus via GPIO~~ the stock Mean Well RS-25-5 PSU because of previous constant undervoltage warnings
 - Carrying handle
 - Magnetic corner clips for panels
 - Nozzle wipe and purge bucket
 - Case LEDs
 - Enclosure temperature/VOC sensor (BME680)
 - VEFACH or Nevermore or BentoBox or something similar (planned)
 - Top Hat or Canopy or similar (planned - I don't want to reprint a carrying handle, but the current handle does not seem to be compatible...)
