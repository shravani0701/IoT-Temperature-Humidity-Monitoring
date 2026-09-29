# IoT-Based Temperature and Humidity Monitoring System

## About the Project

This project is an IoT-based temperature and humidity monitoring system using NodeMCU and DHT11 sensor.

The system measures temperature and humidity and uses ThingSpeak for remote monitoring. A 12V DC fan is automatically controlled using a relay when the temperature rises above 30°C.

## Components Used

- NodeMCU
- DHT11 Temperature and Humidity Sensor
- Relay Module
- 12V DC Fan
- Breadboard
- Jumper Wires
- ThingSpeak

## Working

1. DHT11 measures temperature and humidity.
2. NodeMCU reads the sensor values.
3. The data is sent to ThingSpeak for remote monitoring.
4. When temperature rises above 30°C, the relay turns ON the 12V DC fan.
5. When temperature is 30°C or below, the fan turns OFF.

## Features

- Temperature monitoring
- Humidity monitoring
- Remote monitoring using ThingSpeak
- Automatic fan control
- IoT-based monitoring system

## Technologies Used

- Arduino IDE
- C/C++
- NodeMCU
- DHT11
- ThingSpeak
- IoT
