# Communication Protocol Overview

This document describes the communication protocol used between AURORAE boards and optionally between the system and a host device.

---

## 1. Communication Type

- Wired (I2C, UART, SPI)  
- Optional BLE  

---

## 2. Message Structure

- Header  
- Payload  
- Checksum  
- Message types (sensor event, lighting update, sync, etc.)  

---

## 3. Timing

- Update frequency  
- Latency targets  
- Retry logic  

---

## 4. Error Handling

- Lost packets  
- Corrupted data  
- Out‑of‑sync boards  

---

## Acceptance Criteria

- Document stored in `/docs/communication/`  
- File name: `communication_protocol.md`  
- Includes packet diagrams  
- Linked from README  
