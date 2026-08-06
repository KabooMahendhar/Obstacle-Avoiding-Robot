# Obstacle-Avoiding-Robot
# Obstacle Avoiding Robot Using Arduino

## Overview

This project is a basic autonomous robot that detects and avoids obstacles using an ultrasonic sensor. The robot uses an Arduino Uno, HC-SR04 ultrasonic sensor, servo motor, L298N motor driver, and two DC motors.

## Features

- Automatic obstacle detection
- Forward and backward movement
- Left and right turning
- Ultrasonic distance measurement
- Servo-based direction scanning

## Components

- Arduino Uno
- HC-SR04 ultrasonic sensor
- L298N motor driver
- Servo motor
- Two DC motors
- Robot chassis
- Battery
- Jumper wires

## Working Principle

The ultrasonic sensor continuously measures the distance between the robot and nearby objects.

When the detected distance is greater than 20 cm, the robot moves forward.

When an obstacle is detected within 20 cm, the robot:

1. Stops
2. Moves backward
3. Checks the left and right sides
4. Selects the direction with more free space
5. Turns and continues moving

## Pin Connections

| Component | Arduino Pin |
|---|---:|
| Ultrasonic Trigger | 9 |
| Ultrasonic Echo | 10 |
| Servo Signal | 6 |
| L298N IN1 | 2 |
| L298N IN2 | 3 |
| L298N IN3 | 4 |
| L298N IN4 | 5 |

## Software Required

- Arduino IDE
- Servo library

## How to Run

1. Connect all components according to the circuit diagram.
2. Open the Arduino code in Arduino IDE.
3. Select the Arduino Uno board.
4. Select the correct COM port.
5. Upload the code.
6. Switch on the robot's battery.
7. Place the robot on a flat surface.

## Applications

- Autonomous navigation
- Educational robotics
- Smart vehicles
- Industrial obstacle detection
- Beginner Arduino projects

## Future Improvements

- Bluetooth mobile control
- Line-following mode
- ESP32 camera integration
- Voice control
- GPS tracking
- IoT monitoring

## Author

Bandlamudi Mahendhar
