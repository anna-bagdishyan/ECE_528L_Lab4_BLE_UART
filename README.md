# ECE 528/L - Robotics and Embedded Systems with Lab
**CSU Northridge**

**Department of Electrical and Computer Engineering**

## Bluetooth Low Energy (BLE) Lab
The Bluetooth Low Energy (BLE) lab interfaces with the following:

* User LEDs of the TI MSP432 LaunchPad
* Pololu Gearmotor with Encoder - [Product Link](https://www.pololu.com/product/3675)
* Adafruit Bluefruit LE UART Friend - Bluetooth Low Energy (BLE) Module - [Product Link](https://www.adafruit.com/product/2479)

## Overview
This lab used the UART protocol to send and receive data with the MSP432 LaunchPad. The EUSCI_A3 module was set up in UART mode, and a driver was written for the Adafruit Bluefruit LE UART module. This driver let the LaunchPad talk to a phone over Bluetooth Low Energy (BLE) through the Bluefruit Connect app. First, the driver was used to turn the RGB LED on and off with text commands sent from the phone. Next, an oscilloscope was used to look at the UART signal and check the start bit, data bits, stop bit and bit period. The PMOD SWT switches were also used to pick which byte to send. Finally, the button packets from the app's Control Pad were read and used to drive the robot forward, backward, left and right.
## Components Used
| Components Used | Quantity    | Manufacturer 
| -------------   | ----------- | -----------
| MSP432 Launchpad  | 1 | Texas Instruments
| USB-A to Micro-USB Cable  | 1 | N/A
| TI-RSLK MAX Chassis   | 1 | Pololu
| Adafruit BLE UART Modul  | 1 | Adafruit
| PMOD SWT | 1 | Digilent
| Oscilloscope Probe | 1 | N/A

## Prelab
1. 

## Analysis and Results  
### Task 1  

### Task 2

## Known Issues or Limitations  
There are no known current issues or limitations.  

## Author Contribution  
Anna  
- 

Mario  
- 
  
## References
ECE 528/L Lab 4 - Wireless Control.
