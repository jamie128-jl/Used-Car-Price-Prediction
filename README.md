# Used-Car-Price-Prediction
Predicting used car prices to support pricing insights and decision-making through machine learning regression techniques.

# Used Car Price Prediction

This project builds an end-to-end machine learning pipeline to predict used car prices based on vehicle attributes such as make, model, year, mileage, and engine specifications.  

## Overview
We applied and compared multiple regression models to estimate car prices and evaluated their performance using cross-validation and error metrics. The goal was to determine which models best capture nonlinear relationships in car features while remaining interpretable and efficient.

## Models
- **Ridge Regression** – linear baseline with regularization  
- **Random Forest Regressor** – tree-based ensemble model  
- **Multilayer Perceptron (Neural Network)** – experimented with hidden layers, activations, and learning rates  

## Results
- Ridge Regression provided the most consistent performance across validation sets.  
- Random Forest captured some nonlinear effects but risked overfitting.  
- The MLP Regressor showed potential but underperformed compared to Ridge and Random Forest.  
- **Best R² ≈ 0.70, average cross-validation R² ≈ 0.52.**

## Key Features
- Data preprocessing: cleaning, encoding categorical variables, scaling numerical features  
- Feature engineering to capture relevant car attributes  
- Model selection and hyperparameter tuning (GridSearchCV)  
- Evaluation metrics: RMSE, MAE, R²  
- Visualizations of predicted vs. actual prices  

## Tools & Libraries
- Python (pandas, numpy)  
- scikit-learn (regression models, MLP)  
- matplotlib, seaborn  
- Jupyter Notebook  

## Repo Structure
