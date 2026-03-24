# Satellite Mission Simulation Engine

**Context:** e-bliss LLC  
**Stack:** C++, Godot  
**Focus:** Orbital Mechanics, Simulation  

---

## Overview

Developed a modular simulation engine for modeling satellite missions, including orbital propagation, inter-satellite communication, and ground station visibility.

The system was designed to support rapid scenario evaluation and mission planning through both simulation and visualization tools.

---

## Problem

- Needed accurate orbital modeling without excessive computational cost
- Required integration of multiple domains (orbital mechanics + communications)
- Scenarios needed to be configurable and visualizable by users
- Existing tools were either too rigid or too complex for rapid iteration

---

## Solution

Built a modular C++ simulation core with:

- Orbital propagation system
- Satellite-to-satellite and satellite-to-ground communication modeling
- Line-of-sight and occlusion calculations
- Scenario configuration layer

Integrated with a Godot-based visualization tool for:
- real-time inspection  
- scenario setup  
- debugging  

---

## Key Features

- Multi-satellite constellation simulation
- Line-of-sight constrained communication modeling
- Ground station coverage analysis
- Interactive visualization and scenario editing

---

## Technical Details

- Keplerian propagation with configurable update steps
- Spatial queries for LOS and occlusion checks
- Decoupled simulation and visualization layers
- Data-driven configuration system for mission scenarios

---

## Results / Impact

- Enabled rapid evaluation of satellite communication coverage
- Provided interactive tools for mission planning
- Reduced iteration time for scenario testing

---

## Visuals

- TBA
