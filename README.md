# Line Follower Robot 🚗


This project implements a line follower robot using Arduino and IR sensors. The robot detects a line and adjusts motor speed to follow the path.
A build of a line‑following robot that blends quick sensor logic with steady PID‑based motor control. 
The goal is simple: keep the robot centered, smooth.

## Hardwares Used
- Arduino
- IR Sensors (3)
- L298N Motor Driver
- DC Motors
- Battery

## Working Principle
- IR sensors detect black/white line
- Based on sensor input, motor speed is adjusted
- Robot moves forward, left, or right accordingly

## Code
The main logic is implemented in `line_follower.ino`

## Future Improvements
- Obstacle avoidance
