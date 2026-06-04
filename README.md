# Air Quality and Respiratory Health Prediction

Machine learning project for predicting respiratory-related hospital admissions using air quality and environmental indicators.

## Project Overview

This project predicts respiratory-related hospital admissions based on air quality indicators, weather variables, location information, population density, and hospital capacity.

The target variable is `hospital_admissions`, which is numerical, so this project is treated as a regression problem.

## Dataset

The dataset contains the following groups of variables:

- Air quality indicators: `aqi`, `pm2_5`, `pm10`, `no2`, `o3`
- Weather variables: `temperature`, `humidity`
- Location variables: `city`, `population_density`
- Healthcare capacity variable: `hospital_capacity`
- Target variable: `hospital_admissions`

Note: This dataset is used for educational machine learning purposes. The date range extends far into the future, so dates should not be interpreted as real long-term historical hospital records.

## Project Structure

```text
air-quality-health-prediction/
|-- README.md
|-- requirements.txt
|-- data/
<<<<<<< HEAD
|   |-- air_quality_health_dataset.csv
|   |-- air_quality_health_ml_ready.csv
|-- notebooks/
|   |-- 01_Class2_Data_Cleaning_EDA_ML_Preparation.ipynb
|   |-- 02_Class3_Modeling_Evaluation.ipynb
|-- outputs/
```

## How to Run

1. Install dependencies from `requirements.txt`.
2. Open the notebooks in the `notebooks/` folder.
3. Run `01_Class2_Data_Cleaning_EDA_ML_Preparation.ipynb` first to prepare the ML-ready dataset.
4. Run `02_Class3_Modeling_Evaluation.ipynb` to train and evaluate the models.
=======
|-- notebooks/
|-- outputs/
>>>>>>> d4ee9004d33441657d5f99bdeb724f236b585070
