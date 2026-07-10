# Four Servo Motor Control

Arduino project that controls four servo motors using a sweep motion for two seconds, then holds them at 90 degrees.

## Project Overview

This project demonstrates how to control four servo motors using an Arduino Uno.

The servo motors perform a sweep motion for two seconds. After that, all four servo motors move to 90 degrees and remain in that position.

## Components

- Arduino Uno
- Breadboard
- 4 Servo Motors
- Jumper Wires
- Tinkercad Circuits

## Circuit Connections

- Servo 1 Signal → Pin 2
- Servo 2 Signal → Pin 3
- Servo 3 Signal → Pin 4
- Servo 4 Signal → Pin 5
- All power wires → 5V
- All ground wires → GND

## Circuit Diagram

![Circuit Diagram](Four%20Servo%20Motor%20Control.png)

## How the Code Works

1. The Servo library is included.
2. Four servo objects are created.
3. Each servo is connected to a digital pin.
4. The servo motors move from 0° to 180° and back.
5. The sweep motion continues for two seconds.
6. All servo motors then move to 90° and remain there.

## Project Files

- `four_servo_control.ino`
- `Four Servo Motor Control.brd`
- `Four Servo Motor Control.pdf`
- `Four Servo Motor Control.mp4`
- `Four Servo Motor Control.png`

## Tinkercad Project

[Open the project in Tinkercad](https://www.tinkercad.com/things/07WFEwwIBYp-four-servo-motor-control)

## Result

The four servo motors successfully perform the sweep motion for two seconds and then hold at 90 degrees.
