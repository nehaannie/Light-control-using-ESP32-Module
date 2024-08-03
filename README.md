# Light Control Using ESP32 Module

## Overview
This project demonstrates how to control a light bulb using an ESP32 module. By connecting the ESP32 to a relay module, we can remotely turn the light on and off through a web interface. This project is a simple introduction to IoT (Internet of Things) and can be extended to control multiple devices.

## Components Required
- ESP32 Module
- Relay Module
- Light Bulb
- Breadboard
- Jumper Wires
- USB Cable (for programming the ESP32)
- 5V Power Supply (optional, for the relay)

## Circuit Diagram
![Circuit Diagram](images/ESP32.png)

## Setup Instructions
1. **Connect the ESP32 to Relay Module:**
   - ESP32 GND to Relay GND
   - ESP32 3V3 to Relay VCC
   - ESP32 GPIO 23 to Relay IN

2. **Connect the Light Bulb to Relay:**
   - One terminal of the light bulb to the Normally Open (NO) pin of the relay.
   - The other terminal of the light bulb to the common pin of the relay.
   - Connect the other side of the light bulb to the neutral power line.
   - Connect the common pin of the relay to the live power line.

## How to Run the Project
1.Assemble the Circuit<br>
2.Follow the circuit diagram to connect the components.<br>
3.Upload the Code.<br>
4.Connect the ESP32 to your computer.<br>
5.Open the Arduino IDE.<br>
6.Install the ESP32 board manager if not already installed.<br>
7.Copy the above code into the Arduino IDE.<br>
8.Replace your_SSID and your_PASSWORD with your WiFi credentials.<br>
9.Select the correct ESP32 board and port from the Tools menu.<br>
10.Click the upload button.<br>
11.Control the Light.<br>
12.Click the ON and OFF buttons to control the light.<br>

## Demo Video

![esp](esp.mp4)

## Acknowledgements
Inspired by Techatronic.
