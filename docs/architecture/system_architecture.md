# AURORAE System Architecture Overview

This document provides a high‑level overview of the AURORAE system, describing how modular boards, sensors, lighting, communication, and firmware interact. It serves as the foundation for firmware, hardware, and interaction design.

---

![AURORAE System Architecture](diagrams/aurorae_system_architecture.png)

---

## 1. System Components

- Modular board units  
- Microcontroller (MCU)  
- Lighting subsystem (LEDs, drivers)  
- Sensor subsystem (touch, proximity, motion, etc.)  
- Communication subsystem (wired or BLE)  
- Power subsystem  
- Game logic engine  

---

## 2. Data Flow

Full pipeline description:

- Sensor input → MCU processing  
- Lighting control updates  
- Game logic state transitions  
- Board‑to‑board communication  
- Optional BLE communication to host device  

---

## 3. Firmware Architecture

- Sensor polling loop  
- Lighting control module  
- Game logic engine  
- Communication protocol handler  
- Power management  

---

## 4. Hardware Architecture

- Modular connector layout  
- Power distribution  
- LED driver placement  
- Sensor placement  
- MCU + peripheral routing  

---

## 5. Interaction Design Integration

- How lighting + sensors create gameplay  
- Timing considerations  
- Multi‑board synchronization  

---

## Acceptance Criteria

- Document stored in `/docs/architecture/`  
- File name: `system_architecture.md`  
- Diagram exported as PNG or SVG 
- Linked from README  
