# Patient HealthCare Monitoring System

## Project Overview
The Patient HealthCare Monitoring System is an embedded healthcare monitoring application developed using Arduino and multiple sensors to monitor a patient's vital health parameters in real time. The system measures heart rate, blood oxygen level (SpO2), body temperature, and detects abnormal conditions using sensor inputs.

When abnormal values are detected, the system automatically sends SMS alerts and initiates a phone call to emergency contacts for immediate attention.

## Features
- Real-time Heart Rate Monitoring
- Blood Oxygen Level (SpO2) Monitoring
- Temperature Monitoring
- Sound Detection Monitoring
- Emergency Push Button Detection
- LCD Display for Live Health Parameters
- Automatic SMS Alert System
- Emergency Call Notification
- Abnormal Condition Detection

## Technologies Used
- Arduino Programming (C++)
- Embedded Systems
- MAX30105 Sensor
- LCD Display Module
- GSM Communication Module
- Temperature Monitoring
- Health Monitoring Sensors

## Hardware Components Required
- Arduino Board
- MAX30105 Pulse Oximeter and Heart Rate Sensor
- LCD Display (16x2)
- GSM Module
- Push Button
- Sound Sensor
- Buzzer
- Jumper Wires
- Breadboard
- Power Supply

## Libraries Used
The following Arduino libraries are used in this project:

- Wire.h
- MAX30105.h
- heartRate.h
- LiquidCrystal.h

## Working of the System
1. The system starts and initializes all sensors and modules.
2. The MAX30105 sensor measures heart rate and SpO2 values.
3. Body temperature is monitored using the temperature sensing feature.
4. Sound sensor and push button are continuously monitored.
5. Health values are displayed on the LCD screen.
6. If abnormal conditions are detected:
   - Low or high heart rate
   - Low oxygen level (SpO2)
   - High temperature
   - Sound alert trigger
   - Emergency button press
7. The system automatically:
   - Sends SMS alerts to emergency contacts
   - Initiates a phone call to alert caregivers

## Parameters Monitored
| Parameter | Description |
|----------|-------------|
| Heart Rate | Measures beats per minute (BPM) |
| SpO2 | Blood oxygen saturation level |
| Temperature | Body temperature monitoring |
| Sound Sensor | Detects abnormal sound conditions |
| Push Button | Emergency alert activation |

## Alert Conditions
The system triggers an alert under the following conditions:

- SpO2 level falls below safe range
- Heart rate becomes too low or too high
- Temperature exceeds threshold value
- Sound sensor detects abnormal signal
- Emergency push button is pressed

## Project Flow
Input Sensors → Health Data Collection → Parameter Analysis → Abnormal Condition Detection → LCD Display → SMS Alert & Emergency Calling

## Output
The system displays:
- Heart Rate
- SpO2 Level
- Temperature
- Sensor Status

In case of abnormal readings:
- SMS notification is sent to registered phone numbers
- Emergency call is initiated automatically

## Advantages
- Real-time patient monitoring
- Automatic emergency alert system
- Continuous health tracking
- Reduced manual monitoring effort
- Fast emergency response support

## Applications
- Hospitals
- Home patient monitoring
- Elderly care systems
- Emergency healthcare monitoring
- Smart healthcare applications

## Future Enhancements
- Mobile application integration
- IoT cloud monitoring
- Real-time health dashboard
- GPS-based emergency tracking
- Online doctor notification system

## Conclusion
The Patient HealthCare Monitoring System helps monitor important patient health parameters continuously and automatically alerts caregivers during abnormal situations. This improves patient safety and supports faster emergency response in healthcare environments.

## Author : Hema Deepika
Contact : velagahema@gmail.com
