---
title: Sensor Acquisition PCB
description: Remote CAN acquisition module designed to mitigate EMI on sensor lines and deliver real-time shutdown circuit fault location and current tracking.
publishDate: 2026-10-10
tech: ['Altium Designer', 'CAN Bus', 'PCB', 'Analog Electronics']
thumbnail: ./cover-acquisition.png
---

# Sensors
Developed for UniBo Motorsport in collaboration with two experienced team alumni, this custom PCB was engineered to optimize low-voltage sensor routing across the vehicle. By sampling analog sensor signals locally at the front end rather than routing long wires across the chassis, we eliminated major Electromagnetic Interference (EMI) coupling paths. The acquired data is digitized on-board and broadcast directly to the central ECU via the CAN network.

# OC Detection
A critical feature of the board is its dedicated diagnostic system for the vehicle's shutdown circuit: a high-voltage safety loop composed of multiple safety nodes connected in series. To streamline trackside troubleshooting, I helped design a discrete sensing circuit capable of identifying both the exact location and precise timestamp of a loop open event whenever a safety node trips.

# Current Sensing
Additionally, the board measures the continuous current flowing through the shutdown loop. This current-sensing capability provides vital real-time diagnostic data to detect contactor degradation, intermittent wire faults, and voltage drops before a complete safety shutdown occurs.