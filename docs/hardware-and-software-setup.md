---
title: Setup
description: Learn how to download and install a UF2 file on your OBD-Kill. Follow simple steps to flash firmware using Raspberry Pi Pico's bootloader mode via USB.
keywords: [OBD-Kill, UF2 file, Raspberry Pi Pico, bootloader mode, firmware update, CAN Hack UF2, micro USB, RPI-RP2, flashing firmware, Defcon 30]
sidebar_position: 5
sidebar_label: Setup
---

# Setup

### 4. **How to download a UF2 File to your OBD-Kill**

Download the CAN Hack UF2 File at [https://cdn.intrepidcs.net/guides/OBD-Kill/defcon30\_uf2.zip](https://cdn.intrepidcs.net/guides/OBD-Kill/defcon30\_uf2.zip)

### 4.1 CONNECT THE OBD-Kill PICO TO YOUR COMPUTER

* Connect the micro USB cable to your host computer.
* Connect the other end of the micro USB cable to the Pico while you press and hold the **BOOTSEL** button on the Pico. This will cause the Raspberry Pi Pico to enter bootloader mode and allow you to upload a new UF2 File.

<div class="text--center">

<figure>

![pico](./assets/pico.png "pico")
<figcaption></figcaption>
</figure>
</div>

<!-- ![](.gitbook/assets/image11-1.png) -->

* Release the button once the cable is connected.

**A disk volume called RPI-RP2 will appear on your computer.**

### 4.2 Load a UF2 File to the Raspberry Pi Pico

* Open **RPI-RP2** on your computer by double-clicking it.
* Drag and drop the **.uf2** file that you downloaded earlier.

**RPI-RP2 will unmount and the LEDs on your OBD-Kill will start blinking**

You’ve just uploaded the first bit of code to your Pico!