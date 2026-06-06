# IntelliGas: Real-Time Leak Detection and Emergency Alert System

## Overview

IntelliGas is an Arduino and IoT-based gas leak detection system designed to improve safety in residential and industrial environments.

The system continuously monitors gas concentration using an MQ-2 sensor and automatically performs mitigation actions when a leak is detected.

## Features

- Real-time gas leak detection
- SMS alert notification
- Voice call alert
- Automatic exhaust fan activation
- Automatic gas regulator shutoff
- LED and buzzer warning system
- IoT monitoring capability
- Remote emergency notifications

## Hardware Components

- Arduino Uno
- MQ-2 Gas Sensor
- GSM 900A Module
- Servo Motor MG996R
- Buzzer
- LED
- Exhaust Fan
- Power Supply

## System Architecture

Gas Sensor → Arduino → Alerts & Mitigation

- Buzzer
- LED
- GSM SMS
- GSM Call
- Exhaust Fan
- Servo Motor

## Working

1. MQ-2 continuously monitors gas concentration.
2. Arduino reads sensor values.
3. If threshold exceeds:
   - Buzzer ON
   - LED ON
   - Exhaust Fan ON
   - Servo closes gas regulator
   - SMS sent
   - Voice call initiated
4. System continues monitoring until gas concentration returns to safe levels.

## Technologies Used

- Arduino IDE
- C++
- GSM Communication
- IoT Concepts
- Embedded Systems

## Team Members

- Aniket Ghaturle
- Samiksha Mendhe
- Shravani Pande
- Niket Dabhade
- Shreyash Kude

## Guide

Mr. Piyoosh Awthare

## Future Enhancements

- Cloud Dashboard
- Mobile Application
- AI-Based Leak Prediction
- Multi-Gas Detection
- LoRa Communication

## License

MIT License
