# IoT-Based Fertigation Mobile Robot 🌱

An IoT-based mobile robot designed to automate irrigation and fertilization for ornamental plants. The system monitors soil moisture levels, navigates between designated plant locations, and automatically distributes water and fertilizer when needed.

## 🎥 Demo Video
[Watch Project Demo](https://youtu.be/CLQZPACBSuk)

## 🚀 Features
- **Automatic Navigation:** Uses an IR sensor to detect designated plant locations.
- **Soil Moisture Monitoring:** Measures moisture levels using four soil moisture sensors.
- **Automatic Fertigation:** Activates water pumps when soil moisture falls below 30%.
- **IoT Monitoring:** Displays real-time soil moisture readings through a Node-RED dashboard.
- **Wireless Communication:** Uses ESP-NOW to exchange data between ESP32 boards.

## 🛠️ Technologies & Components
- ESP32 Microcontroller (3 units)
- Soil Moisture Sensors (4 units)
- IR Sensor
- L293N Motor Driver
- 12V DC Motors
- 12V Water Pumps
- Relay Module
- Node-RED
- ESP-NOW Communication

## ⚙️ How It Works
1. Soil moisture sensors collect data from four plants.
2. ESP32 transmits the readings wirelessly using ESP-NOW.
3. The robot starts moving after the push button is pressed.
4. The IR sensor detects black markers and stops the robot at designated locations.
5. If soil moisture is below 30%, the corresponding water pump activates for 5 seconds.
6. The robot continues to the next location until the process is completed.

## 👨‍💻 Project Team
- Mazen Mohamed Mahrous Abdelaziz
- Ali Hayder Kamil Fadhl
- Chow Chan Hoe

**Supervisor:** Dr. Fazilah Binti Hassan

**Institution:** Universiti Teknologi Malaysia (UTM)

---

*Capstone Project 2024/2025 — Awarded a Theme Award in the CMED field at EECS 2025.*
