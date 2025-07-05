
An ESP32-based smart trash bin with ultrasonic sensor, buzzer, and servo control, communicating via MQTT.

This project is a smart dustbin system that uses an *ESP32, **ultrasonic sensor, **servo motor, and **buzzer* to detect the trash level and automatically open the lid. It also publishes the fill level to an MQTT broker.

---

## 🚀 Features

- Ultrasonic sensor measures fill level
- Servo motor opens/closes lid
- Buzzer alert when bin is almost full (≥ 80%)
- Real-time MQTT publishing to HiveMQ
- Wi-Fi enabled via ESP32

---

## 📷 Components Used

- ESP32 Development Board
- HC-SR04 Ultrasonic Sensor
- Servo Motor (SG90/MG90)
- Buzzer
- Wi-Fi Router (for MQTT & internet)
- Power supply

---

## 🧠 Pin Configuration

| Component       | ESP32 Pin |
|----------------|-----------|
| Trig (Ultrasonic) | D12       |
| Echo (Ultrasonic) | D13       |
| Buzzer           | D14       |
| Servo            | D27       |

---

## 🔌 Setup Instructions

1. Replace your Wi-Fi credentials in the code:
   ```cpp
   const char* ssid = "YOUR_WIFI_SSID";
   const char* password = "YOUR_WIFI_PASSWORD";
[12:46 pm, 4/7/2025] ₹@v†πd€₹: # Smart Trash Bin using ESP32

This project is a smart dustbin system that uses an *ESP32, **ultrasonic sensor, **servo motor, and **buzzer* to detect the trash level and automatically open the lid. It also publishes the fill level to an MQTT broker.

---

## 🚀 Features

- Ultrasonic sensor measures fill level
- Servo motor opens/closes lid
- Buzzer alert when bin is almost full (≥ 80%)
- Real-time MQTT publishing to HiveMQ
- Wi-Fi enabled via ESP32

---

## 📷 Components Used

- ESP32 Development Board
- HC-SR04 Ultrasonic Sensor
- Servo Motor (SG90/MG90)
- Buzzer
- Wi-Fi Router (for MQTT & internet)
- Power supply

---

## 🧠 Pin Configuration

| Component         | ESP32 Pin |
|------------------|-----------|
| Trig (Ultrasonic) | D12       |
| Echo (Ultrasonic) | D13       |
| Buzzer            | D14       |
| Servo             | D27       |

---

## 🔌 Setup Instructions

1. Replace your Wi-Fi credentials in the code:
   ```cpp
   const char* ssid = "YOUR_WIFI_SSID";
   const char* password = "YOUR_WIFI_PASSWORD";

2. Upload the code to the ESP32 using the Arduino IDE.


3. Connect hardware as per the pin configuration.


4. Open the Serial Monitor to view real-time fill level data.


5. Use an MQTT dashboard (e.g. HiveMQ WebSocket Client) to monitor messages on topic:

trash/level




---

☁️ MQTT Settings

Broker: broker.hivemq.com

Port: 1883

Topic: trash/level



---



📸 Related pictures

![d6358965-30fa-4678-a54c-8829dc4ce449](https://github.com/user-attachments/assets/6cf89a06-39f7-4e48-b8e2-2140b086fc8b)
![3d938fd0-ed67-49a3-b02f-ebc2c0cb065b](https://github.com/user-attachments/assets/faa54038-efd8-42b4-9190-26bc7ab78776)
![3e533be3-14ef-4236-9039-e84df639c6b7](https://github.com/user-attachments/assets/d20c8df2-7f12-4e89-9c72-aac17afe6e02)
![0c6c4b3b-4f61-41c0-83a6-466a4367243d](https://github.com/user-attachments/assets/c638f3d7-bad4-4f47-b8c8-523f898afef8)




---

🧑‍💻 Author

Ravinder Singh

GitHub: [ ravipeori ]
(https://github.com/ravipeori)
