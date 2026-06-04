# Air Quality and Respiratory Health Prediction

Machine learning project for predicting respiratory-related hospital admissions using air quality and environmental indicators.

## Project Overview

This project aims to predict respiratory-related hospital admissions based on air quality indicators, weather variables, location information, population density, and hospital capacity.

The target variable is `hospital_admissions`, which represents the number of respiratory-related hospital admissions. Since the target variable is numerical, this project is treated as a regression problem.

## Dataset

The dataset contains the following groups of variables:

- Air quality indicators: `aqi`, `pm2_5`, `pm10`, `no2`, `o3`
- Weather variables: `temperature`, `humidity`
- Location variables: `city`, `population_density`
- Healthcare capacity variable: `hospital_capacity`
- Target variable: `hospital_admissions`

## Project Structure

```text
air-quality-health-prediction/
├── README.md
├── requirements.txt
├── data/
├── notebooks/
└── outputs/
