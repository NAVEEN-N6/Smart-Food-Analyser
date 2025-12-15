# Smart Food Analyzer using ESP8266 and MQ2 Sensor

## 📌 Project Description
The Smart Food Analyzer is an IoT-based food monitoring system that detects food spoilage using an MQ2 gas sensor. The system continuously monitors harmful gases released by spoiled food and alerts users through an LCD display, buzzer, LEDs, and the Blynk mobile application.

---

## 🧰 Hardware Components
- ESP8266 (NodeMCU)
- MQ2 Gas Sensor
- 16×2 I2C LCD Display
- Green LED (Normal condition)
- Red LED (Spoiled condition)
- Buzzer
- Wi-Fi Network
- Blynk IoT App

---

## 💻 Software Requirements
- Arduino IDE
- ESP8266 Board Package
- Blynk Library
- LiquidCrystal_I2C Library

---

## ⚙️ Working Principle
The MQ2 sensor detects gases emitted from food. The ESP8266 reads the sensor value and averages multiple readings for accuracy.  
- If the value is **below threshold**, food is considered **normal**.  
- If the value **exceeds the threshold**, food is marked **spoiled**, triggering alerts.

The data is displayed on an LCD and sent to the Blynk app for real-time monitoring.

---

## 🚨 Alert Indications

| Condition | Green LED | Red LED | Buzzer | LCD Message |
|---------|-----------|---------|--------|-------------|
| Food Normal | ON | OFF | OFF | Food Normal |
| Food Spoiled | OFF | ON | ON | Food Spoiled Alert |

---

## 📱 Blynk App Features
- Live sensor value display
- LED status indicators
- Push notification for spoiled food
- Remote monitoring via smartphone

---

## 🧪 Applications
- Smart kitchens
- Food storage units
- Restaurants and hotels
- Food safety monitoring systems

---

## ✅ Conclusion
The Smart Food Analyzer is a reliable and cost-effective solution for detecting food spoilage. By combining sensors with IoT technology, it enhances food safety, reduces waste, and provides real-time alerts to users.

---

## 👨‍💻 Developed Using
- Embedded C
- Arduino IDE
- IoT (Blynk Platform)
