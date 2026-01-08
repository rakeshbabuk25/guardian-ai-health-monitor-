# Guardian AI Health Monitor

## Project Overview
This repository contains the **fully annotated source code** for the academic project:

**“An AI-Powered Health Monitoring System Using ESP32-S3 and TinyML”**

The project implements a **multi-modal AIoT health monitoring system** that performs real-time biometric analysis at the edge using TinyML and provides secure cloud-based visualization for remote monitoring.

The system is designed to demonstrate the **practical feasibility of deploying AI models on resource-constrained microcontrollers** while addressing latency, privacy, and ethical considerations in healthcare applications.

---

## System Features
- Real-time heart rate monitoring and classification
- Voice stress detection using TinyML (MFCC + CNN)
- Fatigue detection via blink-rate analysis
- Edge-based inference using ESP32-S3
- Secure cloud integration using ThingSpeak (HTTPS)
- Multi-modal alert fusion and health state classification

---

## Hardware Components
- ESP32-S3 Microcontroller
- MAX30102 Pulse Oximeter (Heart Rate)
- INMP441 MEMS Microphone (Voice Stress)
- ESP32-CAM (Fatigue / Blink Detection)
- Li-Po Battery (2500 mAh)

---

## Software & Tools
- Arduino IDE 2.x
- ESP32 Board Support Package
- TensorFlow Lite for Microcontrollers
- Edge Impulse / TensorFlow (Model Training)
- ThingSpeak Cloud Platform
- Git for version control

---

## Repository Structure
guardian-ai-health-monitor/
│
├── src/ # Main application source code
├── models/ # Quantized TinyML models (.tflite / headers)
├── include/ # Model and sensor headers
├── docs/ # System diagrams and documentation (if any)
├── README.md # Project documentation
└── LICENSE (optional)




---

## Code Documentation
- All source files are **fully annotated with in-line comments**
- Code comments explain:
  - Sensor integration
  - Data preprocessing
  - TinyML inference pipeline
  - Alert generation logic
  - Cloud communication

⚠️ **Note:**  
In accordance with assessment guidelines, **line-by-line code analysis is intentionally excluded from the written report**.  
This repository is provided to support transparency, reproducibility, and technical verification.

---

## Academic Context
This repository supports the coursework submission for an MSc programme in Artificial Intelligence.

- The implementation reflects the system described in the accompanying report.
- All design decisions, experiments, and evaluations are discussed in the report.
- AI tools were used only for language refinement and not for code generation.

---

## Author
**Rakesh**  
MSc Artificial Intelligence  
Northumbria University

---

## License
This project is provided for **academic and educational purposes only**.
