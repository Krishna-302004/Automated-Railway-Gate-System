# 🚆 Smart Automated Railway Gate System using ESP32 and AWS IoT

## Overview
The Smart Automated Railway Gate System is an IoT-based solution that enhances railway crossing safety through automated gate control and real-time cloud monitoring. Using an ESP32, sensors, and AWS IoT services, the system detects approaching trains, operates the gate automatically, and provides live status updates and alerts.

## Key Features
- Automated train detection and gate operation
- Early warning using a buzzer
- PIR-based obstacle detection before reopening
- Real-time monitoring with AWS IoT Core
- Event logging using Amazon DynamoDB
- Instant notifications through Amazon SNS

## Technologies Used
Hardware: ESP32, Vibration Sensor, PIR Sensor, Servo Motor, Buzzer

Cloud Services: AWS IoT Core, Amazon DynamoDB, Amazon SNS

## Working
1. Detects an approaching train using the vibration sensor.
2. Activates the buzzer and automatically closes the gate.
3. Sends gate status and events to AWS IoT Core.
4. Checks for obstacles using the PIR sensor before reopening the gate.

## Objective
To improve railway crossing safety by reducing human intervention, minimizing accidents, and enabling intelligent, cloud-based monitoring through IoT automation.
