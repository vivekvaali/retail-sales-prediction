# Retail Sales Prediction

## Project Overview
This project focuses on analysing Walmart's historical sales data and building a machine learning model to predict weekly sales across different stores and departments.

The project uses Python and machine learning techniques to understand sales patterns, identify important factors influencing sales predictions, and forecast weekly sales.

## Objectives
- Analyse historical Walmart sales data.
- Explore sales trends across stores, departments, and time periods.
- Understand the impact of holidays and store characteristics on sales.
- Build and evaluate machine learning models.
- Predict weekly sales for the provided test dataset.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset
The dataset is from the **Walmart Recruiting - Store Sales Forecasting** competition on Kaggle.

It includes:
- Historical weekly sales data.
- Store and department information.
- Store types and sizes.
- Holiday indicators.
- Weather and economic features.

## Project Workflow
1. Data Loading and Overview
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Engineering
5. Time-Based Train-Validation Split
6. Model Building
7. Model Evaluation and Comparison
8. Feature Importance Analysis
9. Test Data Preparation
10. Weekly Sales Prediction

## Machine Learning Models

Two regression models were implemented and evaluated.

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 14,541.72 | 20,892.09 | 0.0947 |
| Random Forest Regressor | 2,280.96 | 4,515.34 | 0.9577 |

The Random Forest Regressor achieved better validation performance than Linear Regression.

## Key Findings
- Sales varied across stores and departments.
- Store type and store size showed differences in average weekly sales.
- Average sales were higher during holiday
