
# AI-Assisted Fire-Response Robot

## Project Overview

This project explores a mobile robot that helps an
operator monitor environmental readings and detect
nearby obstacles in a controlled test environment.

## Features

- ESP32-based sensor monitoring
- Temperature and humidity readings
- Ultrasonic obstacle-distance measurement
- Threshold-based demonstration alerts
- Web dashboard mock-up

## Hardware

- ESP32 development board
- DHT22 temperature and humidity sensor
- HC-SR04 ultrasonic sensor
- Jumper wires and USB cable

## Software

- Arduino IDE
- ESP32 board support
- Adafruit DHT sensor library
- HTML, CSS and JavaScript dashboard

## How to Run

1. Install Arduino IDE and ESP32 board support.
2. Install the Adafruit DHT sensor library.
3. Connect the sensors according to the project
   wiring instructions.
4. Open esp32_firmware/fire_response_robot.ino.
5. Select your ESP32 board and serial port.
6. Upload the code.
7. Open Serial Monitor at 115200 baud.
8. Open dashboard/index.html in a web browser.

## Current Limitations

The dashboard uses simulated values and is not
connected to the ESP32. The prototype does not
perform AI-confirmed fire detection, victim rescue,
or fire suppression.

## Safety

This is an educational prototype, not certified
firefighting equipment. Never test it in real flames
or smoke. Human emergency responders remain
essential.
