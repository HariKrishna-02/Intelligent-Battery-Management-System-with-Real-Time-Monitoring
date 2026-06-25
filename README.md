# Intelligent Battery Management System with Real-Time Monitoring
Designed an IoT-enabled Battery Management System using ESP32 for real-time monitoring of voltage, current, and temperature. Implemented battery protection features, State of Charge estimation, and a web dashboard for remote battery health monitoring.

# Intelligent Battery Management System (BMS) with Real-Time Monitoring

## Overview

The Intelligent Battery Management System (BMS) is an IoT-enabled battery monitoring and protection solution designed for lithium-ion battery packs. The system continuously monitors voltage, current, and temperature parameters, estimates State of Charge (SoC), performs cell balancing, and provides real-time battery health visualization through a web dashboard.

---

## Components Used

- ESP32 Development Board
- ACS712 Current Sensor
- DS18B20 Temperature Sensor
- Lithium-Ion Battery Pack
- Voltage Divider Circuit
- MOSFET Balancing Circuit
- Resistors & Capacitors
- Laptop (Web Server)
- WiFi Network

---

## Working

### Step 1: Data Acquisition
ESP32 reads battery voltage, current, and temperature from connected sensors.

### Step 2: Battery Analysis
Embedded firmware processes sensor data and calculates battery parameters such as State of Charge (SoC).

### Step 3: Protection Mechanism
The system continuously monitors battery conditions and detects:

- Over-voltage
- Under-voltage
- Over-current
- Over-temperature

### Step 4: Cell Balancing
MOSFET-based balancing circuitry maintains uniform voltage levels across battery cells.

### Step 5: Data Transmission
ESP32 sends real-time battery data to a laptop-based web server using WiFi communication through HTTP requests or MQTT protocols.

### Step 6: Dashboard Processing
The web application receives, stores, and processes battery data for visualization.

### Step 7: Real-Time Monitoring
Users can monitor battery health, voltage, current, temperature, alerts, and State of Charge through a browser-based dashboard.

---

## Technologies Used

### Hardware
- ESP32
- ACS712 Current Sensor
- DS18B20 Temperature Sensor
- MOSFET Balancing Circuit
- Lithium-Ion Battery Pack

### Firmware
- Embedded C
- Arduino IDE

### Web Technologies
- HTML
- CSS
- JavaScript

### Backend
- Python Flask
- SQLite Database

### Communication
- WiFi
- HTTP API / MQTT

---

## Output

- Real-Time Battery Monitoring
- State of Charge (SoC) Estimation
- Battery Protection System
- Cell Balancing Functionality
- Live Dashboard Visualization
- Historical Data Logging
- Alert Notification System

---

## Future Enhancements

- State of Health (SoH) Estimation
- Predictive Maintenance using Machine Learning
- Mobile Application Integration
- Cloud-Based Data Storage
- Advanced Battery Analytics

---

## Credits

**Created By:** JP HariKrishna Raj

**Project:** Intelligent Battery Management System (BMS) with Real-Time Monitoring

**Domain:** Embedded Systems | IoT | Electric Vehicle Technology | Battery Management Systems

---
