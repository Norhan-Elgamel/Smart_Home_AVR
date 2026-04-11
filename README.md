# Smart_Home_AVR
For Smart Home: "AVR ATmega32 Smart Home system with LCD, Keypad, and Servo control.

Project Overview
This project is a Smart Home Control System designed for the ATmega32 microcontroller. It was developed during my 162-hour training at the Information Technology Institute (ITI). The system uses a layered architecture to manage different hardware components efficiently.

Features

Security: Password-protected entry system using a 4x4 Keypad.

Display: 16x2 LCD shows system messages like "Welcome Home" or "Enter Password."

Actuators: Servo motor control via PWM for a locking mechanism and Stepper motor integration for automated movement.

Feedback: Seven-Segment display and LED status indicators.

Sensors: ADC configuration for reading analog data from environment sensors.

File Structure
The project follows a modular driver design:

MCAL (Microcontroller Abstraction Layer): DIO, ADC, and Timers drivers.

HAL (Hardware Abstraction Layer): LCD, Keypad, Stepper Motor, and Servo drivers.

Library: Standard types and bit math definitions.
