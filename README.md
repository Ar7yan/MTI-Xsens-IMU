MTI Xsens IMU – KNN Sensor Evaluation

This project applies a K-Nearest Neighbors (KNN) regression model to evaluate and correct noisy sensor data from the MTI Xsens IMU. Clean and noise-induced datasets are analyzed, visualized, and used to train a multi-output model that predicts temperature, pressure, rotation, and magnetic field values.

🚀 Overview

Loads and preprocesses IMU datasets

Performs exploratory data analysis and visualizations

Trains a multi-output KNN regressor

Evaluates performance using MSE, MAE, and R²

Generates prediction plots

Saves the final trained model

🧠 Key Features

Noise vs clean data comparison

Correlation and distribution analysis

Multi-target regression

Actual vs predicted visualization

Exported KNN model for reuse

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Joblib

🎯 Applications

IMU noise correction

Robotics and drone stability

Sensor fusion

Real-time monitoring systems
