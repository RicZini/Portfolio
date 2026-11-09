---
title: Analog Filter Design
description: Design, Monte Carlo sensitivity analysis, and bench testing of a 40 kHz active low-pass filter for analog signal conditioning.
publishDate: 2026-6-15
tech: ['Analog Design', 'Op-Amps', 'Monte Carlo Analysis', 'Bench Testing']
thumbnail: ./cover-filter.png
---
<br>

<a href="/Riccardo-Zini-Portfolio/LTGL-LP40-BB_Datasheet.pdf" target="_blank" class="button">Download Full Datasheet (English)</a>

# Brief
This project served as my first hands-on introduction to analog circuit design and laboratory testing, developed as a collaborative team effort with two fellow engineering students. We split the workload equally across theoretical calculations, simulation, and physical testing, holding regular update meetings to align on design choices and component selection. Our goal was to build a 7th-order active Butterworth low-pass filter with a 40 kHz cutoff frequency and a DC gain of 5.

# Design and Simulaitons
To achieve the required 7th-order frequency response, we cascaded multiple Op-Amps stages using LM741 and TL084 ICs in Sallen-Key and Tow-Thomas configurations. Before going to the lab, we modeled the circuit in MATLAB and ran Monte Carlo simulations to make sure component tolerances wouldn't degrade performance. We then built the prototype on a breadboard and tested it using a function generator, oscilloscope, and DC power supply, verifying that our physical measurements matched expected Bode plots.

# Applications
Designed as a general-purpose Analog Front-End (AFE) block, the filter is suited for ADC anti-aliasing, sensor signal conditioning, vibrational analysis, and speed sensor signal processing. Beyond the hardware results, the project was an ideal entry point into real-world analog engineering, bridging the gap between textbook theory, team collaboration, and physical lab measurements.