# FLASH DRIVE PCB DESIGN

## Overview
This repository contains the complete **PCB design and hardware documentation** for a custom **USB Flash Drive** developed using **Altium Designer**.  
The project focuses on understanding real-world hardware design workflows, signal integrity, component selection, and manufacturability for consumer electronics.

This is not a tutorial build — it is a **practical engineering project** aimed at developing industry-relevant PCB design skills.

---

## Project Objectives
- Design a functional USB flash drive from schematic to PCB
- Apply proper USB signal routing practices
- Learn component selection for memory, power regulation, and interfaces
- Prepare the design for real manufacturing (DFM & DRC compliant)
- Build a reusable PCB design portfolio for future hardware products

---

## Design Scope
- USB interface (Full-Speed / High-Speed depending on configuration)
- Flash memory integration
- Power regulation via USB VBUS
- ESD and basic protection circuitry
- Compact PCB form factor suitable for enclosure

---

## Tools & Software
- **Altium Designer** (Schematic & PCB layout)
- Version control via **Git & GitHub**
- Standard PCB manufacturing outputs (Gerbers, Drill files, BOM)

---

## Repository Structure

FLASH_DRIVE/
│── Schematic/ # Circuit schematics
│── PCB/ # PCB layout files
│── Libraries/ # Custom symbols and footprints (if any)
│── Outputs/ # Gerber files, drill files, fabrication outputs
│── Docs/ # Design notes and references
│── README.md


---

## Current Status
- [x] Concept definition
- [x] Schematic design
- [x] PCB layout
- [ ] Design review and optimization
- [ ] Final manufacturing checks
- [ ] Physical fabrication and testing

(Status will be updated as the project progresses.)

---

## Engineering Notes
- Design decisions prioritize **simplicity, reliability, and manufacturability**
- PCB routing follows USB differential pair guidelines
- The project may evolve with revisions as testing feedback is obtained

---

## Intended Use
This repository is intended for:
- Hardware engineering portfolio
- Learning and experimentation
- Reference for future embedded and consumer electronics projects

It is **not** a production-ready commercial design (yet).

---

## Author
**Ayafor Bill**  
Electrical & Electronics Engineering | Hardware & Systems Design  
Focused on building scalable technology solutions in telecommunications and electronics.

---

## License
This project is provided for educational and portfolio purposes.  
Reuse with attribution is encouraged. Commercial use requires permission.
