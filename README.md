# IOT-based-health-monitoring-system
This project enables the monitoring of a patient's health, including heart rate (BPM) and body temperature, by utilizing the ESP8266-01 WiFi module. The monitored data is sent to a ThingSpeak Server, where it is stored in your own specific Channel. Additionally, the system is integrated with IFTTT applets using ThingHTTP and React, facilitating the simultaneous update of the monitored data to Google Sheets. In case of any abnormal behavior detected, the system automatically sends a panic alert to your email.

The primary motivation behind this project is to enable remote monitoring of your parents or loved ones from anywhere in the world. By doing so, you can take prompt action if any health issues arise and ensure timely assistance, potentially preventing any delays in providing necessary care.
# Hardware Components
- Arduino UNO Board
- ESP8266-01 Module
- LCD Display
- Pulse Sensor
- DS18B20 Temperature Sensor
- DC Buzzer
- Potentiometer-10k pot
- 4.7K&100 ohm Resistor
# Key Steps
1. Assembling the sensors with the Arduino Board
2. Creating a ThingSpeak Server and Configuring ESP8266-01
3. Coding and Uploading to the Arduino UNO and Transmitting data to ThingSpeak Server.
4. Creating IFTTT Applets and Integrating with ThingSpeak Server

# Circuit diagram for configuring ESP8266-01 Module:
This configuration pairs your ESP8266-01 Module with your Wifi or Personal Hotsot Network and connects with your respective ThingSpeak channel.
![image](https://github.com/Saimanoj1247/IOT-based-health-monitoring-system/assets/147239207/1f90a40b-e4b6-49cc-b1b1-795c18dc5acd)

# Prototype
![255959722-132d1c21-97ea-4b24-8c45-2ecd87e79045](https://github.com/Saimanoj1247/IOT-based-health-monitoring-system/assets/147239207/afdc2af4-1bd6-4409-ab5e-864d1450a860)







