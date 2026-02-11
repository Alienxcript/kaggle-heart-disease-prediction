# Heart Disease Prediction (Kaggle Playground Series S6E2)

## Overview
This project is based on the Kaggle Playground Series S6E2 competition.  
The objective is to predict the probability of heart disease using tabular data.

The competition evaluation metric is ROC AUC, which measures how well the model ranks positive cases above negative ones.

## Dataset
- Synthetic tabular dataset provided by Kaggle
- Training set includes features and the target variable
- Test set includes features only

## Approach
- Data loading and basic inspection  
- Feature / target separation  
- Feature scaling using StandardScaler  
- Logistic Regression model  
- Probability-based predictions for Kaggle submission  

## Results
- Public leaderboard ROC AUC: 0.94807

## Tools Used
- Python  
- pandas, numpy  
- scikit-learn  
- Kaggle Notebooks  

## Notes
This project focuses on building a simple, interpretable baseline model with strong performance on a synthetic dataset.  
Future improvements may include cross-validation, hyperparameter tuning, and model comparisons.
