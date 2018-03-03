# freertos-lua-component
Vanilla Lua 5.3.4 as a FreeRTOS module. Except disabling the OS library, the source code is not modified at all.
Basically adding a component.mk and an include dir to the Lua source.
This is diffrent from https://github.com/whitecatboard/Lua-RTOS-ESP32, which aims to provide a full-featured Lua-powered environment.

## Warning
You should not use this in production. This code is _not_ testes and _not_ efficient. It's missing a lot of optimizations, and currently doest not provide a way to interact with the outside world from within Lua. See above for an actually usefull implementation.
*This component was only made for toy purposes!*


## Usage
Copy the Lua/ directory into the components/ directory in your project.

## Todo

 * Add KConfig for tweakable parameters
