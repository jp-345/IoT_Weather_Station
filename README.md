# IoT_Weather_Station
An IoT weather station prototype

# ESP32 Localized Weather Station 🌦️

An IoT weather station prototype that predicts local weather conditions without relying on external cloud APIs. This project was developed as a practical prototype during my first semester of engineering.

## 🚀 Project Overview
The core objective is to bring weather forecasting directly to the edge. By utilizing local sensor data and mathematical models, the system operates entirely offline, demonstrating the power of edge computing. 

## ✨ Key Features
* Edge Computing: Operates entirely independently of internet-based weather APIs.
* Uses current barometric pressure trends to calculate short-term weather forecasts locally.
* Sensor Fusion: The sensor fusion part under the logic and mathematics lead processes raw data from the environmental sensors to ensure accurate and stable readings.

## 🛠️ Hardware Requirements
* ESP32 Microcontroller
* BME280 Sensor (Temperature, Humidity, Pressure)
* OLED Display
* MQ-135 Chemiresistor
* MH-RD rain sensor
* Breadboard & Jumper Wires
* Components for physical prototype design

## 👥 Team Credits
This prototype was a collaborative effort built by a team of four members. Responsibilities were divided across hardware construction, mathematical logic, and presentation speech sections to successfully deliver the working model.

## 📂 Repository Contents
* C++ Code: The core logic running on the ESP32.
* Documentation: A poster presentation.
