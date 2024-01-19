
:warning:
I moved on to Home Assistant, so I won't develop anything for OpenHAB anymore.
:warning:

# OpenHAB Codeschnipsel

My Code-Snippets for OpenHAB. Free to use and modify for everyone.

## Anycubic

Stuff for integration of my Anycubic 3D Printer. Or to be exact: To integrate Klipper/Mainsail

## Aqara

I use a lot of Aqara devices in my setup. Environmental sensors, switches, the cube... They are connected using [Zigbee2Mqtt](https://www.zigbee2mqtt.io) but often need some rules. Most of all: The state must be reset, otherwise the script wont be triggered on a new event.
Besides that, the doorswitches return true/false instead of open/close,

## Denon-AVR

Just some stuff for my Denon AVR after digging through the Denon communication specifications and lots of testing

## Roborock

Items, rules and things for my Roborock vacuum cleaner running [Valetudo](https://valetudo.cloud/)

## Misc

Some other stuff:

- motionlight.rules: A rule to trigger a group of lights with motion detection sensors and a button. Depends on time of day and different settings for single or double click of the button.
