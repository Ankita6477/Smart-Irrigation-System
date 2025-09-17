# Smart-Irrigation-System

# 🌱 IoT Based Agriculture System Device (Irrigation Pump)

This project automates irrigation by combining **soil moisture monitoring** and **voice control**.  
Farmers can let the pump work automatically based on soil conditions, or override it with voice commands via Bluetooth.

## 🔧 Modes of Operation
1. **Automatic Mode (Soil Moisture Sensor)**
   - Continuously monitors soil moisture.
   - If soil is dry → Pump turns **ON**.
   - If soil is wet → Pump turns **OFF**.
   
2. **Manual/Voice Control Mode**
   - Farmer can control pump using voice commands ("ON", "OFF", "CHECK").
   - Uses Android + Bluetooth module.

## 🛠 Components
- Arduino UNO / ESP32
- Soil Moisture Sensor
- Bluetooth HC-05 Module
- Relay Module (2 Channel)
- ESP32 (optional for expansion)
- Water Pump / Motor
- Siemens Contactor
- Jumper wires, Breadboard

## ⚡ Working
- Soil moisture data is read by the Arduino.
- If below threshold, pump is activated automatically.
- Farmer can still control pump manually using **voice commands**.
- System ensures safe and efficient water usage.
