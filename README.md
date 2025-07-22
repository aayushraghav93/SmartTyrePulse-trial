# 🚛 SMART TYRE PULSE – Intelligent Tyre Monitoring System for Dumpers

A real-time tyre monitoring and predictive maintenance platform designed for mining industry vehicles, integrating IoT sensors and AI models to enhance safety, performance, and tyre lifespan.

---

## 🔍 Problem Statement (SIH 2024 - PS ID: 1557)

**Development of tyre maintenance and operation app, including fitment of IoT related hardware in Dumpers.**  
> _Theme:_ Smart Automation  _Payload Category:_ Hardware  
> _Team ID:_ 8712  _Team Name:_ GLADIATORS, KIET

---

## 🚀 Overview

Smart Tyre Pulse is a complete IIoT-based solution that monitors key tyre metrics (pressure, load, speed, and temperature) in real-time to:

- Prevent dangerous tyre failures
- Optimize tyre reallocation based on wear rate
- Enhance decision-making for procurement and manufacturing
- Predict tyre lifespan using AI models

---

## 🧠 Key Features

- **Real-Time Tyre Monitoring**  
  Collects pressure, temperature, speed, and load data via IoT sensors.

- **TKPH-Based Analytics**  
  Calculates TKPH (Tonne-Kilometres per Hour) to ensure tyres are used within safe operational limits.

- **AI-Powered Predictive Maintenance**  
  Predicts tyre lifespan using load, terrain, and wear data patterns.

- **Instant Alerts and Notifications**  
  Voice and cloud-based alerts for threshold breaches.

- **Tyre Reallocation Intelligence**  
  Suggests optimal reallocation to extend tyre usability.

---

## 🛠️ Technical Architecture

### 📦 Technologies Used

- **Hardware:**  
  IR Sensor LM393, Load Cell, Raspberry Pi, TPMS Sensor, BMP280, ESP8266, ESP32

- **Frontend & App:**  
  Flutter (Dart), Firebase

- **Backend & ML:**  
  Python, Django, TensorFlow, MQTT

- **Cloud Infrastructure:**  
  AWS IoT Core / Azure IoT Hub  
  AWS Lambda / Azure Functions  
  AWS S3 / Azure Blob Storage

- **Database:**  
  Firebase Realtime DB

---

## 📐 TKPH Formula

> **TKPH** = (Mean Load in Tonne) × (Average Work Shift Speed in km/h)  
An alert is generated when the value exceeds the safe operating threshold.

---

## ⚙️ System Flow

1. **Data Collection:** via tyre-mounted sensors.
2. **Cloud Sync:** Transmits to cloud in real-time using Wi-Fi modules.
3. **AI Processing:** Predicts wear rate and alerts potential failures.
4. **User Interface:** Mobile App displays tyre health and alerts.
5. **Reallocation Logic:** Suggests repositioning based on performance.

---

## ⚠️ Challenges & Mitigation

| Challenge | Strategy |
|----------|----------|
| Weak connectivity in mines | Satellite/local wireless fallback |
| High initial cost | Long-term ROI via efficiency gains |
| Inaccurate AI predictions | Expert loop validation + data improvement |

---

## 🎯 Impact

- **Mining Companies (e.g., CIL):** Reduced downtime, improved safety, optimized tyre usage.
- **Tyre Manufacturers:** Enables production of tyres with ideal TKPH profiles.
- **Maintenance Teams:** Eliminates manual inspection needs.
- **Procurement Officers:** Helps select tyres tailored to operational profiles.

---

## 🧠 AI + IoT for Smarter Tyre Management

> **Smart Tyre Pulse** transforms raw sensor data into actionable insights—paving the way for predictive maintenance and operational excellence in the mining industry.

---

## 👨‍💻 Team GLADIATORS | KIET Group of Institutions

> Developed under Smart India Hackathon 2024  
For queries or contributions, feel free to raise an issue or pull request in this repository.

---
