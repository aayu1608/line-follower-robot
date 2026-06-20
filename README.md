# Line Follower Robot

## Overview

This project presents the design and implementation of an autonomous Line Follower Robot using an Arduino Uno, IR sensors, and an L298N motor driver. The robot is capable of detecting and following a black line on a contrasting surface by continuously processing sensor inputs and adjusting motor movement in real time.

This project demonstrates the application of embedded systems, sensor interfacing, motor control, and basic autonomous navigation principles.

---

## Components Used

- Arduino Uno
- L298N Motor Driver Module
- 2 × IR Sensor Modules
- 2 × DC Motors
- Robot Chassis
- Wheels
- Battery Pack
- Jumper Wires

---

## Working Principle

Two IR sensors are mounted beneath the robot to detect the presence of a black line. Based on the sensor readings, the Arduino controls the motors through the L298N motor driver to keep the robot aligned with the path.

### Navigation Logic

| Left Sensor | Right Sensor | Action          |
|-------------|--------------|-----------------|
| White       | White        | Move Forward    |
| Black       | White        | Turn Left       |
| White       | Black        | Turn Right      |
| Black       | Black        | Stop / Re-align |

The robot continuously repeats this process, allowing it to autonomously follow the designated path.

---

## Features

- Autonomous line tracking
- Real-time sensor-based navigation
- PWM speed control for smooth movement
- Simple and cost-effective design
- Easy to modify and extend for advanced applications

---

## Applications

- Educational robotics projects
- Autonomous guided vehicles (AGVs)
- Warehouse navigation systems
- Path-following robots
- Robotics and embedded systems learning

---

## Skills Demonstrated

- Arduino Programming
- Embedded Systems Development
- Sensor Integration
- Motor Driver Interfacing
- Robotics Fundamentals
- Hardware Debugging and Testing

---

## Future Improvements

- PID-based control for smoother line following
- Obstacle detection and avoidance
- Junction detection
- Maze-solving capability
- ROS 2 integration for advanced control

---

## Demo Video Link

https://drive.google.com/drive/folders/1gUJq877MtUOXvaTAryVBez_PskQL84vq?usp=share_link
