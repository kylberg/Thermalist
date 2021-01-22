# Thermalist
*An inexpensive thermal camera.*

## Background
I bought a Adafruit MLX90640 24x32 thermal camera module a couple of years ago. I recently got arount to interface with it from a Raspberry Pi via Python. Now with this repo I switch platform to ESP32 to create a handheld inexpensive thermal camera.  


### Similar projects
After sourcing the material I stumbeled upon this great project: https://github.com/blackcj/esp32-thermal-camera

I now believe I'm on a good track.
## Component list
- LILYGO TTGO ESP32 Module by http://www.lilygo.cn/ bought from Banggood
- Adafruit MLX90640 24x32 IR Thermal Camera Breakout - 110 Degree FoV
- LiPo battery
- 3D printed housing

This ESP32 module already got a lot already integrated including WiFi, Bluetooth, SD card reader, LCD and a few buttons!

# Build

## Hardware

The ESP32 module is a TTGO T4 V1.3: https://github.com/Xinyuan-LilyGO/LilyGo_Txx
- LCD
  -  sa

## Software

Setting up development environment for Arduino.

### Boards
Add support for ESP32 board in Arduino IDE: https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/


Don't forget to select the right board (both *ESP32 Dev Module* and *DOIT ESP DEVKIT V1* worked as target boards for me), com port, and correct baud rate (115200) 

- Adding the esp32 boards by *Espressif Systems* 1.0.4  
### Libs
- TFT_eSPI by *Bodmer* 2.3.59
- Button2 by *Lennart Henning* 1.5.1


Screen https://github.com/Xinyuan-LilyGO/TTGO-T-Display

# Experiments

First I tried the WiFiScan example from   https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/

# Final remarks