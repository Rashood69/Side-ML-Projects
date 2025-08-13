# 🏠 House Price Prediction — Regression Project

This is a **university-style ML project** to predict housing prices using regression, following industry-level presentation and best practices.

[![Demo Workflow](images/demo.gif)](images/demo.gif)  
*A quick walkthrough of the project's workflow*

---

#📌 Project Overview

- Load the **Boston Housing dataset** (via OpenML), falling back to **California Housing** if Boston is unavailable.
- Preprocess data: **scale numeric features** and apply **one-hot encoding** for categorical variables.
- Compare two models:
  - **Linear Regression** (baseline, interpretable)
  - **Random Forest Regressor** (nonlinear ensemble)
- Evaluate models with metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
  - 5-fold cross-validation for stability
- Generate visualizations:
  - Correlation heatmap
  - Predicted vs Actual scatter plots
  - Residuals distribution
  - Feature importance chart (Random Forest)

---

## Visual Insights

| Plot | Description |
|------|-------------|
| ![Heatmap](images/heatmap.png) | Correlation matrix of numeric features |
| ![Predicted vs Actual](images/pred_vs_actual.png) | Model performance on test set |
| ![Residuals](images/residuals.png) | Distribution of prediction errors |
| ![Feature Importance](images/feature_importance.png) | Most influential features |

---

## Quick Start

```bash
git clone https://github.com/Rashood69/Side-ML-Projects.git
cd Side-ML-Projects



Feature importance for Random Forest.

