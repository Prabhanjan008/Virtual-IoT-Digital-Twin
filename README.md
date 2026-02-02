# Virtual IoT Fleet & Digital Twin Dashboard

## Overview
This project demonstrates a Virtual IoT Device Simulation and Digital Twin Dashboard using Python and Streamlit. It simulates real-time IoT sensor data and visualizes it through an interactive dashboard without using physical IoT devices.

## Objective
- Simulate IoT sensor telemetry data
- Visualize real-time temperature and humidity
- Demonstrate Digital Twin concept
- Perform anomaly detection using stress testing

## Tools and Technologies
- Python
- Streamlit
- Pandas

## Telemetry Parameters
| Parameter | Type | Description |
|---------|------|-------------|
| Temperature | Float (°C) | Environmental temperature |
| Humidity | Integer (%) | Moisture in air |
| Status | String | OK / Warning / Critical |

## Dashboard Features
- Live temperature display
- Live humidity display
- System status indicator
- Real-time line graph visualization
- Stress test simulation

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
