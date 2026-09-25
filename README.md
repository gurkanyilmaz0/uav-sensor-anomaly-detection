# 🚁 UAV Telemetry Sensor Anomaly Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

This repository contains a Machine Learning pipeline designed for **Unmanned Aerial Vehicles (UAVs) and autonomous platforms** to detect sensor and telemetry anomalies before critical hardware failures occur. 

By analyzing real-time-like telemetry data (such as temperature, torque, and RPM), this project aims to implement a **Predictive Maintenance** architecture, which is a crucial safety standard in the defense and aerospace industries.sss

## 📌 Project Overview
In autonomous systems, sudden hardware failures (e.g., motor stalling or overheating) can lead to catastrophic accidents. This project utilizes historical sensor data to train classification models capable of identifying abnormal patterns that precede a failure.

* **Algorithms Used:** Logistic Regression & Random Forest Classifier
* **Dataset:** UCI AI4I Predictive Maintenance Dataset (adapted for UAV motor/telemetry simulation)
* **Key Telemetry Parameters Analyzed:**
  * Air Temperature & Process (Chassis) Temperature
  * Rotational Speed (RPM)
  * Torque (Nm)
  * Tool Wear (Operating time)

## 🚀 Key Features
* **Exploratory Data Analysis (EDA):** Identifies correlations between torque peaks and RPM drops which usually indicate motor stress.
* **Feature Engineering:** Simulates realistic flight conditions by normalizing raw sensor data.
* **High Accuracy Classification:** Uses Ensemble methods (Random Forest) to achieve high precision in detecting true anomalies while minimizing false positives (crucial for aviation).

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/gurkanyilmaz0/uav-sensor-anomaly-detection.git
   cd uav-sensor-anomaly-detection
