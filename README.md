# Real-Time IoT Data Pipeline with Spark Streaming
**Course:** ICS 574 - Big Data Analytics
**Author:** Hilal Alghamdi (ID: 202512230)

## Project Overview
This project implements a complete **Real-Time IoT Data Pipeline** that ingests simulated sensor data, processes it using **Apache Spark Structured Streaming**, and visualizes it on a live dashboard. It was built entirely in Google Colab to demonstrate a scalable, zero-install Big Data architecture.

## Architecture
1. **Source Layer:** Python simulator generating JSON data for 3 sensors.
2. **Ingestion Layer:** File-based buffer acting as the message broker.
3. **Processing Layer:** Apache Spark Structured Streaming for real-time aggregation.
4. **Smart Layer:** Anomaly detection flagging critical temperatures (>30°C).
5. **Storage Layer:** Processed results archived to CSV.
6. **Visualization Layer:** Matplotlib live charts.

## Key Features
* **Real-Time Aggregation:** Calculates statistics dynamically.
* **Smart Anomaly Detection:** Logic to flag overheating sensors.
* **Visual Dashboard:** Instant health monitoring.

## How to Run
1. Open the `.ipynb` file in Google Colab.
2. Run the cells in sequential order (Steps 1 through 5).
