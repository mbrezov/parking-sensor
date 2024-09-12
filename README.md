# Parking Sensor System

This project implements a parking sensor system using an ultrasonic sensor to measure the distance between the car and potential obstacles. The sensor data is processed by a microcontroller and displayed on an LCD screen, providing real-time feedback to the driver. The system is designed to assist in parking, alerting the driver when they approach an object too closely.

## Features
- **Ultrasonic Distance Measurement**: Uses an ultrasonic sensor for accurate distance detection.
- **LCD Display**: Real-time distance readings displayed on a 16x2 I2C LCD screen.
- **Buzzer Alert**: Audible warning when the vehicle approaches obstacles.
- **LED Indicators**: Visual indicators to supplement the display and buzzer.

## Components Used
- Microcontroller (e.g., STM32)
- Ultrasonic sensor (e.g., HC-SR04)
- 16x2 LCD (I2C Interface)
- Buzzer
- LEDs

## Installation & Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/mbrezov/parking-sensor
