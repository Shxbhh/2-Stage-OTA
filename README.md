# Two-Stage Miller Compensated OTA

This repository contains simulation files for a two-stage Miller compensated Operational Transconductance Amplifier (OTA) designed in 180nm CMOS technology. The design achieves high gain, wide bandwidth, and robust phase margin, making it suitable for precision analog applications.

## Features & Specifications

* **Open-Loop Gain**: 60 dB
* **Closed-Loop Gain**: 2 (Unity plus feedback divider)
* **Gain-Bandwidth Product (GBW)**: 20 MHz
* **Phase Margin**: ≥ 60°
* **Input Common-Mode Range (ICMR)**: 0.8 V – 1.6 V
* **Slew Rate**: 15 V/μs
* **Power Consumption**: 140 μW
* **Supply**: 1.8 V (Single Rail)
* **Load Capacitance**: 10 pF

## Files Included
1. Schematic (LTSpice) .asc files.
2. Handwritten calculations and design.
3. Screenshots displaying the phase margin and the bandwidth.
4. DC Operating points of different nodes.
5. LTSpice Simulation Logs.

## Design Overview

1. **First Stage**: Differential pair with active load to provide high gain.
2. **Miller Compensation**: A capacitor between the first and second stage ensures stability and sets the dominant pole.
3. **Second Stage**: Common-source amplifier to boost the gain.
4. **Feedback Network**: Sets closed-loop gain of 2 (unity feedback with a two-resistor divider).

##





