# System Bio: ESP8266-Based RFID Access Control with OLED Display and Servo Motor
## Overview
>This advanced ESP8266-based system is designed for RFID-based access control, featuring an OLED display for real-time status updates and a servo motor to simulate physical access control mechanisms like door locks. This project is an excellent learning tool for understanding RFID technology, servo motor control, and display integration using the ESP8266 microcontroller.

## Components
1. ESP8266: The microcontroller with built-in Wi-Fi capabilities that manages all system functions.
2. MFRC522 RFID Reader: Reads RFID tags to verify access.
3. Servo Motor: Acts as a physical actuator, simulating locking and unlocking mechanisms.
4. OLED Display: A 128x64 pixel screen that provides visual feedback on the system’s status.
   
## Features
1. RFID-Based Access Control:
- Reads and verifies RFID tags against a predefined allowed NUID.
- Grants or denies access based on the RFID tag's NUID.

2. Servo Motor Control:
 - Servo motor moves to 90 degrees to simulate unlocking when access is granted.
 - Returns to 0 degrees to simulate locking after a brief delay.

3. OLED Display:
 - Displays system status messages like "Reader Initialized," "Access Granted," and "Access Denied."
 - Enhances user interaction and system transparency.

4. Serial Monitor Feedback:
 - Provides detailed feedback via the serial monitor, including the type of RFID tag detected and the NUID in hexadecimal and decimal formats.

## Technical Details
 1. Programming Language: Arduino C/C++
 2. Libraries Used:
  - SPI.h for SPI communication.
  - Wire.h for I2C communication with the OLED display.
  - Adafruit_GFX.h and Adafruit_SSD1306.h for controlling the OLED display.
  - MFRC522.h for interfacing with the RFID reader.
  - Servo.h for controlling the servo motor.

## Fritzing Design
![rfid_toll_bb](https://github.com/ImanZulhakim/FunDIYSensors/assets/92504870/50f541c6-57bf-42f2-a743-ea0803fe52d5)
