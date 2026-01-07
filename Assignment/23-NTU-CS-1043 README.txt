Assignment 1 – Embedded IoT Systems

Name: Malaika Arshad
Reg No: 23-NTU-CS-1043
Course: Embedded IoT Systems
Instructor: Sir Nasir Mehmood
Date: 26-Oct-2025

Overview

This contains two ESP32-based projects demonstrating fundamental concepts in embedded systems, including I/O control, state management, timing, and OLED interfacing. All code was developed and tested using the Wokwi online simulator.

Hardware & Software Environment

Development Platform: Arduino Framework (Wokwi/PlatformIO)

Simulation: Wokwi Simulator

Task 1 – Device Control using ESP32 (LEDs, Buttons, Buzzer & OLED)

Description:
The ESP32 controls three LEDs, two buttons, and a buzzer with real-time visual messages displayed on an OLED.
Buttons toggle the LEDs and buzzer states, and the OLED updates accordingly.

Components Used:

ESP32 DevKitC V4

OLED 128x64 (I2C)

LEDs × 3

Buzzer × 1

Push Buttons × 2

420? Resistors × 3

Jumper Wires

Component	ESP32 Pin
Push Button	GPIO 25
Push Button 2   GPIO 33
Red LED  	GPIO 14
Green LED	GPIO 27
Blue LED	GPIO 26
Buzzer (+)	GPIO 19
OLED SDA	GPIO 21
OLED SCL	GPIO 22
OLED VCC	3.3V
OLED GND	GND
Button other side	GND
All LED resistors	GND
Buzzer (-)	GND

Wokwi Project Link:https://wokwi.com/projects/445501799320005633

Screenshots:
!"C:\Users\Administrator\Downloads\23-NTU-CS-101TASK A BOTHH ON.jpg"
!"C:\Users\Administrator\Downloads\1016-VSCODE WORK TASKA.jpg"
!"C:\Users\Administrator\Downloads\VSCODE.DIGRAM .WOKWI.23-NTU-CS-1016.jpg"

Task 2 – Button Press Duration Detection (Short / Long Press with OLED)

Description:
This task detects short and long button presses using the ESP32.
A short press toggles the LED, while a long press activates the buzzer. The OLED displays corresponding feedback.

Components Used:

ESP32 DevKitC V4

OLED 128x64 (I2C)

Push Button × 1

LED × 1

Buzzer × 1

Resistor × 1

Pin Map:

Component	ESP32 Pin
Push Button	GPIO 25
Red LED  	GPIO 14
Green LED	GPIO 27
Blue LED	GPIO 26
Buzzer (+)	GPIO 19
OLED SDA	GPIO 21
OLED SCL	GPIO 22
OLED VCC	3.3V
OLED GND	GND
Button other side	GND
All LED resistors	GND
Buzzer (-)	GND
Wokwi Project Link:https://wokwi.com/projects/445896892712775681
 View Simulation on Wokwi

