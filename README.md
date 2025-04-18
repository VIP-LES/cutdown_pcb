# Cutdown PCB – MK5

## Overview

This repository contains the **MK5** revision of the custom PCB used in the Spring 2025 high-altitude balloon cutdown payload. The board integrates all key circuitry for telemetry, sensor data acquisition, LoRa radio communication, and the nichrome-based cutdown system.

Designed and iterated over **11 fabrication runs** (I know, it was painful), this board represents the final, flyable hardware developed using Georgia Tech’s **HIVE** LKPF Protomat and Protolaser systems.

## Fabrication Notes

- **Board Fabrication**: All prototypes were milled and laser-etched in-house using the HIVE’s LPKF Protomat and Protolaser equipment.
- **Inspection**: Due to tooling artifacts, each board required **intense microscope inspection** to manually remove stray micron-level copper bridges using an X-Acto knife and fine probes.
- **Reliability**: The final revision performed successfully in flight, powering the payload and handling cutdown operations as designed.

## Additional Info

The board connects directly to an Adafruit Feather M0 RFM9x and routes power, sensors (MS8607), and nichrome cutdown lines through onboard circuitry. It is designed for compact, modular integration into the balloon payload stack.
