# Smart Home Energy Management Using ML Algo
### 🏠 Smart Home IoT: Load Forecasting with EDA, ARIMA & LSTM

This repository contains a self-learning project focused on **predicting smart home energy load** using various time series modeling techniques, including **Exploratory Data Analysis (EDA)**, **ARIMA**, and **LSTM**.

### 📌 Project Overview

With the increasing penetration of IoT devices in smart homes, energy consumption data from appliances can be used to predict future load and optimize energy usage. This project uses time series data of household appliance usage and builds models to forecast electrical load.

## 📊 Features

- Time Series Forecasting with:
  - 📈 **ARIMA** (Auto-Regressive Integrated Moving Average)
  - 🔁 **LSTM** (Long Short-Term Memory networks)
- 📉 Data pre-processing and transformation for time series modeling
- 🧪 **Exploratory Data Analysis (EDA)** for visual and statistical insights
- ✅ Model training, evaluation, and saving using Python
## 🧠 Model Details
Model file: my_model.pkl

Input data: Time series data from various household appliances (e.g., AC, heater, lights)

Target variable: Electrical load in watts/kW

Libraries used: pandas, matplotlib, seaborn, statsmodels, tensorflow/keras

The model expects time series data in a processed format, ideally as a DataFrame with datetime index and appliance load columns.

## 📈 Sample Plots (from EDA)
Load trends over time
Daily/weekly consumption patterns
Appliance-wise usage comparison

## ✅ Goals
Understand time series modeling using real-world IoT data
Compare classical (ARIMA) vs deep learning (LSTM) performance
Build a lightweight forecasting model for deployment in smart systems

## 📦 requirements.txt
You can create this file to install dependencies in one command:

numpy
pandas
matplotlib
seaborn
scikit-learn
statsmodels
tensorflow
keras

## 🧪 Future Work
Real-time prediction via API
Integration with home automation systems
Make proper Hardware Device

## 🙋‍♂️ Author
Puneet Sharma
Self-learning project for exploring time series forecasting in smart home IoT systems.



