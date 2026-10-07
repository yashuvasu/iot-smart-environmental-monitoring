IoT-Based Smart Environmental Monitoring and Alert System: Week 1

This repository contains the Week 1 deliverables of a four-week Embedded Systems Internship. The project is an ESP32-based environmental monitoring node that measures temperature, humidity and a gas-based air-quality indication, shows the results on a local OLED display, raises an alert through an LED and buzzer when configurable thresholds are exceeded, and sends data over Wi-Fi to a conceptual remote dashboard. If Wi-Fi is unavailable, the node keeps monitoring and alerting locally.

Week 1 task: System Requirements Analysis and Block Diagram Design. The aim of this week is to plan the whole system before any firmware is written. The work covers the application and intended functionality, numbered functional and non-functional requirements, input and output specifications, communication interfaces (I2C, GPIO, ADC and Wi-Fi), power management, real-time design targets, hardware and software architecture, a detailed block diagram, a software flowchart, data flow, component selection and justification, fault handling, reliability and security considerations, and a requirement traceability matrix.

Proposed hardware: ESP32 microcontroller, DHT22 temperature/humidity sensor, MQ-135 gas sensor (used as a prototype air-quality indicator, not a calibrated analyser), 0.96-inch I2C OLED display, LED and buzzer, and a 5 V USB supply regulated to 3.3 V.

Contents
File	Description
Week1_Technical_Report_IoT_Environmental_Monitor.docx	Full Week 1 technical report
Figure1_Block_Diagram.png	Hardware block diagram with labelled interfaces
Figure2_Software_Flowchart.png	Start-up and monitoring-loop flowchart
Project status

This is a proposed and simulated design. No physical hardware has been built or tested, no firmware has been written, and no cloud service has been deployed. All timing, power and performance figures are design targets or datasheet-based estimates, not measurements.

Roadmap
Week 1: Requirements and architecture (this repository's current content)
Week 2: Firmware development and implementation
Week 3: Debugging and performance optimization
Week 4: System integration and final testing

The architecture and requirements produced in Week 1 form the foundation for all later weeks.

Author: pilla yashwanth | Yuva intern  | 07/10/2026
