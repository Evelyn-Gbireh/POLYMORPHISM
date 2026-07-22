# POLYMORPHISM-Traffic-Management-System

## Project Overview
This repository contains an Object-Oriented Programming (OOP) implementation of a **Smart Traffic Management System** in Python, demonstrating the concept of **Polymorphism**.

## Problem Statement
A smart city manages various traffic devices (e.g., traffic lights, speed cameras, pedestrian signals). Every device responds to a uniform command, `activate()`, but executes a unique behavior based on its specific function.

## Key Features
* **Base Class (`TrafficDevice`)**: Defines the general blueprint and base implementation for all smart devices.
* **Child Classes**:
  * `TrafficLight`: Manages traffic light signaling.
  * `SpeedCamera`: Detects vehicle speed violations.
  * `PedestrianSignal`: Controls pedestrian crosswalk lights.
  * `EmergencySiren`: Triggers high-priority emergency alerts.
* **Polymorphic Activation Loop**: Iterates through a list of diverse device instances and triggers `activate()` dynamically without needing type-checking or conditional logic (`if`/`else`).

## How to Run
Run the main script using Python 3:
```bash
python main.py
