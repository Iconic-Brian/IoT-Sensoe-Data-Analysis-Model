# IoT-Sensor-Data-Analysis-Model
Introduction

This README file provides an overview and usage instructions for four different models used to analyze IoT sensor data. Each model serves a unique purpose and employs specific algorithms and libraries to process and make predictions based on sensor data.

Model 1 (LSTM)
Overview

Objective: To predict the future temperature readings.
Algorithm Used: LSTM (Long Short-Term Memory) networks.
Language: Python.
Libraries: pandas, numpy, matplotlib, scikit-learn, tensorflow, tsfresh.
Usage

Install the required libraries if not already installed: pip install pandas numpy matplotlib scikit-learn tensorflow tsfresh.
Resample the data by one-minute intervals because it is scattered.
Apply Feature extraction, Feature selection, and Windowing as preprocessing steps.
Run the script: python LSTM_sensor.py.
Results

The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 0.1138.
Model 2 (XGBoost)
Overview

Objective: To predict the future temperature readings with the help of gradient boosting technique.
Algorithm Used: XGBoost.
Language: Python.
Libraries: pandas, numpy, matplotlib, scikit-learn, xgboost, LabelEncoder, hyperopt.
Usage

Install the required libraries if not already installed: pip install pandas numpy matplotlib scikit-learn xgboost.
Resample the data by one-minute intervals because it is scattered.
Run the script: python XGBoost_sensor.py.
Results

The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 2.8591.
Model 3 (Prophet)
Overview

Objective: To predict the future temperature readings with the help of prophet developed by Facebook.
Algorithm Used: Prophet.
Language: Python.
Libraries: pandas, numpy, matplotlib, prophet.
Usage

Install the required libraries if not already installed: pip install pandas numpy matplotlib prophet.
Resample the data by one-minute intervals because it is scattered.
Run the script: python Prophet_sensor.py.
Results

The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 0.5824.
Model 4 (ARIMA)
Overview

Objective: To predict the future temperature readings with the help of moving average.
Algorithm Used: ARIMA (AutoRegressive Integrated Moving Average).
Language: Python.
Libraries: pandas, numpy, matplotlib, ARIMA.
Usage

Install the required libraries if not already installed: pip install pandas numpy matplotlib ARIMA.
Resample the data by one-minute intervals because it is scattered.
Run the script: python ARIMA_sensor.py.
Results

The Root Mean Squared Error (RMSE) for the acutal temp readings and forecasted temp readings: 1.1409.
