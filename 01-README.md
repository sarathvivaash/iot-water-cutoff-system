# iot-water-cutoff-system
IoT-based Smart Water Cutoff and Monitoring System using ESP32, LoRa, Ultrasonic Sensors, and OLED Display
An IoT-based system that automates **water tank monitoring** and **motor control** using **ESP32**, **ultrasonic sensors**, and **LoRa communication**.  
It prevents overflow, detects dry runs, and enables **real-time monitoring and analytics** via a **Flutter mobile app** connected to a **Flask backend**.

---

## ⚙️ System Overview
**Modules:**
- **Tank Module** – Measures water level using HC-SR04 and sends data via LoRa.  
- **Main Module** – Receives data and controls motor using relay.  

**Communication:** LoRa RF / Wi-Fi / Bluetooth  
**App:** Flutter mobile app for live control and data visualization.

---

## 🧠 Core Features
- Automatic motor ON/OFF control  
- Dry-run detection and prevention  
- Real-time data updates on mobile app  
- Data logging and analytics  
- Power-efficient modular design  

---

## 🪛 Hardware Used
- 2 × ESP32 Microcontrollers  
- 2 × LoRa Modules  
- HC-SR04 Ultrasonic Sensor  
- Relay Module  
- Boost Converter (3.7V → 5V)
- Flask Server + Flutter App  
