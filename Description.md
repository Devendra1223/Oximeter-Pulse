# Oxy-Vital AQI Monitoring System 🚨🩺

This repository contains the source code and documentation for the **Oxy-Vital AQI Monitoring System**, a mini project developed as part of the B.Tech curriculum in Electronics Engineering by Devendra Srivastava and team.

## 📌 Project Overview

The **Oxy-Vital System** is a real-time health and environmental monitoring system designed to measure:
- **SpO₂ (Oxygen Saturation)**
- **Heart Rate**
- **Air Quality Index (AQI)**

These parameters are monitored using **MAX30100** (for SpO₂ and heart rate) and **MQ-135** (for air quality), interfaced with an **ESP32 microcontroller**. The processed data is displayed on a **0.96-inch OLED screen**, and appropriate alerts are triggered when values go beyond safe thresholds.

## 🧠 Key Features

- **Real-Time Health Monitoring**: Tracks oxygen saturation and pulse rate using the MAX30100 sensor.
- **Air Quality Detection**: Monitors ambient air quality via the MQ-135 gas sensor.
- **OLED-Based Display Interface**: Provides clean, readable output on a compact OLED screen.
- **Environmental Alerts**: Notifies users when AQI or health parameters exceed healthy limits.
- **Simulated Testing**: Tested in a simulated environment, ideal for educational and prototyping purposes.
- **Battery Management**: Integrates PWM to prevent overcharging during power storage.

## 🛠️ Technologies & Components Used

- **Microcontroller**: ESP32
- **Sensors**: 
  - MAX30100 – Pulse Oximeter and Heart Rate Sensor
  - MQ-135 – Air Quality Sensor
- **Display**: OLED 128x64 I²C Display
- **Software**: 
  - Arduino IDE for programming
  - Embedded C/C++
- **Prototyping Tools**: Breadboard, jumper wires, resistors

## 📈 Outcome

The system provides an efficient, low-cost, real-time health and environmental monitoring solution. It's particularly relevant for:
- Personal health tracking in polluted environments
- Smart agriculture
- Educational demonstrations for IoT-based healthcare

## 👨‍💻 Developed By

- **Devendra Srivastava**  


Under the guidance of **Mr. B.R. Singh**, Assistant Professor  
Department of Electronics Engineering  
Dr. Ambedkar Institute of Technology for Divyangjan, Kanpur

---
 
