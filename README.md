
# SimpleFOC Arduino Boards

This is a collection of board definitions for Arduino IDE, to help you get up and running quickly with our SimpleFOC ESC boards with on-board MCUs.

# Installing

Requires: 
- Arduino IDE 2
- [STM32 Arduino Core](https://github.com/stm32duino/Arduino_Core_STM32) 2.4.0 or newer (Board Manager URL: [https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json](https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json))

To Install:
1. Start Arduino IDE 2, go to the boards manager, and make sure you have version 2.4.0 (or newer) of the STM32 board package installed.
1. Quit Arduino IDE
1. Find your Arduino folder in your Documents folder (where your sketches live).
1. Inside it, there is a folder called "hardware".
1. Inside the `Documents/Arduino/hardware` folder, git clone this repository \
`git clone https://github.com/runger1101001/simplefoc_arduino_boards`
1. Start Ardunio IDE
1. You can now choose "SimpleFOC Boards" in the boards menu.

Alternatively you can also use the "Download as ZIP" option for this repository, and unzip the archive to the `Documents/Arduino/hardware` folder.

# Boards included

- SimpleFOC Lepton v2 by Valentine - STM32G031 32kB flash