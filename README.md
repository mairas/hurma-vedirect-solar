# VE.Direct Solar Charge Controller Interface Firmware for Hurma

This repository provides "production" firmware for the SH-ESP32 device interfacing a Victron Energy solar charge controller with the Signal K server on s/y Hurma.

The repository should be usable as is for interfacing any Victron MPPT controller; just change `SOLAR_CHARGE_CONTROLLER_ID` on `src/main.cpp` to your liking.

For more information, see the README for the [SensESP/VEDirect](https://github.com/SensESP/VEDirect) library.
