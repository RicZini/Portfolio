---
title: EV Fuse Board
description: Custom low-voltage high-current PCB designed in Altium Designer, featuring full BOM sourcing and a microcontroller-free R-2R DAC fuse monitoring system.
publishDate: 2026-05-01
tech: ['Altium Designer', 'PCB', 'Analog Electronics', 'BOM']
thumbnail: ./fuseboard.png
---

## Brief
Designed and developed a compact, high-density fuse distribution PCB using **Altium Designer** for low-voltage electric vehicle power architectures. Beyond schematic capture and layout, I took ownership of component selection, engineered the complete **Bill of Materials** (BOM), and managed component procurement. The board layout was optimized for thermal dissipation and precise copper trace sizing to safely handle continuous high-current power distribution.

## Analog Signal Acquisition
To monitor post-fuse health status without introducing unnecessary software complexity or microcontroller failure points, I architected a purely **analog signal acquisition system**. Using a discrete binary resistor DAC network, post-fuse states are encoded into multi-level analog voltage signals routed directly to a single VCU ADC channel.

## Manufacturing and Testing
The PCB was populated and stress-tested in-house. Physical testing confirmed 100% operational functionality for both high-current power delivery and discrete analog diagnostic logic, delivering robust fault detection with zero microcode overhead.