🪴 Arduino Automatic Plant Watering System with Moisture Display

This project is an Arduino-based smart irrigation system designed to automatically water plants based on soil moisture levels. It helps maintain optimal soil conditions by continuously monitoring moisture and activating a water pump only when needed, reducing water waste and manual effort.

To enhance usability, the system includes a 7-segment display module driven through a BCD to 7-segment decoder IC, which displays the current soil moisture level in real time. This allows users to easily observe soil conditions without needing a computer or serial monitor.

⚙️ How It Works

The system operates in a continuous loop:

A soil moisture sensor measures the moisture level of the soil and sends an analog signal to the Arduino.
The Arduino processes this input and converts it into a simplified moisture level range.
This value is sent in BCD (Binary Coded Decimal) format to a BCD-to-7-segment decoder IC.
The decoder IC drives the 7-segment display, showing the current moisture level.
If the soil is detected as dry (below a defined threshold), the Arduino activates a relay module.
The relay turns ON the water pump, which irrigates the plant.
Once the soil reaches sufficient moisture, the pump automatically turns OFF.


🔌 Components Used
Arduino UNO
Soil Moisture Sensor
Relay Module
Water Pump
7-Segment Display
BCD to 7-Segment Decoder IC (e.g., 7447 / 4511)
Power supply
Jumper wires and breadboard


💡 Key Features
Fully automated plant watering system
Real-time soil moisture monitoring
Numeric display of moisture level using 7-segment display
Efficient use of Arduino pins using BCD-to-7-segment decoding
Simple, low-cost, and scalable design for home or agricultural use


🔧 Improvements & Future Upgrades
Add multiple plant zone support
Integrate IoT (ESP8266 / ESP32) for remote monitoring
Use LCD/OLED for more detailed sensor data
Add humidity and temperature sensors for smarter irrigation logic

📌 Purpose
The goal of this project is to demonstrate how microcontrollers can be used in real-world automation systems such as smart agriculture. It combines sensor data processing, embedded control, and digital display techniques in a single practical application.

The goal of this project is to demonstrate how microcontrollers can be used in real-world automation systems such as smart agriculture. It combines sensor data processing, embedded control, and digital display techniques in a single practical application.
