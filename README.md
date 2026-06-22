# IoT-Based Real-Time Patient Vital Signs Monitoring System
A comprehensive healthcare IoT project developed as part of the RISE Internship. This system simulates a real-time patient monitoring device using free virtual software components and securely transmits medical data to a cloud analytics platform using industrial-grade protocols.

## 🚀 Project Features
- **Zero Component Setup:** 100% designed and tested using free virtual tools (Wokwi & ThingSpeak) with no hardware cost.
- **Advanced Networking:** Employs the lightweight **MQTT Protocol** via PubSubClient for instant data delivery.
- **Biomedical Simulation:** Real-time generation of critical human vitals including Heart Rate (BPM), SpO2 (%), and Body Temperature (°C).
- **Threshold Security:** Smart threshold logic triggers a local alert via a buzzer and flags critical states when vitals go out of normal bounds (Heart Rate > 120 BPM, Temp > 38.5°C).
- **Custom Visual Dashboard:** Built a customized hospital-style dark-theme visualization dashboard on ThingSpeak utilizing smooth spline curves.

## 🛠️ Technology Stack
- **Hardware Simulation:** ESP32 Microcontroller (Wokwi)
- **Programming Language:** Embedded C++ (Arduino Core)
- **Protocol:** MQTT (Message Queuing Telemetry Transport)
- **Cloud Infrastructure:** ThingSpeak IoT Analytics Server

## 🔗 Live Circuit Simulation
- Try the interactive virtual circuit here: https://wokwi.com/projects/467508590302174209
## 📊 Cloud IoT Dashboard
- View the live real-time patient health monitoring graphs here: https://thingspeak.mathworks.com/channels/3413678
