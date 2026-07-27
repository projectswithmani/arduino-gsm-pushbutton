# 📞 Arduino GSM Emergency Call & SMS System using SIM800L

An Arduino-based emergency safety device that sends an emergency SMS and automatically places a phone call when a push button is pressed and held for 2 seconds.

This project is simple, reliable, and can be used for personal safety, elderly assistance, women safety, medical emergencies, security systems, and emergency alert applications.

---

## 🎬 Demo

Press and hold the push button for **2 seconds**.

The system will:

✅ Send an Emergency SMS

✅ Automatically call the saved phone number

✅ Keep the call active until the receiver disconnects

---

# Features

- One-touch emergency trigger
- Sends emergency SMS
- Automatically places a phone call
- 2-second hold protection against accidental presses
- Simple Arduino code
- Uses SIM800L GSM module
- Easy to build
- Beginner friendly

---

# Components Required

- Arduino UNO
- SIM800L GSM Module
- Active SIM Card
- External 18650 Battery Holder
- 18650 Li-ion Battery
- Push Button
- Jumper Wires
- Electret Microphone (Optional for voice during the call)

---

# Connection Details

## Arduino UNO → SIM800L

| Arduino UNO | SIM800L |
|-------------|----------|
| D10 | TXD |
| D11 | RXD |
| GND | GND |

---

## Push Button

| Push Button | Arduino |
|-------------|----------|
| One Pin | D6 |
| Other Pin | GND |

---

## SIM800L Power

| 18650 Battery Holder | SIM800L |
|----------------------|----------|
| Positive (+) | VCC |
| Negative (-) | GND |

---

## Microphone Connection (Optional)

| Microphone | SIM800L |
|------------|----------|
| Any Pin | MIC+ |
| Other Pin | MIC- |

> Connect any microphone pin to **MIC+** and the remaining microphone pin to **MIC−**.

---

# Working Principle

1. Power ON the Arduino and SIM800L.
2. Wait until the SIM800L registers on the GSM network.
3. Press and hold the push button for 2 seconds.
4. Arduino sends an emergency SMS.
5. After the SMS is sent, Arduino automatically places a phone call.
6. The phone call remains active until the receiver disconnects.

---

# Change Your Phone Number

Replace this line inside the Arduino code:

```cpp
String phone = "**************";
```

Example:

```cpp
String phone = "+919876543210";
```

Use your number in international format.

---

# Arduino Pins Used

| Function | Pin |
|----------|-----|
| SIM800L RX | D11 |
| SIM800L TX | D10 |
| Push Button | D6 |

---

# Applications

- Women Safety Device
- Personal Safety System
- Elderly Emergency Alert
- Medical Emergency Alert
- School Safety Projects
- College Mini Projects
- IoT Learning
- Arduino GSM Projects

---

# Repository Contents

```
Arduino-GSM-PushButton/
│
├── Arduino_GSM_PushButton.ino
├── README.md
├── Connection_Diagram.png
├── Images/
└── LICENSE
```

---

# Future Improvements

- GPS Location Sharing
- Rechargeable Battery Charging Module
- OLED/LCD Display
- Buzzer Alert
- LED Status Indicator
- Multiple Emergency Contacts
- Battery Monitoring

---

# Personal Project Assistance

📞 Contact: **7847014067**

Need help with:

- Arduino Projects
- IoT Projects
- ESP32
- ESP8266
- Raspberry Pi
- College Mini Projects
- Final Year Projects
- Custom Electronics

Feel free to contact for personal project assistance.

---

# GitHub Repository

https://github.com/projectswithmani/arduino-gsm-pushbutton/tree/main

---

# License

This project is released under the MIT License.

---

## ⭐ If this project helped you, don't forget to Star the repository!
