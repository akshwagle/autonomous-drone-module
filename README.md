# Autonomous Drone Conversion Module

## Overview
This project aims to create a modular system that can convert a manually controlled drone into an autonomous drone. The module will connect to an existing flight controller and provide additional sensors and computing power for autonomous navigation.

The goal is to make autonomous drone development easier for students, hobbyists, and researchers without requiring them to redesign the entire drone system.

## Problem
Most hobby drones can only be controlled manually. Making a drone autonomous usually requires complex setup including additional computers, sensors, and software integration. This process is difficult for beginners.

## Solution
The Autonomous Drone Module is a plug-and-play system that adds autonomy features to existing drones. By connecting this module to a flight controller, users can enable features such as:

- Autonomous waypoint navigation
- Obstacle detection
- Position hold
- Computer vision experiments

## System Architecture
The system consists of:

- Flight Controller (Cube+)
- Companion Computer (Raspberry Pi)
- LiDAR Sensor for obstacle detection
- Optical Flow Sensor for indoor navigation
- Camera for computer vision
- MAVLink communication between systems

## Components
- Raspberry Pi
- TF-Luna LiDAR
- Optical Flow Sensor
- Camera Module
- Power Module
- Mounting System

## Goals of the Project
- Build a prototype autonomy module
- Integrate sensors with MAVLink communication
- Test autonomous navigation on a drone platform
- Document the system for other builders

## Future Improvements
- Custom PCB for autonomy module
- Improved obstacle avoidance algorithms
- AI-based navigation
- Integration with ROS2

## Project Status
Currently in the early design phase.
