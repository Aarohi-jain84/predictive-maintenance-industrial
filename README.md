## Predictive Maintenance Forecast

This project predicts the health and potential failure of industrial equipment using sensor-based time series data. It compares XGBoost (for feature-based modeling) and LSTM (for deep sequence modeling).

## Features

Sensor time-series preprocessing

Feature extraction for traditional ML models

LSTM-based sequence prediction

Failure prediction or RUL (Remaining Useful Life) estimation

Streamlit-based interactive dashboard

## Getting Started

## Prerequisites

Make sure you have Python 3.x installed along with the following libraries:

pip install pandas numpy scikit-learn xgboost keras tensorflow seaborn matplotlib streamlit

## How to Run

Clone this repository.

Open and run the Jupyter notebook file:
maintenance_modeling.ipynb


## Dataset

The dataset (sensor_data.csv) contains multivariate time series data from equipment sensors, with labels for machine failure or remaining useful life (RUL).

Example columns:

sensor1, sensor2, ..., sensorN

timestamp

machine_id

failure_label or RUL

## Project Structure

predictive-maintenance-forecast/
├── maintenance_modeling.ipynb — Model training and evaluation notebook
├── dashboard.py — Streamlit app for visualization
├── sensor_data.csv — Time-series dataset
├── README.md — Project documentation (this file)

## Author

Aarohi Jain
B.Tech Student - Robotics & AI
Manav Rachna University
Email: aarohi.jain.2007@gmail.com

## License
This project is open source and available under the MIT License.
