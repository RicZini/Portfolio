---
title: EV Control Unit
description: Real-time LabVIEW firmware development, state machine control, and TCP integration for autonomous driving on a Formula Student EV.
publishDate: 2025-08-10
tech: ['LabVIEW', 'Autonomous Driving', 'Git']
thumbnail:  ./labview-proj.png
---

## Brief
During my tenure with UniBo Motorsport, I managed the entire codebase for the central Electronic Control Unit (ECU) and maintained version control workflows via Git. I developed the core real-time LabVIEW firmware responsible for hardware abstraction, sensor data acquisition, and processing torque demand algorithms sent directly to the motor inverters.

## Autonomous Vehicle
As Technical Lead, I architected the complete software foundation required for autonomous driving integration. I designed deterministic finite state machines (FSM) to govern overall vehicle dynamics, system interlocks, and seamless mode transitions between manual and driverless operation.

## Driverless Actuations
To bridge low-level vehicle actuation with high-level autonomous processing, I implemented a custom TCP communication layer with the autonomous driving computer. This enabled real-time command processing and precise closed-loop actuation of the steering and braking sub-systems on the physical vehicle.