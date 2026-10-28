# Used Car Price Prediction Using Regression

## Project Overview
This project uses machine learning regression models to predict used-car selling prices based on vehicle details.

## Business Objective
Estimate used-car prices using information such as year, brand, model, kilometres travelled, fuel type, and city.

## Dataset
The dataset contains 1,725 records and 23 columns.

The target variable is `price`, representing the selling price in Indian rupees.

## Project Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Data cleaning and feature selection
4. Categorical feature encoding
5. Train-test split
6. Training regression models
7. Model evaluation and comparison
8. Saving and testing the selected model

## Models Compared
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Results

Random Forest performed best among the three models tested.

| Metric | Result |
|---|---:|
| MAE | ₹3.12 lakh |
| RMSE | ₹9.62 lakh |
| R² Score | 0.725 |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Conclusion
Random Forest achieved the best results among the tested models on the test dataset.

The model was saved and successfully loaded to verify that it reproduced the original predictions. However, some predictions may still have large errors, so the estimates are not guaranteed selling prices.