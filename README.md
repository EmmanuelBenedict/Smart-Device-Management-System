# Smart Home Device Management System

## Project Description

The **Smart Home Device Management System** is a Python Object-Oriented Programming (OOP) application that simulates the management of smart home devices. The system allows users to interact with different smart devices through a menu-driven interface.

The application demonstrates the use of the fundamental concepts of Object-Oriented Programming such as inheritance, encapsulation, method overriding, constructors, getters and setters, and class variables.

---

## Features

The system supports three smart devices:

### 1. Temperature Sensor
- Turn the device ON and OFF.
- Read the current temperature.
- Display device information.

### 2. Security Camera
- Turn the device ON and OFF.
- Start recording.
- Display recording status.
- Display device information.

### 3. Smart Light
- Turn the device ON and OFF.
- Increase brightness.
- Decrease brightness.
- Brightness range is limited between 0 and 100.
- Display current brightness.
- Display device information.

---

## Object-Oriented Programming Concepts Used

### Encapsulation
Private attributes are used to protect sensitive data.

Examples:
- `__device_id`
- `__power_status`
- `__temperature`
- `__recording_status`
- `__brightness`

Getter and setter methods are provided to access and modify these private attributes.

---

### Inheritance

The `SmartDevice` class serves as the parent class.

The following classes inherit from it:

- TemperatureSensor
- SecurityCamera
- SmartLight

This allows all devices to share common properties and methods.

---

### Method Overriding

Each child class overrides the `display_info()` method to display device-specific information while still using the parent class implementation through `super()`.

---

### Class Variables

The `SmartLight` class defines:

```python
min_brightness = 0
max_brightness = 100

## Author

EMMANUEL BENEDICT OFORI-PRAH
