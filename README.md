# Modular Helical Vertical Axis Wind Turbine for Urban Wind
A low cost, modular, 3D printable helical vertical axis wind turbine designed for weak, turbulent, multidirectional urban wind.

This project focuses on consistency, scalability, and accessibility rather than peak efficiency. It is built to capture small amounts of energy from wind that is normally wasted in cities.
Read the fool build guide with pictures and results [here](https://www.instructables.com/Modular-Helical-Vertical-Axis-Wind-Turbine-for-Urb/).

## Overview
Traditional horizontal-axis wind turbines struggle in urban environments. City wind is:

- Low speed
- Highly turbulent
- Constantly changing direction
- Obstructed by buildings
- Large turbines also require space that cities rarely have.

This project explores an alternative approach, instead of optimizing for ideal conditions, this turbine is designed to:

- Accept wind from any direction
- Self-start at low wind speeds
- Smooth out gusty, inconsistent airflow
- Be cheap and easy to reproduce
- Scale vertically using stackable modules

## Core Design Concepts
**Helical Vertical-Axis Geometry**

The helical blade profile:
- Distributes aerodynamic forces along the turbine height
- Reduces torque ripple and vibration
- Ensures some portion of the turbine is always generating torque
  
This produces smoother, more reliable rotation in weak and chaotic wind, even if maximum RPM is lower.

## Mechanical Modularity

The turbine is built from repeatable vertical modules that share:
- Blade geometry
- Shaft diameter
- Threaded mounting interface
  
Modules can be stacked to increase height and swept area without redesigning the system. This makes the turbine:
- Scalable
- Easier to repair or modify
- Faster to iterate
- More filament-efficient
  
Vertical stacking is especially useful in cities where horizontal space is limited.

## Electrical Modularity
Each module can optionally be paired with its own generator and harvesting circuit.
Modules can be connected:
- In series to increase voltage
- In parallel to increase current
- As independent inputs to a shared storage system

This allows flexibility depending on storage, load, or experimental goals.

## Versions Included
### Version 1
- Narrower blades
- Taller modular stack
- Lower material usage

### Version 2
- Wider blades
- Fewer but larger modules
- Higher wind capture at the cost of size

### Version 3
- Balanced width and height
- Moderate footprint
- Good compromise between V1 and V2

All versions follow the same modular principles and assembly method.

## Files

This repository includes 3D model files organized into the following folders:

### v1/
Version 1 components:
- `vawtv1bottom.3mf` - Bottom section
- `vawtv1middle.3mf` - Middle module
- `vawtv1cap.3mf` - Top cap

### v2/
Version 2 components:
- `vawtv2bottom.3mf` - Bottom section
- `vawtv2top.3mf` - Top section

### v3/
Version 3 components:
- `vawtv3short.3mf` - Short module
- `vawtv3tall.3mf` - Tall module

### case/
Motor housing and case components:
- `motor+case.3mf` - Motor housing
- `casecover.3mf` - Case lid for sealing electronics

All models are provided as .3mf files.
