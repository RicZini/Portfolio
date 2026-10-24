---
title: 4WD Electric Vehicle Slip Control
description: Development and real-time ECU implementation of a Sliding Mode Control (SMC) algorithm for longitudinal slip regulation. 
publishDate: 2025-10-06
thumbnail: ./visione.jpg
tech: 
- 'Matlab'
- 'SIMULINK'
- 'LabVIEW'
- 'Real-Time Control'

---

<br>

<a href="/Riccardo-Zini-Portfolio/Tesi_finale.pdf" target="_blank" class="button">Download Full Thesis (Italian)</a>

## Project Scope
Developed as my Bachelor's thesis, this project focused on optimizing traction and longitudinal stability for a four-wheel-drive electric vehicle with independent wheel motors. To accurately capture multi-wheel dynamic interactions, I developed a custom mathematical vehicle model from first principles rather than relying on pre-built abstractions.

## Modeling and Controls
To handle non-linear tire-road dynamics, I designed a **Sliding Mode Control (SMC)** algorithm engineered to maintain optimal longitudinal slip. The complete control pipeline was modeled and simulated in **MATLAB / Simulink**, then ported to **LabVIEW** for real-time execution on the vehicle's onboard Electronic Control Unit (ECU).

## Implementation and Validation
The algorithm was validated through on-track testing on a physical prototype. Telemetry data analysis enabled iterative tuning of the SMC gain parameters, successfully mitigating chattering effects and achieving robust slip convergence under dynamic acceleration.

