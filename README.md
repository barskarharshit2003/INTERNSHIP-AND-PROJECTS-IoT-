# 🌐 INTERNSHIP & PROJECTS (IoT & Embedded Systems)

A collection of my internship and academic projects in Embedded Systems, IoT, and Edge AI — featuring real-time environmental monitoring, smart control systems, and on-device ML implementations. Includes multi-node ESP32/Arduino IoT networks, MQTT-based communication, PCB designs, TinyML anomaly detection, and system-level programming in C.

---

## 🚌 Project 1: IoT-Enabled Smart Bus & Car Monitoring System
**(SWACCH.IO Internship | June – July 2025)**  
**Tech Stack:** ESP32, ESP32-CAM, MQTT, EasyEDA, BME280, PMS7003, INA219, CW-019 Relay, GPS, Ngrok, HTML Dashboard  

A multi-node IoT architecture built to monitor **air quality, temperature, battery voltage, and GPS**, with centralized control and image-based fault detection.

### 🔧 Key Features
- **Distributed ESP32 Network:** 5 interconnected nodes using MQTT protocol for data sharing and system control.
- **Camera Node (ESP32-CAM):** Captures images periodically for visual fault/anomaly detection.
- **Custom PCB Design:** Designed in **EasyEDA** for efficient sensor-microcontroller interfacing and low-noise signal paths.
- **Centralized Monitoring Dashboard:** Deployed a real-time web dashboard (Ngrok-based) for **remote visualization** and control of all nodes.
- **Solar-Powered Car Module:** Integrated Arduino Uno R4 with solar charging and ignition control via MOSFET, connected to same dashboard.
- **Data Analytics:** Processed sensor data for early fault detection, power optimization, and risk management through data-driven decision logic.

### 🖼️ Project Media
<img width="1580" height="811" alt="image" src="https://github.com/user-attachments/assets/de7b4285-b752-4a22-9e94-bcf54811e1a2" />

Note: Due to Non-Disclosure Agreement (NDA) with the host organization, detailed circuit schematics and firmware code for this project cannot be publicly shared. However, system architecture diagrams and non-confidential visuals will be added for reference.

## 🌾 Project 2: Smart Agriculture System (IoT-based Irrigation)
**(Course Project under Prof. Santanu | May 2025)**  
**Tech Stack:** ESP32, DHT11, Soil Moisture Sensor, MQTT (broker.emqx.io), Python (logging & analysis), HTML Dashboard  

An intelligent irrigation system using IoT to automate watering decisions based on soil moisture and environmental data — enabling precision agriculture through embedded analytics.

### 🔧 Project Workflow
**Phase 1:** Simulated sensor models in Python for testing control logic.  
**Phase 2:** Embedded real-time control on **ESP32** (DHT + soil moisture + irrigation LED).  
**Phase 3:** Implemented **MQTT-based communication** for bidirectional data flow (ESP → Broker → Dashboard).  
**Phase 4:** Developed **web dashboard** with live plots and manual override feature.  
**Phase 5:** Added **local data logging (CSV export)** for performance analytics and dataset creation.

### 🧠 Highlights
- Built adaptive irrigation logic using real-time soil moisture and temperature thresholds.
- Designed MQTT-based data exchange for cloud communication and dashboard visualization.
- Processed collected data in Python for **trend analysis**, performance tracking, and **predictive irrigation control**.
- Created a reusable, modular codebase combining embedded firmware and Python data analytics.

### 🖼️ Project Media
1. Schematic 
<img width="468" height="355" alt="image" src="https://github.com/user-attachments/assets/589eaab5-7365-4796-bac0-89f38046d7d7" />

2. Dashboard
<img width="674" height="242" alt="image" src="https://github.com/user-attachments/assets/c2c65e4f-49e1-4b6e-ab9f-c2aae850584a" />

3. Analysis
<img width="224" height="472" alt="image" src="https://github.com/user-attachments/assets/8450337d-4fcd-437d-bef3-239c99211764" />
<img width="1028" height="586" alt="image" src="https://github.com/user-attachments/assets/fc8447d8-5f49-465f-bef5-67a7ba52f8e9" />


## 📊 Tech Domains Covered
- Embedded Systems (ESP32, Arduino, sensors, PCB design)
- IoT Protocols (MQTT, HTTP, Ngrok tunneling)
- Cloud & Edge Integration (real-time dashboards, TFLite)
- Data Analytics (Python-based fault detection & trend visualization)
- Sustainable Systems (solar energy management, low-power embedded design)

---

## 🧠 Future Scope
- Integration of **TinyML-based anomaly detection** for predictive maintenance.
- Expansion to **LoRa-based long-range IoT communication**.
- Unified multi-node dashboard for scalable environmental intelligence.

---

## 📎 Repository Structure
