# Intelligent Campus Lighting System Using IoT and AI

## About the Project
The Intelligent Campus Lighting System is an IoT-based project designed to make campus lighting more energy-efficient using human presence detection and ambient light sensing.

The system uses an ESP32 microcontroller to process sensor inputs and control LED brightness. IoT monitoring and AI-based occupancy analytics are planned software enhancements.

## Objectives
- Automate campus lighting using an ESP32.
- Detect human presence using a PIR motion sensor.
- Sense ambient light using an LDR.
- Adjust LED brightness according to occupancy.
- Explore IoT monitoring and AI-based occupancy prediction.

## Hardware Components
- ESP32 development board
- HC-SR501 PIR motion sensor
- LDR sensor
- ACS712 current sensor
- MOSFET driver
- 12V LED strip

## Working Principle
1. The PIR sensor detects human movement.
2. The LDR senses the surrounding light level.
3. The ESP32 processes sensor readings and controls the LED brightness according to the programmed logic.
4. The planned lighting logic uses 100% brightness when a person is detected and approximately 10% safety lighting when no person is detected.

## Technologies
- ESP32
- Arduino IDE
- Embedded C/C++
- IoT and Wi-Fi
- Sensor interfacing

## Planned Enhancements
- Wi-Fi-based monitoring dashboard
- Occupancy heatmap analytics
- AI-based occupancy prediction using historical sensor data
- Current monitoring and lighting fault alerts using ACS712

## Project Progress
**Hardware:** Completed.

**Software and AI:** Under development / planned.

## Repository Structure
- `images/` — Hardware photographs and circuit diagrams
- `src/` — ESP32 source code
- `dashboard/` — IoT dashboard files
- `documentation/` — Project report and technical documentation

## Future Scope
The project can be extended to multiple campus lighting zones with centralized monitoring, occupancy analytics, and intelligent energy management.
