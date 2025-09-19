# Rusty Bargain Car Sales Value Prediction

## Overview
Built and compared multiple regression models to predict used car market prices using Rusty Bargain’s real-world dataset.

## Objectives
- Perform EDA on car features (mileage, brand, age, fuel type, etc.).
- Handle missing data and encode categorical variables.
- Train Linear, Decision Tree, Random Forest, and LightGBM models.
- Compare performance using RMSE.

## Key Tools & Libraries
- pandas, numpy, seaborn
- scikit-learn
- LightGBM

## Highlights
- LightGBM achieved RMSE under **1800** on holdout test set.
- Included custom preprocessing and grouped median imputation.
- Visualized prediction errors by brand and mileage.

## How to Run
1. Open `Rusty Car sales Project.ipynb`.
2. Run preprocessing, training, and test steps
