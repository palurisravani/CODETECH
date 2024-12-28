Name: PALURI SRAVANI  Company: CODTECH IT SOLUTIONS PVT. LTD Intern ID: CT12EFN  Domain: Embedded Systems Duration: December 17th, 2024 to February 17th, 2025

Overview of the Project Project: LED Blinking with Arduino Program an Arduino board to blink an LED at a specific interval. This project introduces basic embedded programming concepts and interfacing with hardware.

Objective Program an Arduino to control an LED. Use digitalWrite() and delay() functions for timing.

Components Required Arduino board (e.g., Uno, Nano) 1 LED 220Ω resistor Breadboard and jumper wires

Circuit Diagram Connect the anode (longer leg) of the LED to digital pin 13 through a 220Ω resistor. Connect the cathode (shorter leg) to the GND pin. Alternatively, if you're using an Arduino Uno, the onboard LED is already connected to pin 13, so you can test without external components.

Explanation Setup Function (setup()): Runs once when the Arduino starts. The pinMode() function sets pin 13 as an output pin.

Loop Function (loop()): Repeats indefinitely. Turns the LED on, waits for the specified interval, then turns it off and waits again.

Functions Used: pinMode(pin, mode): Configures the specified pin as INPUT or OUTPUT. digitalWrite(pin, value): Sets the pin to HIGH (ON) or LOW (OFF). delay(ms): Pauses the program for the specified duration in milliseconds.

Testing Upload the code to your Arduino using the Arduino IDE. Check if the LED blinks at 1-second intervals. If it doesn’t work: Verify the wiring. Check if the LED is functional. 

![WhatsApp Image 2024-12-28 at 3 35 35 PM](https://github.com/user-attachments/assets/73f0eecd-f781-4228-8d25-0b394ba15266)
