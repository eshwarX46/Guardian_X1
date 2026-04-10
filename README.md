# 🤖 Guardian X1 – Autonomous Patrolling & Security Robot

## 📌 Overview
Guardian X1 is a multi-functional autonomous security robot designed for home and industrial surveillance. It integrates multiple sensors for hazard detection, supports both manual and automatic control, and provides real-time video streaming using ESP32-CAM.

---

## ✨ Features
- 🚗 Dual Mode: Manual (Bluetooth) + Autonomous (Line Following)
- 🎥 Live Video Streaming (ESP32-CAM)
- ⚠️ Gas Leak Detection (MQ-2)
- 🔊 Sound Detection (KY-037)
- 🛑 Ultrasonic Obstacle Avoidance (HC-SR04)
- ⚫ Line Following (TCRT5000)
- 🔔 Buzzer Alerts & 💡 LED Indicators
- 🔊 Voice Alerts (ISD1820 Module)

---

## 🛠️ Hardware Components
| Component | Quantity |
|----------|---------|
| Arduino Nano | 1 |
| ESP32-CAM | 1 |
| L298N Motor Driver | 1 |
| DC Motors | 4 |
| HC-SR04 Ultrasonic Sensor | 1 |
| MQ-2 Gas Sensor | 1 |
| KY-037 Sound Sensor | 1 |
| TCRT5000 IR Sensors | 2 |
| ISD1820 Voice Module | 1 |
| HC-05 Bluetooth Module | 1 |
| Battery (7.4V) | 1 |

---

---

## ⚙️ Working Principle
- The robot operates in **manual mode** via Bluetooth and **automatic mode** using line-following.
- Sensors continuously monitor the environment:
  - Gas sensor detects harmful gases
  - Sound sensor detects unusual noise
  - Ultrasonic sensor detects obstacles
- On detecting hazards:
  - Robot stops immediately
  - Buzzer and LEDs activate
  - Voice alert is triggered
- ESP32-CAM provides live video streaming via WiFi.

---

## 🚀 Installation

### Arduino Code
1. Open Arduino IDE  
2. Select Board: **Arduino Nano**  
3. Select Processor: **ATmega328P**  
4. Upload `Guardian_X1_Main.ino`  

### ESP32-CAM Code
1. Select Board: **AI Thinker ESP32-CAM**  
2. Enable PSRAM  
3. Update WiFi credentials  
4. Upload code  

---

## 📱 Usage

### Bluetooth Commands
| Command | Action |
|--------|--------|
| F | Forward |
| B | Backward |
| L | Left |
| R | Right |
| S | Stop |
| M | Toggle Mode |
| X | Lights ON |
| x | Lights OFF |

---

## 📸 Demo
![image 1](https://github.com/user-attachments/assets/27794d70-d680-4e62-bc0d-f141dfe80614)

## 🎥 Demo Video
Watch the working demo of Guardian X1 here:

👉 https://youtu.be/egBaonEOTN0
---

## 🔮 Future Enhancements
- AI Object Detection  
- GPS Navigation  
- Mobile App Control  
- Cloud Monitoring  

---

## 📄 License
This project is open-source and available under the MIT License.

---

## 👤 Author
**Eshwar prasad Y**

---

## 🙏 Acknowledgments
- Arduino Community  
- ESP32 Community  
- Open Source Contributors  
