# RP2040-ADC16bit-CustomBoard
This repository documents the development of a custom board based on the RP2040 microcontroller, integrated with a high-resolution 16-bit external ADC. Designed for precision measurement applications in biophysics and geophysics, the board features validated PCB layout, minimal firmware, and complete technical documentation.

Component	Description
MCU	Raspberry Pi RP2040 (Dual-core ARM Cortex-M0+)
External ADC	ADS1115 (16-bit resolution, I²C interface, 4 channels)
Operating Voltage	3.3V (regulated via onboard LDO)
Interface	USB-C for communication and programming
PCB	2-layer, 50mm x 30mm, validated via DRC and ERC
Firmware	Written in C using the official Pico SDK
Sampling Rate	Up to 860 SPS (configurable via ADS1115 settings)
