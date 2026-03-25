# Satellite Constellation & Mission Modeling

**Context:** e-bliss LLC  
**Stack:** C++, e-physics engine  
**Focus:** Orbital Simulation, Systems Modeling  

---

## Overview

Developed a simulation system for modeling satellite constellations and mission scenarios, including orbital propagation, inter-satellite communication, and ground station coverage.

Built on top of the e-physics engine, this system enabled analysis of mission feasibility and communication performance.

---

## Problem

- Needed to model interactions between large numbers of satellites  
- Communication depended on line-of-sight constraints and orbital dynamics  
- Required evaluation of coverage over time and geography  
- Needed flexibility to test different constellation configurations  

---

## Solution

Implemented a constellation modeling layer on top of the core simulation engine:

- Orbital propagation for each satellite  
- Line-of-sight (LOS) calculations between entities  
- Communication link modeling (satellite ↔ satellite, satellite ↔ ground)  
- Scenario-based configuration for mission setups  

---

## Key Features

- Multi-satellite constellation simulation  
- Time-evolving orbital state tracking  
- LOS-constrained communication modeling  
- Ground station coverage analysis  

---

## Technical Details

- Spatial queries for LOS and occlusion checks  
- Efficient pairwise evaluation between entities  
- Time-stepped simulation of dynamic systems  
- Configurable scenario parameters for rapid iteration  

---

## Results / Impact

- Enabled evaluation of communication coverage and mission viability  
- Supported rapid iteration on constellation design  
- Provided actionable insights for satellite mission planning  

---

## Visuals

TBA
