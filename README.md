# Ultrasonic Sensor Based Toll Gate
This project is a DIY toll gate system that uses an ultrasonic sensor to detect approaching objects and trigger a gate to close and open.

## Table of Contents
1. Introduction
2. Hardware Requirements
3. Software Requirements
4. Installation
5. Usage

## Introduction
The Ultrasonic Sensor Based Troll Gate is a simple system that can be used to block trolls from entering certain areas. The system consists of an ultrasonic sensor, an Arduino board, and a gate mechanism. The ultrasonic sensor is used to detect the distance of any approaching objects. When an object is detected within a certain distance, the gate will automatically close to block the toll's path. Once the toll moves away from the sensor, the gate will automatically open again.

This project can be used in a variety of settings, such as private properties, museums, and theme parks, where a gate system is needed to prevent unauthorized access.

## Hardware Requirements
To build the Ultrasonic Sensor Based Troll Gate, you will need the following hardware:

1. Arduino board (e.g. Arduino Uno)
2. Ultrasonic sensor module (e.g. HC-SR04)
3. Servo motor (e.g. SG90)
4. Jumper wires
5. Breadboard
6. Gate mechanism (e.g. small gate hinge and a piece of wood)

## Software Requirements
To program the Arduino board, you will need the following software:

1. Arduino IDE (Integrated Development Environment)
2. Ultrasonic sensor library (e.g. NewPing)

## Installation
1. Connect the ultrasonic sensor module to the Arduino board according to the following pin layout:
- VCC to 5V
- GND to GND
- Trig to digital pin 3
- Echo to digital pin 5
2. Connect the servo motor to the Arduino board according to the following pin layout:
- VCC to 5V
- GND to GND
- Signal to digital pin 9
3. Attach the gate mechanism to the servo motor.
4. Download and install the Arduino IDE from the official website.
5. Open the Arduino IDE and install the NewPing library by going to ``Sketch > Include Library > Manage Libraries`` and search for "NewPing" in the Library Manager.
6. Download the source code from this Github repository and open it in the Arduino IDE.
7. Upload the code to the Arduino board.

## Usage
1. Power up the Arduino board.
2. Place the ultrasonic sensor facing the area you want to protect.
3. Adjust the gate mechanism so that it covers the area completely.
4. The gate should remain open until an object is detected within a certain distance by the ultrasonic sensor. The gate will then close automatically.
5. Once the object moves away from the sensor, the gate will open again.

## Contributing
If you have any suggestions or improvements for this project, please feel free to fork this repository and create a pull request. We welcome contributions from the community.
