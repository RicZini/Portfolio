---
title: 32-Bit Minimum Latency Carry-Bypass Adder
description: Hierarchical post-layout design of a 32-bit Carry-Bypass Adder in UMC 65nm, simulated in Cadence Virtuoso with full parasitic extraction.
publishDate: 2026-11-04
tech: ['Cadence Virtuoso', 'UMC 65nm', 'Post-Layout Simulation', 'Timing Analysis']
thumbnail: ./cover-adder.png
---

# Brief
Designed a low-latency 32-bit Carry-Bypass Adder (CBA) utilizing the UMC 65nm CMOS technology. The architecture was built hierarchically: starting from custom logic gates to form an optimized 1-bit Full Adder (FA), I designed a 4-bit bypass stage utilizing a multiplexer to skip the ripple chain when propagation conditions are met. Eight of these 4-bit blocks were then cascaded to construct the complete 32-bit datapath.

# Estimations and Simulations
All design, simulation, and performance estimation phases were executed within **Cadence Virtuoso**. To guarantee silicon-accurate results, dynamic simulations were performed exclusively using the **config view**, fully accounting for the layout parasitic extraction (RC parasitics) of every individual standard cell. Delay models were extracted using Look-Up Tables (LUTs) parameterized by external load capacitance and input transition time. This granular post-layout data enabled a highly accurate critical path analysis to minimize worst-case propagation delays.

# Energy analysis
Beyond latency, I performed a comprehensive power analysis, calculating the switching energy consumed by every individual logic cell including parasitic effects. Finally, the arithmetic logic was evaluated in a synchronous environment using previously characterized CMOS registers. By mapping the post-layout critical path delays against strict setup and hold time constraints, I determined the absolute minimum clock period, maximizing the overall throughput while ensuring robust timing closure.