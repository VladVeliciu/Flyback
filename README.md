# Flyback Dual-Output Isolated Power Supply

This repository documents the design of a **dual-output, galvanically isolated AC–DC flyback power supply**, developed as an academic engineering project.  
The focus of the project is on **power electronics design methodology**, analytical calculations, simulation-based validation, and PCB layout implementation.

The repository is intended for **educational and portfolio purposes**, showcasing the complete engineering workflow rather than providing manufacturing-ready files.

---

## Project Overview

**Topology:** Flyback converter  
**Controller:** UC3844 (current-mode control)  
**Input voltage range:** 85–265 VAC, 50–60 Hz  
**Outputs:**
- **3.3 V DC** (main regulated output)
- **8 V DC** (secondary isolated output)
- Auxiliary supply for control circuitry

**Key features:**
- Galvanic isolation between input and outputs
- Current-mode control with optocoupler feedback
- Hiccup-mode overcurrent protection
- Designed snubber network and current sensing
- Multi-layer PCB with isolation slots and EMI-aware layout

---

## Design Scope

The project covers:

- Specification definition and requirement analysis  
- Analytical design of the flyback converter  
- Transformer design (turns ratio, core selection, losses)  
- Power semiconductor and passive component selection  
- Control loop and compensation design  
- PSIM simulations and performance validation  
- PCB layout implementation (4-layer stack-up)  
- Assembly drawings and bill of materials (BOM)

Simulation results include:
- Startup behavior
- Output voltage ripple
- Load transients
- Short-circuit and overload response
- Hold-up time verification

---

## Repository Contents

| File | Description |
|-----|------------|
| `Flyback.pdf` | Complete design report (calculations, simulations, explanations) |
| `Schematic Prints.PDF` | Electrical schematics |
| `Layers.PDF` | PCB copper layers overview |
| `Assembly Drawings.PDF` | Assembly and placement drawings |
| `PDF3D.PDF` | 3D visualization of the PCB |
| `Bill of Materials.xlsx` | Component list with manufacturers and quantities |

---

## Important Notes & Disclaimer

- **Manufacturing files (Gerbers, pick-and-place, stencil files) are intentionally not included.**
- **Native design files (Altium, PSIM projects) are intentionally not included.**

This project:
- has **not undergone full safety, EMI, or regulatory compliance testing**
- is **not intended for direct manufacturing or commercial deployment**
- is shared **strictly for educational and demonstration purposes**

Anyone intending to reproduce or extend the design must perform their own validation, safety analysis, and compliance testing.

---

## Learning Objectives

This project demonstrates:
- Practical offline SMPS design
- Power electronics analysis and verification
- Isolation, creepage, and clearance considerations
- EMI-aware PCB layout techniques
- Professional engineering documentation practices

---
