# Project Description

I am trying to make a running dynamics sensor based on the [SparkFun Pro nRF52840 Mini - Bluetooth Development Board](https://www.sparkfun.com/products/15025) and a ICM20948 IMU. Starting from the example of the nRF5_SDK_17.1.0 ANT Plus hrm_tx example

# Compilation

Compiled with version 17.1.0 of Nordic SDK. S212 Softdevice and toolchain GNU Tools for Arm Embedded Processors 9-2019-q4-major 9.2.1 20191025 (release) [ARM/arm-9-branch revision 277599]

# Flashing

Flashed with a Black Pill turned to a Black Magic Probe per the instructions in this [link](https://github.com/koendv/blackmagic-blackpill). Interestingly enough a STMLink is not needed, making it a very inexpensive debugger.