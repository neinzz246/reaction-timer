# reaction-timer
a fun game to measure the reaction response time
An Arduino-based reaction timer game that measures how fast you can respond to a signal.
The system uses a push button, 16x2 LCD display, and a buzzer to provide feedback and show your reaction speed in milliseconds.

Features
Random delay before start to avoid guessing
Buzzer sound and LCD display as "GO!" signal
Measures reaction time in milliseconds
Results displayed on 16x2 LCD
Simple, low-cost, and fun interactive project
Components
Arduino Uno (or compatible)
16x2 LCD (I2C recommended)
Push button
Buzzer
Resistors (10kΩ for button pull-down if needed)
Breadboard and jumper wires
Working Principle
The LCD displays "Get Ready".
After a random delay, the LCD shows "GO!" and buzzer beeps.
The player presses the button as quickly as possible.
Arduino calculates the reaction time using millis() and displays it on the LCD.
