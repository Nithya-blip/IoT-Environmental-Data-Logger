# IoT-Based Environmental Data Logger 🌍

## 📌 Overview
This project is an ESP32-based IoT system that collects environmental data such as temperature and humidity and demonstrates real-time monitoring. The system is designed to send data to a cloud platform using MQTT protocol.

> Note: Cloud integration (AWS IoT Core) is planned and will be added in future updates.

---

## 🚀 Features
- Real-time environmental data monitoring
- ESP32-based embedded system
- Scalable cloud integration (planned)
- Lightweight and low-power design

---

## 🛠️ Tech Stack
- ESP32
- Embedded C (Arduino IDE)
- MQTT Protocol (Conceptual)
- IoT Architecture

---

## 📷 Project Images

### Hardware Setup
![Setup](docs/images/hardware_setup.jpg)

### Circuit
![Circuit](docs/images/circuit.jpg)

### Output
![Output](docs/images/output.jpg)

---

## 🎥 Demo Video
[Watch Demo](docs/demo_video_link.md)

---

## ⚙️ Working
The ESP32 collects environmental data using sensors and processes it in real time.  
The system is designed to transmit this data to a cloud platform using MQTT protocol for remote monitoring.

---

## ☁️ Cloud Integration (Planned)
- AWS IoT Core
- MQTT Broker communication
- Real-time dashboard visualization

---

## 📊 Sample Output
```json
{
  "temperature": 28.5,
  "humidity": 65
}
