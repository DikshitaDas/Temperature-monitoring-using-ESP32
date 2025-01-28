# 🌡️ IoT Temperature Monitoring Using ESP32

## ✨ Overview
Monitor real-time temperature with an **ESP32 microcontroller** and **DS18B20 sensor**, while visualizing data on the **Blynk IoT platform**. The project integrates hardware and software to create an intuitive IoT-enabled temperature monitoring solution.

---

## 🛠️ Features
- 📈 Real-time temperature monitoring in Celsius and Fahrenheit.
- 🌐 Wi-Fi-enabled IoT integration.
- 📊 User-friendly dashboards for web and mobile.

---
### Flowchart
![ESP32 Board](https://github.com/DikshitaDas/Temperature-monitoring-using-ESP32/blob/main/flowchart.jpeg)

---

## 🔩 Hardware Requirements
- 🖥️ **ESP32 Development Board**
- 🌡️ **DS18B20 Temperature Sensor**
- 📶 **Wi-Fi Network**

---

## 💻 Software Requirements
- 🛠️ **Arduino IDE**
- 📦 Libraries: `WiFi`, `BlynkSimpleEsp32`, `DallasTemperature`, `OneWire`
- 🌐 **Blynk IoT Cloud 2.0**

---

## 🚀 Setup Guide
1. **Hardware**: Refer to the [Hardware Setup Guide](Documentation/Hardware_Details.md) for connections.  
   ![ESP32 Board](https://github.com/DikshitaDas/Temperature-monitoring-using-ESP32/blob/main/circuit/Circuit_Diagram.png)

2. **Software**:  
   - Install Arduino IDE and required libraries.  
   - Follow the [Blynk IoT Setup Guide](Documentation/Software_Setup.md).  
   ![Blynk Template](https://github.com/DikshitaDas/Temperature-monitoring-using-ESP32/blob/main/circuit/web_based_interface.png)

3. **Code**: Upload the [TemperatureMonitoring.ino](ArduinoCode/TemperatureMonitoring.ino) file to your ESP32.



## 📜 License
This project is licensed under the [MIT License](LICENSE).  
