# Driver Behavior Analysis using LSTM

## Overview
This project focuses on analyzing driver behavior using time-series vehicle sensor data. The objective is to understand normal driving patterns and identify abnormal or unsafe behavior using data analysis and deep learning techniques.

## Problem Statement
Modern vehicles generate large volumes of sequential sensor data such as speed, acceleration, and yaw rate. Analyzing this data helps in improving road safety, monitoring driver performance, and enabling predictive analytics by detecting abnormal driving patterns.

## Dataset
The dataset consists of time-series vehicle data including:
- Speed
- Acceleration
- Yaw Rate

The data required preprocessing and outlier handling before model training.

## Methodology
1. Performed data cleaning and preprocessing using Pandas and NumPy.
2. Identified and handled outliers using statistical techniques.
3. Conducted exploratory data analysis and visualized trends using Matplotlib.
4. Built and trained an LSTM model to learn normal driving behavior from sequential data.
5. Used reconstruction error to detect deviations from normal driving patterns.

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib  
- TensorFlow / Keras  
- Google Colab  

## Results
The LSTM model successfully captured temporal patterns in the data and helped identify abnormal driving behavior, demonstrating the effectiveness of deep learning for time-series anomaly detection.

## Conclusion
This project demonstrates how LSTM-based models can be applied to real-world vehicle sensor data for analyzing driver behavior and detecting unsafe driving patterns.
