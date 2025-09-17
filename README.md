# 🌱  Smart-Irrigation-System

This project is designed to automate agricultural irrigation pumps using soil moisture sensing and Bluetooth voice control. It addresses the challenges faced by farmers in remote areas where cellular networks are unavailable and manual operation of pumps is difficult due to bad weather, night-time risks, or rough terrain.

The system ensures that crops get adequate water supply without wastage and allows farmers to override automation manually using their smartphones.

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
