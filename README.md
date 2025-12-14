# KiCad Library: MLX90640 Thermal Camera Module

This repository contains a verified **KiCad Symbol** and **Footprint** for the MLX90640 IR Thermal Camera breakout board.

![MLX90640_Board](https://github.com/user-attachments/assets/a9d26378-7992-4389-addd-922029a9eabe)
<br>
*A generic MLX90640 Module (32x24 IR Array), which this library is designed to represent.*

I created this library to accurately reflect the MLX90640 Modules commonly found on Amazon/AliExpress, as standard libraries often miss the specific footprint for these breakout boards.

### Features

-   **Correct Pin Count:** 8 Pins.
-   **Accurate Pinout:** VCC, GND, SCL, SDA (Standard I2C configuration).

## 📂 Files Included

### Schematic Symbol (`MLX90640.kicad_sym`)

![KiCad Symbol Screenshot](https://github.com/user-attachments/assets/df8fa6ec-2c85-44ec-8789-db73dbd3a44c)
<br>
*The schematic symbol, featuring the standard I2C connection pins.*

## How to Use

1.  Download the files from this repository.
2.  In KiCad, go to **Preferences > Manage Symbol Libraries** and add the `.kicad_sym` file.
3.  You can now search for `MLX90640` in your schematic editor!
