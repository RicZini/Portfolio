---
title: Inverter Integration and HV Testing
description: Integration of next-gen DTI motor inverters via CAN bus, high-voltage bench testing, and on-track EMI noise characterization.
publishDate: 2026-03-01
tech: ['CAN Bus', 'EMI/EMC', 'Power Electronics']
thumbnail: ./dti-inverters.png
---

## Brief
This project focused on integrating cutting-edge DTI motor inverters—newly introduced to the market—into the electric vehicle powertrain. I configured and implemented the CAN bus communication stack, developing deterministic message parsing to translate vehicle dynamics logic into precise torque demand commands.

## Testbench
To guarantee system reliability, I led high-voltage (HV) bench testing on the electric motors. This step was crucial to validate the power electronics integration, ensuring proper thermal handling, voltage limits, and isolation safety before deploying the powertrain onto the actual chassis.

## Track Tests
Finally, I conducted extensive track testing to characterize Electromagnetic Interference (EMI) produced by high-frequency inverter switching. I analyzed how noise emissions propagated across sensitive low-voltage sensor lines and CAN networks, identifying potential signal degradation paths to safeguard vehicle communication integrity.