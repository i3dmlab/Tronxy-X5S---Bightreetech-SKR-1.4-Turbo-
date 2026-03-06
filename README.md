# Tronxy-X5S---Bightreetech-SKR-1.4-Turbo-TMC2209
In this repo you find the configuration.h, configuration_adv.h and platformio.ini files to use to code the Marlin firmware for a Tronxy X5S with a Bigtreetech SKR 1.4 Turbo board and TMC2209 drivers

Basic: Marlin 2.1.x bugfix Release

In this configuration X/Y/Z TMC2209 drivers need a pin to be cutted out to use physical endstops. 

Hotend fan is connected with 2.4 pin of the mainboard  

I am not the creator of Marlin, I am not the creator of SKR boards, I am not the creator of Tronxy X5S printers. 
This is just a user project for an upgrade of the mainboard of the 3d printer. 

IMPORTANT: This is a work in progress project and you use it at your own risk.

How to 
Instructions: 1) Install Visual Studio Code  https://code.visualstudio.com/
              2) Install PlatformIO extension in Visual Studio Code
              3) Install Marlin firmware auto build extension in Visual Studio Code
              4) Download Marlin 2.1.x "bugfix" https://marlinfw.org/meta/download/
              5) Unzip Marlin 2.1.x bugfix and create a "Marlin 2.1.x bugfix" folder
              6) Dowload platformio.ini file from this repository
              7) Copy platformio.ini file in the main unzipped folder "Marlin 2.1.x bugfix"
              8) Dowload configuration.h, configuration_adv.h files from this repository
              9) Copy configuration.h, configuration_adv.h files in Marlin folder inside the main unzipped folder "Marlin 2.1.x bugfix" 
              10) Open Pio home in Visual Studio Code
              11) Click Open --> click open project  --> chose the Marlin 2.1.x bugfix unzipped folder --> click open 
              12) Open platformio.ini file in Visual studio code
              13) Click Build in Visual studio code
              14) Search firmware.bin with windows search tool inside Marlin 2.1.x bugfix folder
              15) Copy firmware.bin file on a SDHC card (8GB max) and flash the new firmware on your SKR 1.4 turbo mainboard 
