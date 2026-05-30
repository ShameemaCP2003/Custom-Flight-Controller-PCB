# Custom Flight Controller PCB

Open-source STM32-based flight controller designed in KiCad for PX4 and ArduPilot-compatible UAV platforms.

---

## Overview

This project is a custom flight controller developed from scratch as a learning and engineering exercise in embedded hardware design, sensor integration, power management, and PCB development.

The design is inspired by modern flight controller architectures and incorporates a high-performance STM32 microcontroller, onboard inertial sensors, environmental sensing, multiple communication interfaces, and PWM outputs for UAV control applications.

---

## Features

- STM32F446RET6 ARM Cortex-M4 MCU
- ICM-42670-P 6-Axis IMU
- BMP390 Barometric Pressure Sensor
- USB Type-C Interface
- CAN Bus Support
- Multiple UART Interfaces
- Dual SPI Interfaces
- ADC Inputs
- GPIO Expansion
- 6 Servo/PWM Outputs
- SWD Programming Interface
- Onboard 3.3V Regulation
- Power Protection Circuitry

---

## Hardware Specifications

| Component | Part Number |
|------------|------------|
| MCU | STM32F446RET6 |
| IMU | ICM-42670-P |
| Barometer | BMP390 |
| Voltage Regulator | SPX3819 |
| Crystal | 3.2mm × 2.5mm |
| USB Interface | USB Type-C |

---

## Communication Interfaces

| Interface | Quantity |
|------------|----------|
| CAN Bus | 1 |
| UART | 3 |
| SPI | 2 |
| ADC | 2 |
| GPIO Input | 1 |
| GPIO Output | 2 |

---

## PWM Outputs

| Output |
|----------|
| Servo 1 |
| Servo 2 |
| Servo 3 |
| Servo 4 |
| Servo 5 |
| Servo 6 |

---

## PCB Statistics

| Parameter | Value |
|------------|---------|
| Layers | 2 |
| Nets | 79 |
| Pads | 291 |
| Vias | 297 |
| Unrouted Nets | 0 |
| ERC Status | Passed |
| DRC Status | Passed |

---

## Design Workflow

1. Requirements Definition
2. Component Selection
3. Schematic Design
4. ERC Validation
5. PCB Placement
6. PCB Routing
7. Ground Plane Implementation
8. DRC Verification
9. Prototype Preparation

---

## Current Status

- ✅ Schematic Complete
- ✅ PCB Layout Complete
- ✅ ERC Passed
- ✅ DRC Passed
- ⏳ Prototype Manufacturing Pending
- ⏳ Hardware Bring-Up Pending
- ⏳ PX4 Integration Pending

---

## Future Improvements

Planned future revisions include:

- Dual redundant IMU architecture
- SD card logging
- Additional CAN interfaces
- GPS connector
- Battery management system
- Power monitoring enhancements
- 4-layer PCB revision
- PX4 board support package
- ArduPilot board support package

---

## Repository Structure

hardware/
├── schematic/
└── pcb/

docs/
└── images/

firmware/

---

## Acknowledgements

This project was created as a learning and engineering exercise in custom flight controller design.

The development process was heavily influenced by the open-source embedded systems community, including the educational content and flight controller development resources shared by Timothy Kowalski.

## References

This project was developed with the help of open-source resources and educational content.

### Timothy Kowalski

Special thanks to Timothy Kowalski for sharing detailed flight controller development content and open-source hardware resources.

Reference Project:
- [Custom Flight Controller](https://github.com/HomeGliders/FCV2)
