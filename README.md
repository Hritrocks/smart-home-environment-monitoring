# Smart Home Environmental Monitoring System

## Week 1 — System Requirements Analysis and Block Diagram Design

The **Smart Home Environmental Monitoring System** is a proposed embedded-system design for monitoring basic indoor environmental conditions such as temperature, humidity, air quality, and light intensity.

The proposed system uses environmental sensors connected to an **ESP32 microcontroller**. The ESP32 acts as the central controller, processes the collected sensor readings, and provides the information through a local OLED display. Its built-in Wi-Fi capability is also proposed for remote monitoring.

## Project Objectives

* Monitor room temperature.
* Monitor humidity.
* Monitor general indoor air-quality conditions.
* Measure light intensity.
* Process sensor data using a microcontroller.
* Display current readings locally.
* Support wireless data transmission.
* Provide a modular and expandable system architecture.

## Proposed Components

| Component    | Purpose                                   |
| ------------ | ----------------------------------------- |
| ESP32        | Central processing and Wi-Fi connectivity |
| DHT22        | Temperature and humidity measurement      |
| MQ-135       | General indoor air-quality sensing        |
| LDR          | Light-intensity measurement               |
| OLED Display | Local display of sensor readings          |
| Power Supply | Provides power to the system              |

## Proposed System Flow

```text
Environmental Sensors
        ↓
ESP32 Microcontroller
        ↓
Data Processing
       ↙ ↘
OLED     Wi-Fi
Display    ↓
        Remote Interface
```

## Week 1 Work

The Week 1 assessment focuses on:

* System requirements analysis
* Functional and non-functional requirements
* Hardware and software requirements
* Performance requirements
* Communication interfaces
* Power requirements
* Real-time constraints
* System architecture
* Block diagram design
* Component selection and design justification
* System working and data flow
* Limitations and future enhancements

## Project Status

**Current stage: Requirements Analysis and System Design**

This repository documents a proposed system architecture. Physical hardware construction, firmware development, sensor calibration, and real-world testing have not been completed as part of this Week 1 assessment.

## Future Scope

Possible future extensions include:

* Mobile application
* Cloud-based data storage
* Historical data visualization
* Environmental alerts
* Additional sensors
* Automated fan or lighting control
* Battery-powered operation
* Data analytics
* Machine-learning-based environmental prediction

## Documentation

The detailed Week 1 assessment report is available in the `docs` folder.

## Author

**Hritik Kumar Sharma**

B.Tech – CSE (AI/ML)
IILM University, Greater Noida
