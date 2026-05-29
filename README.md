# IoT-Based Smart Parking System

This is a team project which consists of 3 members 
I did the hardware part  

## Overview

The IoT-Based Smart Parking System is designed to automate parking management using IoT hardware and a web-based platform. The system allows users to pre-book parking slots, verify access through OTP authentication, and manage parking and unparking operations efficiently.

## Features

- Real-time parking slot monitoring
- Pre-booking of parking slots
- OTP-based authentication
- Automated parking and unparking process
- Website integration for remote access
- User registration and email verification
- Parking fee payment through web portal
- Secure access control

## Technologies Used

### Hardware
- ESP32 / Arduino Controller
- Ultrasonic Sensors
- IR Sensors
- Servo Motors
- LCD Display

### Software
- HTML
- CSS
- JavaScript
- REST API
- IoT Backend Integration

## System Workflow

1. User arrives at the parking lot.
2. User selects Park or Un-Park.
3. For pre-booked parking:
   - Enter registered email.
   - Enter OTP.
   - System verifies credentials.
   - Barrier opens automatically.
4. For non-pre-booked parking:
   - Enter registered email.
   - System assigns an available parking slot.
5. During unparking:
   - User completes payment (if applicable).
   - Barrier opens after verification.

## Project Architecture

- IoT Hardware Layer
- Backend Server
- REST API Communication
- Website Frontend
- User Database

## Results

The system successfully demonstrates:

- Pre-booked parking access
- OTP validation
- Non-pre-booked parking allocation
- Parking slot monitoring
- Automated parking barrier control
- Secure user verification

## Future Enhancements

- Mobile Application Integration
- QR Code Based Entry
- Online Payment Gateway Integration
- AI-Based Parking Prediction
- Cloud Database Support

