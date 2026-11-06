
# Boardoza ADS1115 16-Bit ADC Breakout Board

The **Boardoza ADS1115 Breakout Board** is a high-resolution analog-to-digital conversion module based on the **Texas Instruments ADS1115 16-bit ADC**. It features four configurable analog input channels that support both single-ended and differential measurements. With its integrated programmable gain amplifier (PGA), internal voltage reference, and low-noise architecture, the board enables accurate analog signal acquisition for embedded systems and sensor applications.

The board operates with a **3.3V to 5V power supply** and communicates through an **I²C interface**, making it compatible with Arduino, Raspberry Pi, ESP32, STM32, and other microcontroller platforms. The board is suitable for **precision sensor monitoring, voltage measurement, data acquisition, and industrial control applications**.

---

## PCB Pictures

| Front Side | Back Side |
| :---: | :---: |
| ![Front](./assets/ADS1115%20Front.png) | ![Back](./assets/ADS1115%20Back.png) |

---

## Key Features

- **16-Bit ADC Resolution:** Provides high-resolution analog-to-digital conversion for precise sensor and voltage measurements.
- **Flexible Analog Inputs:** Supports four single-ended inputs or two differential measurements through a configurable input multiplexer.
- **I²C Communication Interface:** Enables easy integration with microcontrollers using a two-wire communication interface.
- **Programmable Gain Amplifier (PGA):** Supports selectable full-scale input ranges for measuring signals of different amplitudes.
- **Low-Power Operation:** Supports single-shot and continuous conversion modes for energy-efficient measurement applications.

---

## Technical Specifications

**Model:** ADS1115  
**Manufacturer:** Boardoza  
**Manufacturer IC:** Texas Instruments  
**Input Voltage:** 3.3V - 5V  
**Interface:** I²C  
**Resolution:** 16-bit  
**Analog Input Channels:** 4 Single-Ended or 2 Differential  
**Programmable Data Rate:** 8SPS - 860SPS  
**Internal Reference:** Integrated Voltage Reference  
**Operating Modes:** Single-Shot and Continuous Conversion  
**Operating Temperature:** -40°C to +125°C  
**Board Dimensions:** 20mm x 40mm  

> **Note:** The programmable full-scale range does not represent the maximum allowable voltage on the analog input pins. Input voltages must remain within the ADS1115 supply limits.

---

## Board Pinout

### ( J1 ) Power Supply and I²C Communication Pins

| Pin Number | Pin Name | Description |
| :---: | :---: | --- |
| 1 | VIN | Power Supply Input (3.3V - 5V) |
| 2 | ALERT | Programmable Comparator Output or Conversion-Ready Signal |
| 3 | SDA | I²C Serial Data Line |
| 4 | SCL | I²C Serial Clock Line |
| 5 | GND | Ground Connection |

### ( J2 ) Analog Input Pins

| Pin Number | Pin Name | Description |
| :---: | :---: | --- |
| 1 | AIN3 | Analog Input 3. |
| 2 | AIN2 | Analog Input 2. |
| 3 | AIN1 | Analog Input 1. |
| 4 | AIN0 | Analog Input 0. |

---

## Board Dimensions

<img src="./assets/ADS1115 Dimensions.png" alt="ADS1115 Board Dimensions" width="450"/>

---

## Step Files

[Boardoza ADS1115.step](./assets/ADS1115%20Step.step)

---

## Datasheet

[ADS1115 Datasheet.pdf](./assets/ADS1115%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact <support@boardoza.com>

---

## **License**

This repository contains both hardware and software components:

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### **Software/Firmware**

[![BSD-3-Clause][bsd-shield]][bsd]

All software and firmware are licensed under [BSD 3-Clause License][bsd].

[bsd]: https://opensource.org/licenses/BSD-3-Clause
[bsd-shield]: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg
