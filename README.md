# Heart Disease Prediction (Kaggle Playground Series S6E2)

## Overview
This project is based on the Kaggle Playground Series S6E2 competition.  
The goal is to predict the probability of heart disease using tabular data.

The evaluation metric is ROC AUC, which measures how well the model ranks positive cases above negative ones.

## Dataset
- Synthetic tabular dataset provided by Kaggle
- Train set contains features and target
- Test set contains features only

## Approach
- Data loading and inspection
- Feature/target separation
- Feature scaling using StandardScaler
- Logistic Regression model
- 5-fold cross-validation using ROC AUC
- Probability-based predictions for Kaggle submission

## Results
- Cross-validation ROC AUC: ~0.94  
- Public leaderboard ROC AUC: 0.948

## Tools Used
- Python
- pandas, numpy
- scikit-learn
- Kaggle Notebooks

## Notes
This project focuses on building a simple, interpretable baseline model with strong performance on synthetic data.
