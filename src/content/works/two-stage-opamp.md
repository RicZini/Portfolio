---
title: Two-Stage CMOS OpAmp Design
description: Transistor-level design, sizing, and SPICE optimization of a two-stage CMOS Op-Amp with various constraints from the specsheet.
publishDate: 2026-08-20
tech: ['CMOS IC Design', 'Analog Electronics', 'SPICE', 'Transistor Sizing']
thumbnail: ./cover-twostage.png
---
<br>

<a href="/Riccardo-Zini-Portfolio/PCSA_Twostage.pdf" target="_blank" class="button">Download Full Datasheet (English)</a>

# Brief
Designed individually as part of my Master's coursework in Analog Circuit Design at UniBo, this project served as my introduction to transistor-level integrated circuit (IC) design. Starting from strict electrical specifications, I designed a two-stage CMOS operational amplifier architecture featuring a differential input pair with an active load, a common-source output stage, Miller frequency compensation, and an onboard bias network.

# Design and Simulations
Working entirely at the device level, I carried out initial theoretical hand calculations to determine quiescent operating points, transistor aspect ratios (W/L), and compensation components (Capacitance and zero-nulling MOSFET). To ensure real-world foundry compatibility, all device dimensions were quantized to a 50 nm manufacturing grid. Using SPICE simulations, I iteratively tuned the circuit—rebalancing current mirrors to expand output swing, scaling transistor areas, and tuning zero positioning to guarantee a stable phase margin of 65.2°.

# Final Results
The final circuit achieved a 106dB DC gain and a 7MHz bandwidth while keeping total power consumption down to 479.5uA. Tackling this project independently was a key milestone for me: it confirmed my strong interest in analog microelectronics and IC design, bridging theoretical device physics with practical transistor-level simulation and stability analysis.