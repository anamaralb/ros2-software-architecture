# Obstacle Avoidance (ROS2)

ROS2 package implementing an obstacle avoidance behavior using a Finite State Machine.

The robot moves forward until detecting an obstacle, performs a turn and an arc motion to avoid it, and continues navigating autonomously.

## Features

- Finite State Machine control
- Laser-based obstacle detection
- Velocity command publishing
- Button input handling
- LED state feedback
- Tested on Kobuki robot

## Technologies

- ROS2
- C++
- rclcpp
- LaserScan
- Kobuki

## Run

```bash
ros2 launch avoid_cerodumped_cpp avoid_cerodumped.launch.py