A project developed for the PIC18F16Q41 Curiosity Nano demonstrating I²C communication using two VL53L4CD Time-of-Flight sensors.

The firmware dynamically reassigns one sensor's I²C address through the XSHUT pin, allowing both sensors to operate simultaneously on the same bus. Distance measurements are continuously displayed on a 16×2 LCD in real time.

## Features

- PIC18F16Q41 Curiosity Nano
- Dual VL53L4CD ToF sensors
- Dynamic I²C address reassignment (0x29 → 0x30)
- 16×2 LCD (4-bit interface)
- Real-time distance measurement
- Developed with MPLAB X IDE, XC8, and MCC Melody

## Hardware

- PIC18F16Q41 Curiosity Nano
- 2× VL53L4CD Time-of-Flight Sensors
- 16×2 Character LCD
- I²C Bus
- XSHUT control lines
