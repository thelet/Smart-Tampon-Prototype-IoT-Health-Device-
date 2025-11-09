# 💡 Smart Tampon Prototype — IoT Health Device

This repository documents the **Sense Smart Tampon** project —  
an IoT-based health device developed as part of **Ariel University’s Entrepreneurship Accelerator**,  
where it earned **1st place** for innovation and technical feasibility.

The project explores how connected sensing technology can detect tampon saturation in real time  
using simple, low-cost materials and wireless data transmission.

---

## 📘 Overview

The goal was to build and test a **proof-of-concept** capable of measuring fluid absorption  
through electrical properties of the tampon (capacitance and resistance),  
and to demonstrate how these signals could be streamed to a mobile interface.

Development progressed through multiple **POCs (Proofs of Concept)**:

| POC | Focus | Key Outcome |
|-----|--------|-------------|
| **POC #0 Lab Validation** | Synthetic fluid test | Verified measurable response up to ~50 pF at full saturation:contentReference[oaicite:4]{index=4} |
| **POC #1** | Capacitance-based sensing | Confirmed that capacitance increases with fluid absorption:contentReference[oaicite:3]{index=3} |
| **POC #2** | Resistance sensing + BLE | Achieved live wireless readings via Arduino Nano 33 BLE Sense Rev 2:contentReference[oaicite:5]{index=5} |

---

## 🧩 Prototype Summary

- **Sensor type:** Conductive zinc or foil electrodes integrated into a tampon analog  
- **Microcontroller:** Arduino Nano 33 BLE Sense Rev 2 (Bluetooth Low Energy)  
- **Measurement method:** Resistance-based voltage divider (POC #2), capacitance-based timing (POC #1)  
- **Testing medium:** Saline “synthetic blood” solution prepared to simulate physiological conductivity  
- **Data visualization:** Custom prototype mobile app displaying live fill-level readings    

---

## 🧪 Files Included

| File | Description |
|------|--------------|
| **prototype/** | Technical documentation of POC stages and lab validation experiments |
| **showcase/** | Pitch deck, presentation materials, and prototype photos/videos |

## 🧪 Key Documents

| File | Description |
|------|--------------|
| **Capacitive Sensor – Preliminary Lab Validation.pdf** | Laboratory validation confirming capacitance correlation with fluid absorption. |
| **First POC – Arduino.pdf** | Early proof-of-concept measuring tampon capacitance and mapping saturation levels. |
| **2nd POC – BLE.pdf** | Upgraded prototype using resistance sensing and BLE for real-time data streaming. |
| **Investor_Pitch_Deck.pdf** | Presentation used during the accelerator and investor pitch. Summarizes concept, market potential, and technical milestones. |

---


## 💬 About This Repository

This repository focuses on sharing the **concept, experiments, and workflow** behind the prototype,  
rather than publishing the full production code or app design.  
All included documents are internal working materials used by the team to record experiments,  
exchange ideas, and communicate progress during development.

---


## 🏁 Summary

This project demonstrates a complete early-stage development cycle —  
from concept validation and lab testing to live wireless prototyping —  
showing how IoT and simple sensor design can improve menstrual health technology.
