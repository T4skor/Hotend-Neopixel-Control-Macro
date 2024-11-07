# Hotend Neopixel Control

## Description

This macro allows you to control a Neopixel LED based on the temperature of the hotend in a 3D printer running Klipper firmware. The Neopixel's color changes depending on the hotend's temperature range:

Green: Hotend is 40°C or lower.

Red: Hotend is between 40°C and 100°C.

Purple: Hotend is above 100°C.

White: Neopixel turns white when the printer starts a print job.

## How to Add This Macro to Klipper
Step 1: Download "neopixel.cfg"

Step 2: Put your neopixel pin where the macro asks for it. 

Step 3: Place it on your Klipper configuration directory

Step 4: Put in your print_start.cfg "CANCEL_TEMPERATURE_MONITOR"

Step 5: In your print_end.cfg put "START_TEMPERATURE_MONITOR"

Step 6: In your printer.cfg put "[include neopixel.cfg]"

Step 7: Restart your Klipper

## Happy Printing!
