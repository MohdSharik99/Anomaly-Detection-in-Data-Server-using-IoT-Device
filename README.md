# Anomaly Detection in Data Servers Using IoT Devices

This project focuses on predicting energy consumption and power usage in data servers by analyzing data collected from IoT sensors. It employs advanced machine learning models to forecast future values and detect anomalies, ensuring operational efficiency and system reliability.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [System Design](#system-design)
- [Usage](#usage)
- [EDA](#eda)
- [Energy Prediction](#energy-prediction)
- [Power Prediction](#power-prediction)
- [Anomaly Detection](#anomaly-detection)
- [Dashboard Visualization](#dashboard-visualization)
- [Authors](#authors)
- [References](#references)

---

## Introduction

In modern data centers, monitoring energy and power consumption is crucial for maintaining operational efficiency and preventing system failures. This project leverages IoT sensor data and machine learning techniques to predict energy and power usage, as well as detect anomalies that may indicate potential issues.

By utilizing real-time and historical sensor data, the system applies predictive models such as LSTM, Random Forest, XGBoost, and ARIMA to forecast energy consumption accurately. Additionally, anomaly detection models track these forecasts to identify deviations from normal patterns, enabling early warnings and proactive interventions.

The solution is designed for applications in *Industrial IoT (IIoT), **energy management, and **environmental monitoring. It can be extended to **smart city projects* for energy optimization, predictive maintenance, and monitoring environmental conditions in urban infrastructure.

---

## System Design

The following designed system tracks power and energy usage based on sensor readings, predictive analysis, and anomaly detection.
**Data Collection:** Real-time data is collected by sensors and sent wirelessly to a database.
**Data Processing:** Live and historical data are cleaned and preprocessed for uniformity.
**Model Prediction:** Predictions are made on power and energy usage patterns by machine learning models.
**Anomaly Detection:** The system detects unusual patterns and sends alerts for anomalies.
**Dashboard Visualization:** Users track data, forecasts, and anomalies through an interactive dashboard.
**System Feedback & Fixes:** Users take corrective measures based on insights to maintain optimal performance.

Key Benefits:
- Real-time monitoring for ongoing monitoring.
- AI-based forecasts improve decision-making.
- Automated anomaly detection avoids failures.
- Dashboard insights enhance transparency.
This system provides effective monitoring and predictive maintenance for optimal energy consumption.

![image](https://github.com/user-attachments/assets/9d7c8eb8-ccb1-41be-bfb4-1f1aba53d179)

---

## Features

- **Energy Consumption Forecasting**: Predicts future energy usage based on historical data.
- **Power Usage Prediction**: Estimates power consumption trends to aid in capacity planning.
- **Anomaly Detection**: Identifies deviations from normal patterns to preemptively address potential problems.
- **Interactive Dashboard**: Visualizes predictions and anomalies using a Tableau dashboard for intuitive analysis.

---

## Installation

To set up and run this project, follow the steps below:

```bash
Use any of the following links to clone the repository to your local system.
- HTTPS: git clone https://github.com/MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device.git
- SSH: git clone git@github.com:MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device.git
```

---

## Usage

Follow the below steps one after the other to understand how to execute this project.

- Dataset is available at [this page](https://www.kaggle.com/datasets/mohdsharik/sensor-sourse-data).
- Original dataset information is available [here](https://ieee-dataport.org/open-access/data-server-energy-consumption-dataset).

### EDA
- Download the [EDA file](https://github.com/MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device/blob/main/iot-sensor-data-eda/iot-sensor-data-eda.ipynb). 
- Open a new Jupyter notebook in Kaggle and upload the downloaded file into it.
- Execute the file one cell after the other.

### Energy Prediction
- Download the cleaned dataset from [here](https://github.com/MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device/blob/main/datasets/sensor_df10m_final.csv).
- Download the [Energy Prediction code file](https://github.com/MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device/blob/main/energy-prediction/Energy_Prediction_using_ARIMA.ipynb).
- Open a new Colab notebook. Upload the downloaded `sensor_df10m_final.csv` file into and execute all the steps.

### Power Prediction
- Download [Power Prediction code file](https://github.com/MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device/blob/main/power-prediction-and-anomaly-detection/Power-prediction-model.ipynb).
- Open a new Jupyter notebook in Kaggle and upload the downloaded file into it. 
- Execute the file one cell after the other.

### Anomaly Detection:
- Download [Anomaly Detection code file](https://github.com/MohdSharik99/Anomaly-Detection-in-Data-Server-using-IoT-Device/blob/main/power-prediction-and-anomaly-detection/Anomaly-detection-model.ipynb).
- Open a new Jupyter notebook in Kaggle and upload the downloaded file into it. 
- Execute the file one cell after the other.

---

## Dashboard Visualization
- The dashboard is accessible from [here](https://public.tableau.com/app/profile/mohd.sharik/viz/Power-EnergyDashboard/Dashboard1?publish=yes).

---

## Authors

| Author            | Contact Details       |
|-------------------|-----------------------|
| Ravi Teja Kothuru | rkothuru@sandiego.edu |
| Shruthi AK        | sak@sandiego.edu      |
| Mohd Sharik       | msharik@sandiego.edu  |

---

## References

1. Estrada, R., Asanza, V., Torres, D., Bazurto, A., & Valeriano, I. (2022). Learning-based Energy Consumption Prediction. Procedia Computer Science, 203, 272-279, https://doi.org/10.1016/j.procs.2022.07.035.  
