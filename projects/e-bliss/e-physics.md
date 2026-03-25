# e-physics: Modular Simulation Engine

**Context:** e-bliss LLC  
**Stack:** C++  
**Focus:** Simulation Architecture, Physics Systems  

---

## Overview

Designed and implemented a modular C++ simulation engine for modeling physical systems, with an emphasis on flexibility, performance, and extensibility.

The engine serves as the core runtime for higher-level simulation applications, including orbital mechanics and satellite mission modeling.

---

## Problem

- Needed a flexible simulation framework adaptable to multiple domains  
- Existing tools were either too rigid or too domain-specific  
- Required support for both real-time visualization and batch simulation  
- Needed clean separation between simulation logic and presentation  

---

## Architecture

Built a modular system organized around:

- **Entity representation** (satellites, ground stations, etc.)  
- **Component-based simulation logic**  
- **Decoupled update systems** for physics, communication, and state  

Core principles:
- modularity  
- separation of concerns  
- data-driven configuration  

---

## Key Systems

- Physics update loop with configurable timestep  
- Object state propagation and tracking  
- Communication system hooks (LOS, signal modeling)  
- Event-driven updates for interactions between entities  

---

## Technical Details

- Deterministic-friendly update structure  
- Decoupled simulation and rendering layers  
- Lightweight data structures for scalability  
- Designed for both real-time and offline execution  

---

## Results / Impact

- Provided a reusable foundation for multiple simulation applications  
- Enabled rapid development of higher-level tools (e.g., orbital mission modeling)  
- Reduced complexity when extending simulation features  

---

## Visuals

TBA
