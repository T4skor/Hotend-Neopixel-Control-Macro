# Hotend Neopixel Control

## Description

This macro allows you to control a Neopixel LED based on the temperature of the hotend in a 3D printer running Klipper firmware. The Neopixel's color changes depending on the hotend's temperature range:

Green: Hotend is at 40°C or lower.

Purple: Hotend is between 40°C and 100°C.

Red: Hotend is above 100°C.

White: Neopixel turns white when the printer starts a print job.

## How to Add This Macro to Klipper
Step 1: Download "neopixel.cfg"

Step 2: Put your neopixel pin where the macro asks for it. 

Step 3: Place it on your Klipper configuration directory

Step 4: In your printer.cfg put "[include neopixel.cfg]"

Step 5: Restart your Klipper

## Happy Printing!
