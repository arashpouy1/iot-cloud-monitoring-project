# iot-cloud-monitoring-project
End-to-end IoT and cloud infrastructure project involving Linux systems, AWS services, and sensor-based monitoring.
# IoT Cloud Monitoring Project

University Project – QUT Advanced Networks  
Technologies: Raspberry Pi, AWS EC2, AWS RDS, Python, MQTT, Linux, Bluetooth, IoT Sensors

---

## Project Overview

This project involved the design and implementation of an IoT-based plant monitoring system for automated irrigation and environmental monitoring.

The system collected soil moisture, temperature, humidity, and light data using sensors connected to a Teensy microcontroller. Sensor data was transmitted to a Raspberry Pi for processing and then uploaded to AWS cloud infrastructure for monitoring, storage, and analysis.

The project demonstrated foundational concepts in cloud infrastructure, Linux systems, networking, IoT integration, and distributed data processing.

---

## Objectives

- Monitor soil moisture levels for potential irrigation automation
- Measure environmental conditions including temperature, humidity, and light
- Process and transmit sensor data through multiple system layers
- Upload and store collected data in cloud infrastructure
- Provide web-based monitoring access
- Trigger notifications when thresholds were exceeded
- Explore data analysis and visualization concepts

---

# System Architecture

The solution was implemented across three logical tiers.

## Tier 1 – Sensing Layer

Sensors connected to a Teensy microcontroller were used to collect environmental data.

### Hardware Components
- Soil Moisture Sensor
- DHT11 Temperature & Humidity Sensor
- Photoresistor
- Teensy Microcontroller
- HC-05 Bluetooth Module

The collected sensor data was transmitted to the Raspberry Pi using Bluetooth communication.

---

## Tier 2 – Data Processing Layer

A Raspberry Pi was used as the intermediary processing system.

### Functions Performed
- Receive sensor data through Bluetooth
- Process collected sensor information using Python scripts
- Prepare data for cloud transmission
- Send processed data to AWS infrastructure

### Technologies
- Raspberry Pi
- Linux
- Python
- Bluetooth communication

---

## Tier 3 – Cloud Analytics & Visualization Layer

AWS cloud infrastructure was used for data storage, monitoring, and visualization.

### Cloud Components
- AWS EC2 Instance
- AWS-hosted Database (RDS/MySQL)
- MQTT Messaging (Mosquitto)
- Web-based Monitoring Interface

### Functions
- Store and manage collected sensor data
- Publish processed data for monitoring
- Trigger notification mechanisms when thresholds were exceeded
- Support historical data visualization and analysis

---

# Technologies Used

| Area | Technologies |
|---|---|
| Cloud Infrastructure | AWS EC2, AWS RDS |
| Operating Systems | Linux, Raspberry Pi OS |
| Programming | Python |
| Messaging | MQTT / Mosquitto |
| Networking | Bluetooth, WiFi |
| Hardware | Raspberry Pi, Teensy Microcontroller |
| Sensors | Soil Moisture, DHT11, Photoresistor |

---

# My Responsibilities

My primary contributions focused on Tier 1 and Tier 2 of the project, including:

- Assisting with AWS EC2 instance setup and configuration
- Installing required client and server software components
- Supporting Raspberry Pi integration and connectivity
- Assisting with infrastructure setup for cloud-based monitoring
- Contributing to end-to-end system integration and testing

---

# Key Skills Demonstrated

- Linux systems exposure using Raspberry Pi
- Cloud infrastructure fundamentals using AWS
- Python scripting for data processing
- Networking and communication protocols
- Infrastructure integration across multiple system layers
- IoT systems architecture concepts
- Troubleshooting and system testing

---

# Key Learnings

This project provided practical exposure to:
- Cloud-hosted infrastructure concepts
- Linux-based systems administration
- IoT device communication and integration
- Distributed monitoring systems
- End-to-end data processing workflows
- Infrastructure troubleshooting and testing

It also strengthened understanding of how cloud services, networking, and embedded systems can be integrated into a complete operational solution.

---

# Disclaimer

This repository is intended to showcase the architecture, technologies, and learning outcomes of a university networking and infrastructure project completed as part of postgraduate studies at Queensland University of Technology (QUT).

Some original project files and configurations are not included.
