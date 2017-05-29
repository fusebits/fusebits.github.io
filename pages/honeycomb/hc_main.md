---
title: Honeycomb
sidebar: mydoc_sidebar
permalink: hc_main.html
toc: false
folder: honeycomb
---

Honeycomb is a line of development boards designed to get you stated with Silicon Labs' EFM8 line of microcontrollers.


### Features

Honeycomb uses an [EFM8UB10F16](https://www.silabs.com/documents/public/data-sheets/EFM8UB1_DataSheet.pdf). It's a really neat MCU with some interesting specs and features.

* Full speed USB 2.0 transciever
* Built in USB bootloader for easy programming
* Hardware Debugging
* Up to 12 GPIO
* 11 ADC inputs
* SPI/I2C/UART
* 3.3V/5V tolerant IO
* 16KB Flash

The board has a reset button conected to RSTb, and an LED on P0.0.

### Pinout

Every Pin except for the USB pins are broken out to the headers.

![pinout](/images/HoneycombPinout.png){:class="img-responsive"}

### Software

The Honeycomb can be programmed over USB from [Silicon Labs' Simplicity Studio](http://www.silabs.com/products/development-tools/software/simplicity-studio). Simplicity Studio can also be used to hardware debug over the C2 interface. 



{% include links.html %}