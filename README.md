# Line-Following_and_Obstacle-detection_Robot 

This repository contains the code, design files, and documentation for an Arduino-based line-following robot with autonomous navigation and obstacle detection capabilities. The robot is equipped with infrared (IR) sensors for line detection and a color sensor for obstacle detection based on color differentiation. The body of the robot was designed using CAD software for a streamlined structure optimized for sensor placement and efficient movement.

## Project Overview

The line-following robot is designed to autonomously navigate along a marked path. IR sensors detect and follow the line, while a color sensor identifies obstacles based on color, allowing the robot to adjust its path accordingly. This project demonstrates the integration of various sensors and control mechanisms to enable real-time navigation and obstacle avoidance.

## Features

- **CAD-Designed Body:** The robot's body was carefully designed using CAD software to accommodate sensors and motors, ensuring optimal performance and stability.
- **Line Detection:** IR sensors track a black line on a light-colored surface, guiding the robot along a predefined route.
- **Color-Based Obstacle Detection:** The color sensor detects obstacles based on color, enabling the robot to avoid objects in its path.
- **Motor Control:** An L298 motor driver controls the robot’s movement based on sensor inputs, ensuring precise navigation and speed adjustments.

## Team Collaboration

Each team member actively contributed to all components of the project. Decisions on design and functionality were made collaboratively to ensure the best solutions. Every part of the project was reviewed, improved, and validated by all team members to maintain a high standard of quality in the final submission.

## Hardware Components

- **Arduino:** Processes sensor data and controls the motors.
- **IR Sensors:** Used for line detection.
- **Color Sensor:** Detects obstacles based on color.
- **Ultrasonic Sensor:** For obstacle detection based on distance.
- **L298 Motor Driver:** Controls the robot’s motors based on inputs from the Arduino.

## Setup and Usage

1. **Assembly:** Assemble the CAD-designed body and attach the IR sensors, color sensor, and motor driver to the Arduino.
2. **Code Upload:** Flash the provided code onto the Arduino.
3. **Testing:** Place the robot on a track and observe its line-following and obstacle detection abilities.

## Future Enhancements

- Optimize color detection for dynamic obstacle identification.
- Improve motor control for faster, smoother line-following.
- Implement adaptive learning algorithms for enhanced path-following.
