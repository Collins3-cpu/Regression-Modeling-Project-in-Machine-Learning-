# Regression-Modeling-Project-in-Machine-Learning-
Comparative Analysis of Linear Regression vs Random Forest Regression

This project explores machine learning regression techniques to predict the aqueous solubility (logS) of molecules using molecular descriptors. It compares the performance of Linear Regression and Random Forest Regression.

Data Source: delaney_solubility_with_decriptors.csv

📋 Project Overview

Dataset: Delaney's Solubility dataset (delaney_solubility_with_descriptors.csv)

Features: Molecular descriptors (MolLogP, MolWt, NumRotatableBonds, AromaticProportion)

Target: logS — Log of aqueous solubility

Goal: Build, evaluate, and compare two regression models for solubility prediction.

📊 Key Insights
## Linear Regression

Simple baseline model using all descriptors.

Achieved reasonable performance on both training and test sets.

## Random Forest Regression

Ensemble method with controlled tree depth.

Compared against linear model for accuracy and generalization.

## Model Performance

Evaluated using MSE and R² scores on train/test splits.

Visualized predictions vs experimental values.

# 🔍 Analysis Highlights

Data loaded and split into features (X) and target (Y).

Models trained and predictions generated for both train and test sets.

Performance metrics calculated for comparison.

Scatter plot visualization of predicted vs actual solubility values.

# 💡 Recommendations

## Model Selection:
Random Forest may capture nonlinear relationships better than linear regression.

Consider hyperparameter tuning for Random Forest (e.g., n_estimators, max_depth).

## Feature Engineering:
Explore additional molecular descriptors.

Consider feature scaling or selection.

## Further Improvements:
Cross-validation for more robust evaluation.

Compare with other models (XGBoost, SVR).

Deploy the model for virtual screening of new compounds.

## Applications:

Drug discovery: Predict solubility of candidate molecules.

Environmental chemistry: Assess compound behavior in water.

# 🛠️ Technologies Used

Data Handling: pandas, numpy

Modeling: scikit-learn (LinearRegression, RandomForestRegressor)

Visualization: matplotlib

Environment: Python 3, Jupyter


