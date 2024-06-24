# House Price Prediction using Linear Regression

## Overview
This repository contains code and documentation for predicting house prices in California using Linear Regression. The project includes exploratory data analysis (EDA), model building, hyperparameter tuning, and evaluation.

## Contributors
- **Siddharth Nautiyal** (Reg No: 23122034, Class: 3MSc DS A)

## Objective
The objective of this project is to analyze the California Housing dataset, develop a Linear Regression model to predict housing prices, and evaluate the model's performance.

## Approach
1. **Data Exploration and Preprocessing**: 
   - Preliminary analysis
   - Visualization of key features
   - Data cleaning

2. **Model Building**:
   - Feature selection
   - Data splitting

3. **Linear Regression Model**:
   - Model fitting
   - Prediction

4. **Hyperparameter Tuning and Model Evaluation**:
   - Scaling the data
   - Tuning hyperparameters
   - Model evaluation using metrics like R² Score and Root Mean Square Error (RMSE)

## Files
- `housing.csv`: Dataset containing California housing information.
- `README.md`: Overview of the project and instructions.
- `house_price_prediction.ipynb`: Jupyter Notebook containing code for data analysis, model building, and evaluation.

## Usage
1. Clone the repository: `git clone https://github.com/Sid0702/House-Price-Prediction.git`
2. Navigate to the project directory: `cd House-Price-Prediction`
3. Run the Jupyter Notebook: `jupyter notebook house_price_prediction.ipynb`

## Results
- The best performing model achieved an R² Score of 0.63 and an RMSE of 69656.73.
- The Linear Regression model with intercept and scaled training data was selected for deployment.
