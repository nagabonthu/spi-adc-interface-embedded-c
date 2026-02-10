# SPI ADC Interface – Embedded C (Bare-Metal)

This repository contains a hands-on implementation of the SPI (Serial Peripheral Interface) protocol in Embedded C, used to interface an MCP3204 Analog-to-Digital Converter (ADC) for converting analog
voltage signals into digital data.

The project is implemented in a bare-metal environment and focuses on low-level, register-based SPI communication on an ARM microcontroller.

---

## Features
- SPI master initialization using register-level programming
- SPI transmit and receive operations
- Interfacing MCP3204 ADC via SPI
- Chip Select (CS) control and SPI data framing
- Analog voltage sampling and digital data extraction
- Modular driver-based code structure

---

## Target Platform
- ARM7-based microcontroller (LPC2129)
- Bare-metal firmware (no RTOS)
- Embedded C

---

## Repository Structure
