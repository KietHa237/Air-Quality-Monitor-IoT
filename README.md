# 🌍 Advanced Air Quality Station (O3, Dust & Climate)

An integrated environmental monitoring system designed for high-precision air quality analysis. This project focuses on detecting Ozone levels and particulate matter using industrial-grade sensors.

## 📌 Sensor Specifications
- **PMS2005:** Laser-based PM2.5/PM10 sensor (Provides high-accuracy particulate matter counting).
- **MQ131:** Ozone ($O_3$) gas sensor (Detects low/high concentrations of Ozone in the atmosphere).
- **DHT22:** Precision Temperature & Humidity sensor (Digital signal via single-bus protocol).

## 🛠 Technical Details
- **Signal Processing:** Analog-to-Digital conversion for MQ131 with calibration for baseline voltage.
- **Data Protocol:** UART interface for PMS2005 to read real-time particulate density.
- **Display:** [LCD1602/OLED] for immediate on-site data feedback.
- **MCU:** [Dán tên board của bạn vào, VD: ESP32/Arduino/STM32].

## 📂 Project Structure
- `/Code`: Implementation of sensor libraries and main measurement loop.
- `/Schematic`: Wiring diagrams for interfacing Laser and Gas sensors.
- `/Data`: Calibration curves for the MQ131 Ozone sensor.

## 🚀 Why this project?
Unlike standard air monitors, this station includes **MQ131**, allowing it to detect Ozone levels, which is critical for both indoor safety and outdoor environmental research.
