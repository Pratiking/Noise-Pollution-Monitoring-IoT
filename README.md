# 🔊 Noise Pollution Monitoring System (IoT)

An IoT-based system designed to monitor environmental noise levels in real time using an ESP32 microcontroller and KY-037 sound sensor. The system visualizes noise levels on a Node-RED dashboard and sends alerts via the Blynk mobile application using the MQTT communication protocol.

---

## 📌 Project Overview

Noise pollution is a major environmental concern in urban areas. This project measures surrounding sound intensity and provides real-time monitoring through a web dashboard and smartphone interface.

---

## 🎯 Features

✅ Real-time noise level monitoring
✅ Node-RED web dashboard visualization
✅ Blynk mobile app monitoring & alerts
✅ MQTT-based real-time data communication
✅ Adjustable sensitivity using KY-037 sensor
✅ Live data updates over Wi-Fi

---

## 🛠 Hardware Components

* ESP32 (NodeMCU)
* KY-037 Sound Sensor Module
* Jumper wires
* Power supply

---

## 💻 Software & Tools Used

* Arduino IDE
* Node-RED
* MQTT Protocol
* Blynk IoT Platform
* Wi-Fi Network

---

## 🌐 Communication Protocol

This system uses the **MQTT (Message Queuing Telemetry Transport)** protocol to transmit real-time noise data from the ESP32 to Node-RED dashboards and cloud services. MQTT is lightweight, fast, and ideal for IoT applications requiring reliable real-time communication.

---

## 🔌 Circuit Connections

| KY-037 Pin    | ESP32 Pin |
| ------------- | --------- |
| VCC           | 3.3V      |
| GND           | GND       |
| AO            | GPIO 34   |
| DO (optional) | GPIO 26   |

---

## ⚙️ Working Principle

1. The KY-037 sound sensor detects sound intensity from the surroundings.
2. ESP32 reads analog values from the sensor.
3. ESP32 publishes noise data using MQTT over Wi-Fi.
4. Node-RED subscribes to the MQTT data and displays live noise levels on a dashboard.
5. Blynk app provides remote monitoring and alerts.

---

## 📊 Applications

* Smart city noise monitoring
* Traffic & industrial noise analysis
* Hospitals & school silent zones
* Residential noise tracking

---

## 🚀 Future Improvements

* Add cloud data storage & analytics
* AI-based noise classification
* Accurate decibel (dB) calibration
* Automatic noise threshold alerts

---

## 📷 Circuit Diagram

![Circuit Diagram](https://github.com/user-attachments/assets/0d71fa8a-6b64-4a73-9f0b-9a5e9eeb2e07)

---

## ⭐ License

This project is licensed under the MIT License.
