# Firmware

This folder contains the Arduino sketches that make up the firmware that runs on the ESP32. Go [here](https://sparkfun.github.io/SparkFun_RTK_Firmware/firmware_update/#zed-f9x-firmware) for more information about the firmware that runs the ZED-F9x Receiver.

* **RTK_Surveyor** - The main firmware for the RTK Surveyor PLUS additional code to suport the VEML7700 Lux sensor connected via qwiic connector over I2C. Also included in this folder is packet_defs.hpp that adds remote GUI functionality. 

* **Test Sketches** - Various sketches used in the making of the main firmware. Used internally to verify different features. Reader beware.

## Compilation Instructions

See [Compiling Source](https://sparkfun.github.io/SparkFun_RTK_Firmware/firmware_update/#compiling-source) for detailed steps.
