# Smart Button-Activated LED with Melody and Display with ESP8266
> This innovative ESP8266-based system seamlessly integrates multiple functionalities to provide an interactive and educational experience. Combining LED control, musical output, and real-time display updates, it serves as an excellent project for beginners and enthusiasts alike to understand the basics of electronics and programming with Wi-Fi enabled microcontrollers.

## Components

1. Breadboard
2. Buzzer
3. LED
4. OLED
5. 10k resistor
6. Jumper wires
7. Push Button

## Features

1. Button-Controlled LED:
   - The LED turns on when the button is pressed and off when it is released.
   - This simple yet effective feature helps users learn about digital inputs and outputs.

2. Melody Playback:
   - When the button is pressed, a melody ("Twinkle, Twinkle, Little Star") is played through the buzzer.
   - The system uses PWM (Pulse Width Modulation) to generate musical tones, making it an engaging way to explore sound synthesis.
     
3. OLED Display:
   - Provides real-time feedback on the system’s status.
   - Displays messages like "LED Turned ON" or "LED Turned OFF", making the system more interactive and user-friendly.


## Technical Details

- Programming Language: Arduino C/C++
- Libraries Used:
  - Wire.h for I2C communication with the OLED display.
  - Adafruit_GFX.h and Adafruit_SSD1306.h for controlling the OLED display.


## Fritzing Design
![twinkle2buttonledbuzzer_bb](https://github.com/ImanZulhakim/FunDIYSensors/assets/92504870/0072d7bb-240f-4839-963a-94c8bbc32eab)



