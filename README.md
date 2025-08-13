🏠 House Price Prediction — Regression Project
This project is a university-style machine learning assignment that predicts housing prices using regression models.
It uses the Boston Housing dataset (via OpenML) or falls back to California Housing if Boston is unavailable.


End-to-end workflow preview

📌 Project Overview
The goal is to:

Perform feature preprocessing (scaling numeric data, one-hot encoding categorical variables).

Compare Linear Regression and Random Forest models.

Evaluate models using MAE, MSE, RMSE, R² metrics.

Visualize results (correlation heatmap, predicted vs actual, residuals, feature importance).

📂 Dataset
Primary: Boston Housing Dataset

Fallback: California Housing Dataset

⚙️ Requirements
Install dependencies:

bash
Copy
Edit
pip install scikit-learn pandas numpy matplotlib seaborn
🚀 Running the Project
Run in Jupyter Notebook, VS Code, or PyCharm.

Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Run the .py or .ipynb file:

bash
Copy
Edit
jupyter notebook House_Price_Prediction.ipynb
or

bash
Copy
Edit
python House_Price_Prediction.py
📊 Model Workflow
Data Loading

Load Boston Housing from OpenML.

Fallback to California Housing if needed.

Preprocessing

Scale numeric features with StandardScaler.

Encode categorical features with OneHotEncoder.

Use ColumnTransformer for clean pipelines.

Modeling

Linear Regression (baseline).

Random Forest Regressor (non-linear, tree-based).

Evaluation Metrics

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score (Coefficient of Determination)

Cross-validation for robustness.

Visualizations

Correlation heatmap.

Predicted vs Actual scatter plots.

Residual distribution plot.

Feature importance for Random Forest.

