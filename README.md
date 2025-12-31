# 🔧 AI-Powered Predictive Maintenance System

An AI-powered predictive maintenance system designed to monitor machine health in real time using IoT sensors, edge computing, and machine learning techniques.  
The system predicts potential failures before breakdowns occur, enabling data-driven and cost-effective maintenance decisions.

---

## 📌 Project Overview

Traditional maintenance strategies are reactive or schedule-based, often leading to unnecessary downtime and increased costs.  
This project introduces an **AI-powered Predictive Maintenance System** that continuously monitors machines and detects early signs of failure using multi-sensor data.

The system integrates **vibration, current, temperature, and acoustic signals** to assess machine health and generate timely alerts.

---

## 🎯 Objectives

- Monitor machine health in real time using IoT sensors  
- Detect anomalies and early fault conditions  
- Reduce unplanned downtime  
- Optimize maintenance schedules  
- Improve operational safety and reliability  
- Enable edge-based intelligent decision-making  

---

## 🧠 System Architecture

- **IoT Sensors** collect vibration, current, temperature, and sound data  
- **ESP32 (Edge Device)** performs data acquisition and preprocessing  
- **Anomaly Detection & ML Models** analyze sensor patterns  
- **Alerts System** triggers warnings via LED/Buzzer  
- **Data Logging** ensures traceability and historical analysis  

---

## ⚙️ Hardware Components

- ESP32 Development Board  
- ADXL345 Accelerometer (Vibration Monitoring)  
- ACS712 Current Sensor  
- MAX9814 Microphone Module (Acoustic Monitoring)  
- ADS1115 High-Resolution ADC  
- DS3231 RTC (Time Synchronization)  
- DHT11 / DHT22 Temperature Sensor  
- Micro SD Card Module  
- LEDs and Buzzer  
- DC Motor (Test Machine)  

---

## 💻 Software & Tools

- Arduino IDE  
- Embedded C / C++  
- Machine Learning (Anomaly Detection)  
- Edge Computing Techniques  
- EasyEDA (Circuit Design)  

---

## 🔬 Methodology

1. Sensor data acquisition from multiple sources  
2. Signal conditioning and analog-to-digital conversion  
3. Feature extraction (RMS, peaks, frequency components)  
4. Anomaly detection and fault classification  
5. Alert generation and data logging  
6. Visualization and maintenance insights  

---

## 📊 Results & Performance

| Parameter | Result |
|---------|--------|
| Fault Detection Accuracy | 93.4% |
| Response Time | 180 ms |
| False Positive Rate | 4.1% |
| Data Logging Reliability | 99.2% |
| TinyML Inference Time | 35 ms |

The system successfully distinguishes between **Normal**, **Warning**, and **Fault** states under varying machine conditions.

---

## 📈 Applications

- Industrial motors and machinery  
- Smart factories (Industry 4.0)  
- Condition monitoring systems  
- Preventive & predictive maintenance platforms  

---

## 🚀 Future Scope

- Remaining Useful Life (RUL) prediction  
- Cloud-based dashboards and analytics  
- Advanced deep learning models  
- Wireless protocols (LoRaWAN / 5G)  
- Fully autonomous maintenance scheduling  

---

## 📄 Documentation

- 📘 Detailed documentation available in the `docs/` folder  
- 📑 Research paper included in the `research/` folder  
- 📊 Presentation available in the `presentation/` folder  

---

## 🤝 Acknowledgment

This project was developed under the guidance of faculty at **Vishwakarma Institute of Technology, Pune**.  
Special thanks to mentors and peers for their continuous support and technical guidance.

---

## 📬 Feedback

Feedback, suggestions, and discussions are welcome.
