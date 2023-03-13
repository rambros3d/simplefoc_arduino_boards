
# SimpleFOC Arduino Boards

This is a collection of board definitions for Arduino IDE, to help you get up and running quickly with our SimpleFOC ESC boards with on-board MCUs.

# Installing

Requirements: 
- Arduino IDE 2
- [STM32 Arduino Core](https://github.com/stm32duino/Arduino_Core_STM32) 2.4.0 or newer (Board Manager URL: [https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json](https://github.com/stm32duino/BoardManagerFiles/raw/main/package_stmicroelectronics_index.json))
- Start Arduino IDE 2, go to the boards manager, and make sure you have version 2.4.0 (or newer) of the STM32 board package installed.
- Quit Arduino IDE to do the install.


Where to Install:
1. Find your Arduino Sketchbook folder. Normally you can find it here:
   - Windows: `C:\Users\{username}\Documents\Arduino`
   - macOS: `/Users/{username}/Documents/Arduino`
   - Linux: `/home/{username}/Arduino`
1. Inside the Sketchbook folder, find (or create) the folder `hardware`

Install from GIT:
1. Inside the `hardware` folder, git clone this repository \
`git clone https://github.com/simplefoc/simplefoc_arduino_boards.git simplefoc`

Install from ZIP file:
1. Use the green "Code" button on the github repository page and choose "Download ZIP".
1. Extract the resulting ZIP file to the `hardware` folder in your Sketchbook folder
1. Rename the extracted folder as "simplefoc"

Check it is working:
1. Start Ardunio IDE
1. You can now choose "SimpleFOC Boards" in the boards menu.


# Boards included

- SimpleFOC Lepton v2 by Valentine - STM32G031 64kB flash