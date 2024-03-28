# DX32A
The DX32A DELUXE Mini is a custom development board based on the Espressif ESP32S3 N16R8 WiFi and Bluetooth module. designed to be simple and breadboard compatible

## Features
WiFi and BLE
x25 GPIO pins
x1 WS2812B addresable RGB led
x1 MicroSD card reader


## PlatformIO support
Ive added to this repo a slightly modified version of the official S3 DevKitC .json file to this repo, drag and drop it into `.platformio/platforms/espressif32/boards` to add the DX32 to the PlatformIO boards selector, this can also be used with any other board based on the ESP32S3 N16R8
