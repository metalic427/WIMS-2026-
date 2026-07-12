# WIMS-2026: Microfluidic Water Quality Testing System with IoT

An IoT-enabled microfluidic system for real-time water quality testing. The system uses a color sensor within a microfluidic chip to analyze water samples, transmits data via an ESP32 with GSM module, and displays results on a cloud-based dashboard (AWS HMI) for real-time remote monitoring.

## 🎯 Overview

This project combines microfluidics and IoT to create a low-cost, portable water quality testing solution. A microfluidic chip processes small water samples and measures color-based indicators of water quality. Sensor data is sent through an ESP32 microcontroller with GSM connectivity to a cloud dashboard built on AWS, enabling remote, real-time monitoring from anywhere.

## ⚙️ How It Works

1. **Sample Input** – Water sample flows through the microfluidic chip
2. **Sensing** – A color sensor detects changes indicating water quality parameters
3. **Data Transmission** – ESP32 + GSM module sends sensor readings to the cloud
4. **Cloud Dashboard** – AWS-based HMI displays real-time data for monitoring
5. **AI Analysis (Planned)** – Future integration will use AI to interpret sensor data and provide automated water quality predictions/alerts

## 🧩 Components

- Microfluidic chip/sensor (color-based detection)
- ESP32 microcontroller
- GSM module (for remote data transmission)
- Cloud dashboard — AWS HMI
  
## 📁 Repository Structure

- `CAD& Fabrication/` – CAD models and fabrication files
  - `Assembley/` – Assembly models
  - `Dylon/`, `Elson/`, `Rubin/` – Design files contributed by team members
  - `SLD/` – SolidWorks files
  - `STL/` – 3D printable files
  - `Media/` – Images/renders
  - `Pump/` – Pump component designs

## 🚧 Project Status

🔨 In development — currently working on integrating AI-based analysis of sensor data for automated water quality assessment.

## 📌 Roadmap

- [x] Microfluidic chip design
- [x] Sensor + ESP32/GSM integration
- [x] Cloud dashboard (AWS)
- [ ] AI model for water quality prediction
- [ ] Field testing

## 👤 Author

metalic427
