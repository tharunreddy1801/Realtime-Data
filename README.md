# 📡 Real-time Ultrasonic Distance Data to Adafruit IO using MQTT and ESP8266
## 📘 Overview
This project showcases how to send real-time distance measurements from an ultrasonic sensor (HC-SR04) to the Adafruit IO cloud platform using the MQTT protocol with an ESP8266 microcontroller. The system continuously measures the distance of nearby objects and publishes the data to the cloud for live monitoring.

Using the MQTT protocol, the ESP8266 establishes a connection with Adafruit IO and sends distance data at regular intervals. Adafruit IO provides a user-friendly dashboard to visualize the data in real time using charts and gauges.
## 🔧 Features
- 📏 **Ultrasonic Distance Sensing** using HC-SR04
- 📶 **Wi-Fi Communication** with ESP8266 (NodeMCU)
- ☁️ **Cloud Integration** with Adafruit IO via MQTT
- 📊 **Real-time Data Visualization** on Adafruit IO Dashboard
- 🔁 **Continuous Publishing** of distance data at set intervals

## 📁 Repository Contents

.Code to interface the HC-SR04 ultrasonic sensor with ESP8266

.Wi-Fi and MQTT setup using NodeMCU(ESP8266)

.Integration with Adafruit IO using MQTT credentials

.Real-time data publishing and dashboard visualization

.Circuit diagram, sample dashboard screenshots, and code comments

## 📡 Hardware Requirements

- 🔌 **ESP8266 (NodeMCU)**
- 🔊 **HC-SR04 Ultrasonic Sensor**
- 🔗 **Jumper wires**
- 🔋 **Breadboard and USB Cable**
- 🌐 **Wi-Fi Access Point**

# Circuit Diagram
![Circuit Diagram](https://github.com/tharunreddy1801/Realtime-Data/blob/f3096b375411d7fe0d87e9bba6a771a719f63667/real-time-data.png?raw=true)

## 🔐 Applications
This is ideal for IoT projects like obstacle detection, smart parking systems, or distance monitoring applications.
## 🚀 Future Improvements
-Add temperature compensation for more accurate distance
-Enable alerts when object crosses a set threshold
-Support multiple sensors



