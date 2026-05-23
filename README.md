# Home Automation System

A Python object-oriented home automation simulation built for an Engineering Programming assessment. The project models smart-home devices, sensors, automation controllers, safety systems, scheduling routines, and energy monitoring using inheritance and composition.

## Project Overview

This system demonstrates how different smart-home components can work together through a central automation hub. It includes device status tracking, simulated sensor readings, automated responses, safety handling, and a unit test suite.

## Features

- Core device hierarchy using object-oriented programming principles
- Light and smart light control with brightness and energy usage
- Temperature, motion, smoke, humidity, and soil moisture sensors
- Thermostat and humidity control automation
- Door lock and motion-based security system
- Fire alarm system with sprinkler response
- Irrigation controller based on soil moisture levels
- Smart scheduler for time-based routines
- Energy monitoring and automatic energy management
- Demonstration workflow inside the notebook
- Unit tests covering the main system behaviours

## Repository Structure

```text
home_automation_assessment/
├── README.md
├── UML diagram.png
└── chau0732/
    ├── chau0732.ipynb
    └── chau0732.docx
```

## Technologies Used

- Python 3
- Jupyter Notebook
- `unittest`
- Object-oriented programming

## Main Components

- `Device`: Base class for all smart-home devices
- `Sensor`: Base class for sensor-style devices
- `Light` and `SmartLight`: Lighting devices with energy tracking
- `Thermostat`: Climate control device
- `DoorLock` and `SecuritySystem`: Access and security automation
- `SmokeDetector`, `Sprinkler`, and `FireAlarmSystem`: Fire safety automation
- `SoilMoistureSensor` and `IrrigationController`: Garden watering automation
- `HumiditySensor` and `HumidityController`: Humidity management
- `Clock` and `SmartScheduler`: Time-based routine scheduling
- `EnergyMonitor`: Total energy usage monitoring
- `HomeAutomationHub`: Central coordinator for automation behaviour

## How to Run

1. Open the notebook:

   ```text
   chau0732/chau0732.ipynb
   ```

2. Run all cells in Jupyter Notebook, JupyterLab, VS Code, or another notebook environment.

3. The notebook will:

   - Load all classes
   - Demonstrate the home automation workflow
   - Run the unit test suite

## Testing

The notebook includes a `unittest` test suite covering device actions, automation responses, scheduler logic, fire alarm handling, irrigation, security, humidity control, and energy monitoring.

At the time of submission, the notebook output shows:

```text
Tests run: 46 | Failures: 0 | Errors: 0
```

## Author

Devendra Chaudhari

## Suggested GitHub Description

Python OOP smart-home automation simulation with sensors, controllers, security, irrigation, fire safety, scheduling, energy monitoring, UML, and tests.
