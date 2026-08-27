# Stochastic-Multi-Sensor-Simulator
A Stochastic Multi-Sensor Simulator utilizing an ESP32, physical telemetry hardware, and a local Python motor dashboard for real-time data acquisition.

---

## Project Overview
This project demonstrates mulit-sensor data acquisition and anomaly detection pipeline. A motorized rotating shaft spins custom slotted discs through LM393 Optical Sensors, generating stochastic pulses that are then transformed into an interactive dashboard consisting of analog and digital signals, monte carlo simulations, 3d plot and activity maps.

---

## Hardware & Rig Demonstration
>**NOTE:** *The video playback is set to 2x speed to be ample to be uploaded within github's 25mb file limit

View this demonstration under the '0827 (1)(1).mp4' section of this repository

---

## Features
* **Multi-Channel Telemetry** Real-Time analog pulse monitoring across three sensors
* **Automated Data Processing** Python script to obtain and filter data from ESP32
* **Interactive Dashboard** Visualisation of data in the form of Plotly Python Graphs
* **Monte Carlo Simulation** Runs stochastic probabilities to determine the most probable sensor outcome

---

## Written Report
* **Technical Write-up** Detailed documentation of system architecture and validation
* **Hardware Analysis** Documentation of the integration between ESP32 Microcontroller, Sensors and Motor
* **Data Analysis** Breaks down the findings of the telemetry system including noise filtration method and significance of monte carlo outputs
* **Visualisation** Thorough view through graphical visualisation, the physical rig structure and the circuitry feeding the project

View this document under 'ss.docx'

---

## Scripts
* **'esp32_firmware'** ESP32 C++ firmware consisting of handling data collection and storage as well as serial output
* **'python_dashboard'** Python Script for Data Processing, Statistical Analysis and Plotly Visualisation

---
