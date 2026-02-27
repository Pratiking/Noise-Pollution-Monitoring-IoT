# Noise-Pollution-Monitoring-IoT
An IoT-based system designed to monitor environmental noise levels in real time using an ESP32 microcontroller and KY-037 sound sensor. The system visualizes noise levels on a Node-RED dashboard and sends alerts via the Blynk mobile application.

---

## 📌 Project Overview

Noise pollution is a major environmental concern in urban areas. This project measures surrounding noise intensity and provides real-time monitoring through a web dashboard and smartphone interface.

---

## 🎯 Features

✅ Real-time noise level monitoring
✅ Node-RED web dashboard visualization
✅ Blynk mobile app monitoring & alerts
✅ Adjustable sensitivity using KY-037 sensor
✅ Live data updates over Wi-Fi

---

## 🛠 Hardware Components

* ESP32 (NodeMCU)
* KY-037 Sound Sensor Module
* Breadboard
* Jumper wires
* Power supply

---

## 💻 Software & Tools Used

* Arduino IDE
* Node-RED
* Blynk IoT Platform
* Wi-Fi Network

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
3. Data is transmitted over Wi-Fi.
4. Node-RED displays live noise levels on a web dashboard.
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


---


## 📷 Project Preview

<img width="690" height="624" alt="Circuit diagram IOE" src="https://github.com/user-attachments/assets/0d71fa8a-6b64-4a73-9f0b-9a5e9eeb2e07" />







## ⭐ License

This project is licensed under the MIT License.
