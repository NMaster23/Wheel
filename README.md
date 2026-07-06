# Wheel
An STM32F407VGT6 based microcontroller board designed for use with the OpenFFBoard firmware.
This is made to be used as a controller for a hoverboard hub motor. That way you can use the hoverboard for direct drive sim racing.

## Setup
This controller will be flashed with the OpenFFBoard firmware over the dedicated ST-Link port. It is the unlabeled 1 x 5 connector. I will then flash the hoverboard with: ![Hoverboard Firmware](https://github.com/flo199213/Hoverboard-Firmware-Hack-Gen2). This will then allow me to use the hoverboard as a regular BLDC motor thus allowing me to create a fully working sim wheel.

## Design

This is a picture of the full schematic:
![Schematic](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/Schematic.png)

This is a picture of the board for the MT6835 magnetic encoder:
![MT6835](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/MT6835.png)

This is a picture of the board for the Brake Chopper:
![Brake Chopper](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/Brake Schematic.png)

This is a picture of the full PCB:
![PCB](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/PCB.png)

This is a picture of the Brake Chopper PCB:
![Brake Chopper PCB](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/Brake PCB.png)

This is a picture of the expected product, but missing a few footprints:
![Product](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/Result.png)

This is a picture of the expected Brake Chopper:
![Expected Brake Chopper](https://github.com/NMaster23/Wheel/blob/3d5918cc2e5182b45f3dc3a3820b7830cf7105c5/Assets/Brake Result.png)