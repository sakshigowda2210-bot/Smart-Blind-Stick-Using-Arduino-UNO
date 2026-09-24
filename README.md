# Smart Blind Stick Using Arduino UNO

## Overview

A smart assistive stick developed using Arduino UNO to help visually impaired users detect nearby obstacles.

The system uses an HC-SR04 ultrasonic sensor to measure the distance to obstacles. When an obstacle is detected within 20 cm, the system activates a buzzer to provide an audible warning.

## Objective

The objective of this project is to develop a simple and low-cost obstacle detection system using Arduino UNO.
## Project Circuit

![Smart Blind Stick Circuit]
## Hardware Used

* Arduino UNO
* HC-SR04 ultrasonic sensor
* Buzzer
* Smart stick
* Connecting wires
* Power supply

## Pin Connections

| Component    | Arduino UNO Pin |
| ------------ | --------------- |
| HC-SR04 TRIG | D9              |
| HC-SR04 ECHO | D10             |
| Buzzer       | D11             |

## Working Principle

1. The HC-SR04 ultrasonic sensor sends an ultrasonic pulse.
2. The pulse reflects from a nearby obstacle.
3. Arduino UNO measures the returning echo signal.
4. The distance to the obstacle is calculated.
5. If the distance is less than 20 cm, the buzzer is activated.
6. The measured distance is displayed on the Serial Monitor.
   Distance (cm) = (echo time in µs × 0.034) ÷ 2

## Features

* Real-time obstacle detection
* Ultrasonic distance measurement
* Audible obstacle warning
* Arduino-based control
* Low-cost design
* Physical hardware implementation

## Software

* Arduino IDE
* Embedded C/C++
* Arduino UNO

## Serial Communication

* Baud rate: 9600
* Distance measurements are displayed through the Serial Monitor.

## Applications

* Assistive walking stick
* Obstacle detection
* Navigation assistance
* Embedded systems learning

## Testing

The Smart Blind Stick was physically assembled and tested for obstacle detection at different distances.

The system successfully detects nearby obstacles and activates the buzzer when the measured distance is below 20 cm.

## Future Improvements

* Add vibration feedback
* Add water detection
* Add GPS location tracking
* Add emergency SOS functionality
* Add Bluetooth or GSM communication

## Project Status

Completed and physically tested successfully.

## Author

**Sakshi**

Electronics and Communication Engineering
