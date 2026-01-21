## Tricast
### Comparative Analysis of Linear Modeling Techniques: Frequentist, Bayesian, and Machine Learning Approaches in Predicting Housing Prices

## Overview
This project explores and compares different modeling approaches for predicting housing prices using the Ames Housing dataset. Methods span frequentist, Bayesian, and machine learning techniques, with a focus on predictive accuracy, interpretability, and uncertainty quantification.

## Methods
- **Frequentist Linear Regression** (`lm`)
- **Regularized Regression** (Ridge, Lasso via `glmnet`)
- **Bayesian Regression** (`brms`, `rstanarm`)
- **Random Forest** (`ranger`)
- **Gradient Boosting** (`xgboost`)

## Evaluation Metrics
- **Accuracy**: RMSE, MAE, R²  
- **Uncertainty**: Confidence intervals, credible intervals, bootstrapped intervals  
- **Interpretability**: Coefficients, variable importance, posterior distributions  

## Structure
- `data/` – Ames housing dataset  
- `scripts/` – R scripts for each model  
- `results/` – Output tables, figures, diagnostics  
- `report/` – Final project write-up  

## Key Findings
All models captured housing price variation, with machine learning methods excelling in prediction accuracy while Bayesian regression provided richer insights into uncertainty. Together, these approaches illustrate trade-offs between interpretability, predictive performance, and uncertainty quantification.
