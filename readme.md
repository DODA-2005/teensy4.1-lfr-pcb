# Teensy 4.1 Line Follower Robot – Competition PCB

A custom-designed, fabricated, and tested PCB for a high-speed Line Follower Robot (LFR),
built around the Teensy 4.1 microcontroller and optimized for competitive robotics use.

This repository contains **only the hardware design files** (PCB, schematic, and fabrication outputs).
Firmware is intentionally not included.

---

## Overview

This PCB was designed from scratch for use in competitive line-following robots where
speed, stability, and reliable sensor acquisition are critical.

The design focuses on:
- clean analog signal routing
- mechanical–electrical integration
- ease of tuning during competitions
- real-world performance on tracks

The board has been fabricated, assembled, and tested on a working robot.

---

## Key Features

- Teensy 4.1 based high-performance control board
- Curved front-mounted IR sensor array for wide and consistent line coverage
- Optimized analog routing for stable ADC readings at high speed
- On-board tactile buttons for mode selection and tuning
- Symmetric layout for predictable motion behavior
- PCB designed to act as a structural element of the robot
- Competition-tested hardware design

---
## Motor Driver Variants

Two PCB variants were designed and fabricated to evaluate different motor driver
configurations for competitive line-following robots.

Both variants share the same core architecture, sensor layout, and mechanical form factor.

---

### Variant A: TB6612FNG

- Motor Driver: TB6612FNG
- Known for robustness and stable performance
- Suitable for higher current margin applications
- Used in early competition testing

#### Assembled PCB
![TB6612FNG PCB – With Motors](images/tb6612fng/with_motors.jpg)

---

### Variant B: DRV8833

- Motor Driver: DRV8833
- Compact and efficient dual H-bridge driver
- Lower Rds(on), improved thermal behavior
- Evaluated as an alternative motor driver solution

#### Assembled PCB
![DRV8833 PCB – With Motors](images/drv8833/with_motors.jpg)


## PCB Specifications

- Layers: 2
- Material: FR4
- Controller: Teensy 4.1
- Sensor Interface: Analog IR sensor array
- Motor Interface: Dual DC motors
- Power Input: Li-ion / LiPo compatible
- Design Tool: EasyEDA

---

## Repository Contents


---

## Fabrication

This PCB can be fabricated by directly uploading the Gerber files to any PCB manufacturer
(e.g., JLCPCB, PCBWay).

Recommended fabrication settings:
- 2-layer board
- 1.6 mm thickness
- FR4 material
- Green solder mask

---

## Project Status

✔ PCB designed  
✔ PCB fabricated  
✔ Assembled and tested on robot  
✔ Used in competitive line-following environments  
✖ Firmware intentionally excluded  

---

## License

This project is released as **open hardware** under the  
**CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P v2)**.

You are free to:
- manufacture the PCB
- modify the design
- use it in personal or academic projects

**Attribution to the original author is required.**

See the `LICENSE` file for full terms.

---

## Disclaimer

This hardware design is provided for educational and experimental purposes.
The author assumes no responsibility for damage, malfunction, or misuse.
Use at your own risk.
