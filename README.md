# Air Quality and Respiratory Health Prediction

Machine learning project for predicting respiratory-related hospital admissions using air quality, environmental, healthcare, and time-related indicators.

## Project Overview

This project predicts respiratory-related hospital admissions based on air quality indicators, weather variables, location information, population density, and hospital capacity.

The target variable is `hospital_admissions`, which is numerical. Therefore, this project is treated as a regression problem.

The main goal of this project is to build a complete machine learning workflow that can support public health planning by identifying important factors related to respiratory-related hospital admissions.

## Dataset

The dataset contains the following groups of variables:

- Air quality indicators: `aqi`, `pm2_5`, `pm10`, `no2`, `o3`
- Weather variables: `temperature`, `humidity`
- Location variables: `city`, `population_density`
- Healthcare capacity variable: `hospital_capacity`
- Time-related variables: `year`, `month`, `day`, `day_of_week`, `quarter`, `is_weekend`
- Target variable: `hospital_admissions`

Note: This dataset is used for educational machine learning purposes. The date range extends far into the future, so dates should not be interpreted as real long-term historical hospital records.

## Project Structure

```text
air-quality-health-prediction/
|-- README.md
|-- requirements.txt
|-- data/
|   |-- air_quality_health_dataset.csv
|   |-- air_quality_health_ml_ready.csv
|-- notebooks/
|   |-- 01_Class2_Data_Cleaning_EDA_ML_Preparation.ipynb
|   |-- 02_Class3_Modeling_Evaluation.ipynb
|   |-- 03_Class4_Publishing_and_Feedback.ipynb
|-- outputs/
