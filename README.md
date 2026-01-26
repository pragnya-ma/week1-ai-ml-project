# Air Quality Index (AQI) Prediction Using Machine Learning

## Overview
This project focuses on predicting Air Quality Index (AQI) values using machine learning techniques applied to real-world environmental and atmospheric data. Accurate AQI prediction is important for understanding air pollution trends and raising public health awareness.

The project follows a structured, step-by-step data science workflow, from data cleaning and exploration to model training, evaluation, and interpretation.

## Dataset
The dataset contains air quality and meteorological data collected across different locations in India.
It includes variables such as:
- Pollutant concentrations (PM2.5, PM10, NO2, SO2, CO, etc..)
- Weather parameters (temperature, humidity, wind speed, precipitation)
- Temporal features (date, time, seasonality indicators)
After preprocessing, missing values were handled and non-numeric inconsistencies were removed to ensure model compatibility.

## Data Preprocessing
Key preprocessing steps include:
- Conversion of numeric columns and datetime parsing
- Removal of columns with excessive missing values
- Median imputation for remaining numeric NaNs
- Feature selection to avoid target leakage and redundant variables
These steps ensured that the dataset was clean, consistent, and suitable for machine learning models.

## Models Used
The following regression models were implemented and evaluated:
-**Linear Regression**
-**Decision Tree Regressor**
Each model was trained using an 80-20 train-test split and evaluated using standard regression metrics.

## Evaluation Metrics
Model performance was assessed using:
-**Mean Absolute Error (MAE)** - to measure average prediction error.
-**R2 Score** - to measure the proportion of variance explained by the model.
These metrics provide a balanced understanding of prediction accuracy and model reliability.

## Results Summary
- Linear Regression provided a strong baseline with interpretable results.
- Decision Tree Regression captured non-linear relationships but required careful feature handling.
- Feature sensitivity analysis showed that certain pollutant variables significantly influenced predictions.
Overall, the models demonstrated that machine learning can effectively model AQI trends when proper preprocessing is applied.

## Interpretation and Ethical Considerations
- AQI predictions may be affected by sensor inaccuracies and regional data imbalance.
- Model outputs should be interpreted as **supporting indicators**, not exact real-time replacements.
- Ethical use requires transparency about limitations and uncertainty in predictions.

## Project Structure
week1/
|----data/
|----notebooks/
|----report/
   |___main.tex
|----scripts/
|----README.md

## How to Run
1. Clone the repository
2. Install required Python libraries ('pandas', 'numpy', 'scikit-learn')
3. Run the notebooks in order for preprocessing and model training
4. Compile 'main.tex' to generate the final report

## Author
**Pragnya M.A**
Grade 12 | Data Science and Climate Analytics Project 


   
























-
