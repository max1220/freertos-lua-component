# freertos-lua-component
Vanilla Lua 5.3.4 as a FreeRTOS module. Except disabling the OS library, the source code is not modified at all.
Basically adding a component.mk and an include dir to the Lua source.
This is diffrent from https://github.com/whitecatboard/Lua-RTOS-ESP32, which aims to provide a full-featured Lua-powered environment.

## Usage
Copy the Lua/ directory into the components/ directory in your project.

## Todo

 * Add KConfig for tweakable parameters
