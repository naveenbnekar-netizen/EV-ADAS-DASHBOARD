# EV-ADAS-DASHBOARD# 🚗 EV-ADAS Dashboard
### Real-Time Electric Vehicle Dashboard & ADAS Warning System

![GitHub](https://img.shields.io/badge/Language-C-blue)
![STM32](https://img.shields.io/badge/MCU-STM32F103C8T6-green)
![Python](https://img.shields.io/badge/Python-Dashboard-yellow)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

The **EV-ADAS Dashboard** is an Automotive Embedded Systems project developed during my internship. The project simulates an Electric Vehicle (EV) dashboard integrated with Advanced Driver Assistance System (ADAS) features using the **STM32F103C8T6 Blue Pill**, **PICSimLab**, and a **Python-based real-time dashboard**.

The firmware continuously monitors vehicle parameters, obstacle distances, battery status, motor temperature, and vehicle state while providing collision warnings, blind-spot detection, parking assistance, and fault management.

---

## 🎯 Objectives

- Develop a real-time EV Dashboard.
- Implement ADAS safety features.
- Design modular embedded firmware.
- Transmit live vehicle data over UART.
- Visualize data using a Python Dashboard.
- Simulate complete vehicle behavior using PICSimLab.

---

# 🛠 Hardware Used

- STM32F103C8T6 (Blue Pill)
- HC-SR04 Ultrasonic Sensors
- ST-Link V2
- PICSimLab Simulator

---

# 💻 Software Used

- STM32CubeIDE
- STM32 HAL Library
- CubeMX
- PICSimLab
- Python

---

# 🚀 Features

## EV Dashboard

- Real-time Speed Monitoring
- Battery State of Charge (SOC)
- Estimated Driving Range
- Motor Temperature
- Power Consumption
- Torque Calculation
- Drive Modes
  - ECO
  - NORMAL
  - SPORT
- Regenerative Braking

---

## ADAS Features

- Forward Collision Warning
- Collision Detection
- Blind Spot Detection
- Parking Assistance
- Time-To-Collision (TTC)
- Distance Measurement using HC-SR04
- Warning & Critical Alerts

---

## Safety Features

- Vehicle State Machine
- Fault Detection
- Over Temperature Protection
- Low Battery Protection
- Collision Fault Handling
- Alarm Priority Management
- Buzzer Alerts
- LED Warning Indicators

---

# 🧩 Firmware Modules

- `main.c`
- `ev_control.c`
- `adas.c`
- `fault.c`
- `ultrasonic.c`
- `uart_shell.c`

Each module is developed independently to improve code readability and maintainability.

---

# ⚙ Technologies Used

- Embedded C
- STM32 HAL Drivers
- UART Communication
- ADC
- GPIO
- Timers
- PWM
- Interrupts
- State Machine
- Modular Programming
- Python
- Matplotlib
- PySerial

---

# 📊 Python Dashboard

The Python Dashboard displays:

- Vehicle Speed
- Battery Percentage
- Estimated Range
- Motor Temperature
- Torque
- Power
- Drive Mode
- ADAS Bird-Eye View
- Blind Spot Indicators
- Collision Warnings
- Fault Alerts

---

# 🔄 System Workflow

```
Sensors
     │
     ▼
STM32 Firmware
     │
     ▼
UART Communication
     │
     ▼
Python Dashboard
     │
     ▼
Real-Time Vehicle Monitoring
```

---

# 🧪 Testing

The project includes testing for:

- Sensor Validation
- Distance Accuracy
- UART Communication
- Collision Detection
- Blind Spot Detection
- Fault Injection
- Drive Modes
- Regenerative Braking
- Dashboard Refresh
- Alarm Verification

---

# 📸 Project Demonstration

## Firmware

srcCod

## Dashboard

images/pythonDashboard.png

## PICSimLab Simulation

images/spareParts.png

---

# 🎥 Demo Video

demoVideo/demo.mp4

---

# 📈 Future Improvements

- CAN Bus Communication
- FreeRTOS Integration
- Real Hardware Deployment
- Mobile Dashboard
- GPS Integration
- OTA Updates
- Bluetooth Connectivity
- Cloud Data Logging

---

# 📚 What I Learned

During this internship project, I gained practical experience in:

- Automotive Embedded Systems
- STM32 Firmware Development
- Embedded C Programming
- UART Protocol Design
- Sensor Interfacing
- Timer & Interrupt Programming
- State Machine Design
- Fault Management
- ADAS Concepts
- Python Dashboard Development
- Modular Software Architecture

---

# 👨‍💻 Author

**Naveen Nekar**

Electronics & Communication Engineering Student

---

## ⭐ If you found this project useful, consider giving it a Star!