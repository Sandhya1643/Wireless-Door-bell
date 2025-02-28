
                                   Wireless Doorbell using Arduino and RF Module
Aim:
To design and implement a wireless doorbell system using Arduino and RF (Radio Frequency) modules, allowing remote activation of the doorbell without the need for wired connections


Hardware Requirements:
Arduino Uno (2x) – One for the transmitter and one for the receiver
RF Module (433MHz or 315MHz) (1 set) – Includes RF transmitter and RF receiver
Push Button (1x) – To trigger the doorbell
Buzzer or Speaker (1x) – To produce the doorbell sound
12V Relay Module (Optional) – To control an external chime or bell
LED (Optional) – To indicate button press
Resistors (1kΩ, 10kΩ as needed)
Capacitors (As required for stability)
Battery or Power Adapter (9V or 12V) – To power the circuits
Connecting Wires and Breadboard

Software Requirements:
Arduino IDE – For writing and uploading code
VirtualWire or RadioHead Library – To enable RF communication between transmitter and receiver

Working Principle:
When the push button is pressed on the transmitter circuit, the Arduino sends a signal via the RF transmitter module.
The RF receiver module at the receiver end picks up the signal.
The receiver Arduino processes the signal and activates the buzzer or speaker, producing a doorbell sound.
Optionally, an LED can blink, or a relay can be used to trigger an external chime.

