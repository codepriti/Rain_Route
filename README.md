
# 🌧️ RainRoute – Global Weather Prediction

### One World. Every Location. Smarter Rainfall Insights.

## 1. Project Overview

RainRoute is a weather data analysis and machine learning project
that collects historical weather information from different
locations around the world and predicts next-hour rainfall.

The project aims to make weather information easier to analyse
and understand using data science and machine learning.

## 2. Problem Statement

Rainfall patterns differ across locations and weather conditions.
Analysing historical weather data can help identify rainfall
patterns and build predictive models.

## 3. Project Objectives

- Collect historical weather data from multiple global locations.
- Clean and analyse weather datasets.
- Identify rainfall patterns and trends.
- Apply machine learning for next-hour rainfall prediction.
- Evaluate model performance using standard metrics.

## 4. Dataset Information

- Data Source: Open-Meteo Historical Weather API
- Total Records: 105,264
- Locations: 6
- Countries: 5
- Period: January 2024 – December 2025
- Data Frequency: Hourly

### Locations

- Nalasopara, India
- Mira Road, India
- London, United Kingdom
- New York, USA
- Tokyo, Japan
- Sydney, Australia

## 5. Weather Features

- Temperature
- Relative Humidity
- Precipitation
- Rainfall
- Wind Speed
- Atmospheric Pressure

## 6. Data Science Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Feature Importance Analysis

## 7. Machine Learning Model

Algorithm: Random Forest Regressor

Prediction Target: Next-hour rainfall (mm)

Evaluation Metrics:
- MAE
- MSE
- RMSE
- R² Score

## 8. Model Results

The Random Forest model achieved better overall
performance than the mean-based baseline model
on the chronological test dataset.

## 9. Feature Importance

The most important feature in the trained model
was previous-hour rainfall.

## 10. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Open-Meteo API

## 11. Current Project Status

Completed:
- Historical weather data collection
- Data analysis and visualization
- Feature engineering
- Next-hour rainfall prediction model
- Model evaluation

Future Development:
- Live weather integration
- Global location search
- Interactive weather map
- Waterlogging reports and risk analysis
- Web application using HTML, CSS, JavaScript and Flask

## 12. Important Note

This version predicts next-hour rainfall using historical
weather data. It does not yet provide operational live
forecasting or validated waterlogging predictions.

## 13. Author

RainRoute – Global Weather Prediction
