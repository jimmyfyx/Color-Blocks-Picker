# Color Blocks Picker with UR3

## Overview and Objective
This project involves designing a robotic system using a UR3 arm for identifying and picking colored blocks. The system employs ROS for communication and control, and an vison-based blob detector for color identification. The project was developed as part of the **ECE470 Introduction to Robotics** course at University of Illinois Urbana-Champaign.

The goal of this project was to apply key robotics concepts such as computer vision, kinematics, and control to develop an automated pick-and-place system. By integrating ROS with the UR3 robotic arm, the project demonstrates a toy example of robotics applications in manufacturing and automation.

## Table of Contents
- [Project Overview](#overview-and-objective)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Implementation Details](#implementation-details)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Contributors](#contributors)
- [Acknowledgements](#acknowledgements)

## Features
- **Blob Detection**: Develope a blob detector using OpenCV to identify colored blocks
- **Pick-and-Place Operations**: Implement inverse and forward kinematics to perform precise pick-and-place tasks with the UR3 arm
- **Real-Time Control**: Integrate with ROS for real-time communication and control of the UR3 robotic arm


## System Architecture
![System Architecture Diagram](tbd.png)

The system consists of the following components:
1. **Perception Module**: Detects and identifies colored blocks using OpenCV
2. **Kinematics Module**: Computes inverse and forward kinematics for the UR3 arm to execute pick-and-place operations
3. **Control Module**: Utilizes ROS to control the UR3 arm's movement and gripper


## Implementation Details
TBD


## Installation and Setup
### Prerequisites
- Python 3.x
- Numpy 1.4 +
- OpenCV 3.0 +
- Scipy 1.10 +
- A functional UR3 with ROS Noetic set up

### Installation Steps
- Place the package in the ROS workspace on a device that can communicate with a UR3 arm
- Rebuild the workspace
    
## Usage
### Running the System
1. Launch the ROS nodes to initialize the camera and UR3 arm
2. Run the execution node:
    ```bash
    cd package/scripts
    python3 execute.py
    ```

## Demonstration
- [Demo video](https://demovideo.com)

## Contributors
- **Yixiao Fang** - [GitHub](https://github.com/jimmyfyx)
- Josh Akin

## Acknowledgements
Special thanks to all the ECE470 course staff in Spring 2022 for guidance

