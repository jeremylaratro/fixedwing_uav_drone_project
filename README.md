# ASEP: The Autonomous Systems Engineering Project
> ASEPv0.0.1

## Overview
A 3D printed fixed-wing UAV (FWUAV). The ASEP FWUAV aims to provide a simple, reliable UAV system engineering process utilizing all open-source flight control and autopilot software.  

## Core Components
### Software
- Ardupilot: core autopilot and flight control software. 
### Hardware
- Pixhawk C6: core flight control hardware system.
- GPS M10: GPS module with antenna for location service.
- ELRS R3 receiver: core RX module.
### Communications
The Express Long Range System (ExpressLRS or ELRS) open radio protocol was chosen for the core communication and control stack.
### Sensors
The first revision of the ASEP FWUAV features a single video-capable camera along with an analog video transmission module. Additional sensors include

## Project Management
The ELRS protocol was chosen due to its open-source nature and ability to maintain operational status across extremely long ranges. 

![arch](https://github.com/jeremylaratro/fixedwing_uav_drone_project/blob/main/system_arch_l.png)
