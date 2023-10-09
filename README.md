# Retail Sales Prediction - Rossmann

![image](https://github.com/iamanantalok/Retail-Sales-Prediction-Rossmann/assets/117917485/9661f2a8-bb0a-48ab-9ce1-994abdaae076)


Rossmann operates over 3,000 drug stores in 7 European countries. This repository presents a comprehensive analysis and prediction model for Rossmann's daily sales, aiming to assist store managers in forecasting sales up to six weeks in advance. Store sales are influenced by a multitude of factors, including promotions, competition, holidays, seasonality, and location. With individual managers predicting sales based on unique circumstances, this project seeks to enhance the accuracy and consistency of these predictions.

## Dataset

The dataset consists of two CSV files:

1. `rossmann_store_data.csv`: Sales data per day for each store.
2. `store.csv`: Information about each store.

## Business Problem

Rossmann needs to predict daily sales across its numerous stores in multiple European countries. Accurate sales predictions are crucial for effective store management, inventory planning, and resource allocation.

## Solution Strategy

### Step 01: Know Your Data
- Performed initial data exploration using `info()`, `head()`, `tail()`, and identified missing values.
- Removed duplicates and handled missing data.

### Step 02: Understand Your Variables
- Examined the uniqueness and data types of variables.
- Addressed any irregularities in the dataset.
- Described key variables to gain insights.

### Step 03: Data Wrangling & Data Visualization
- Explored the data to understand the impact of variables on model learning.
- Utilized data visualization to gain insights and identify trends.

### Step 04: Hypothesis Testing
- Formulated hypotheses based on data visualization insights.
- Conducted statistical tests to validate hypotheses.

### Step 05: Feature Engineering
- Performed feature selection, manipulation, and addressed missing values and outliers.
- Transformed selected features and prepared data for model training.

### Step 06: Machine Learning Modeling
- Trained machine learning models to predict sales.

### Step 07: Hyperparameter Fine-Tuning
- Optimized model parameters to enhance predictive performance.

### Step 08: Deploy Modelo to Production
- Published the model in a cloud environment for broader use in business decision-making.

## Top Data Insights

1. Sales were higher on Mondays, possibly due to Sunday store closures, which had the lowest sales.
2. Promotions positively impacted both customers and sales.
3. Most stores had competition distances within 0 to 10 km, indicating higher sales in busy locations.
4. Store type 'B' had the highest sales average, attributed to unique assortments and Sunday openings.
5. Outliers in the dataset were justifiable, often associated with store type 'B' or ongoing promotions, which increased sales.

## Machine Learning Models Applied

Four models were utilized for analysis:

1. Linear Regression
2. XGBoost Regressor
3. Decision Tree Regressor

## Machine Learning Model Performance

### Decision Tree Regressor Model Performance:
- R-squared (Test): 0.9363
- Mean Absolute Error (Test): 503.83
- Root Mean Squared Error (Test): 783.60

## Conclusions

The sales forecast and insights generated from this analysis provide valuable tools for the CEO to allocate budgets effectively for store restoration and management.
