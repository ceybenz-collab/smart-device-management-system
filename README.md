# smart-device-management-system
# Smart Device Management System

## Project Overview

A Python-based Object-Oriented Programming (OOP) application that simulates a smart home device management system. This project demonstrates key OOP concepts including inheritance, encapsulation, polymorphism, and the use of properties and getter/setter methods.

## Features

- **Device Management**: Create and manage different types of smart devices
- **Device Types**:
  - Temperature Sensor: Read current temperature
  - Smart Light: Adjust brightness levels (0-100%)
  - Security Camera: Start/stop recording
- **Core Functionality**:
  - Turn devices on/off
  - Display device information
  - Adjust device-specific settings
  - Interactive menu-driven interface

## OOP Concepts Demonstrated

### Inheritance
- All device classes inherit from the `SmartDevice` parent class
- Child classes override and extend parent methods
- `super()` is used to initialize inherited attributes

### Encapsulation
- Private attributes (`_device_id`, `_power_status`) are protected
- Property decorators control access to private attributes
- Validation ensures data integrity

### Polymorphism
- Each device class implements its own version of `display_info()`
- Device-specific methods are called polymorphically

## Project Structure
