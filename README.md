# Advanced Regression House Prices - Machine Learning Project

## Overview
This project explores advanced regression techniques to predict **house prices** in Ames, Iowa. Using **data preprocessing, feature engineering, and machine learning models**, we aim to build an accurate pricing model that can be used by buyers, sellers, and real estate professionals.

## Key Features
- **Data Preprocessing & Cleaning:**
  - Handled missing values using imputation techniques.
  - Encoded categorical variables for model compatibility.
  - Normalized numerical features for better model performance.
- **Exploratory Data Analysis (EDA):**
  - Visualized relationships between key features and house prices.
  - Identified strong predictors such as `OverallQual`, `GrLivArea`, and `TotalBsmtSF`.
- **Modeling & Evaluation:**
  - Applied multiple regression techniques:
    - **Linear Regression**
    - **Ridge and Lasso Regression**
    - **Gradient Boosting (XGBoost, LightGBM)**
    - **Random Forest Regressor**
  - Evaluated models using **Root Mean Squared Error (RMSE)**.
  - Best performing model achieved **RMSE of 0.1519 on training data**.

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn)
- **Jupyter Notebook** for analysis and modeling
- **GitHub** for version control and collaboration

## Results
- **Top Predictors:** `OverallQual`, `GrLivArea`, and `TotalBsmtSF` were the most influential in determining house prices.
- **Feature Engineering:** Log-transforming `SalePrice` improved model performance.
- **Best Model:** XGBoost had the lowest RMSE, outperforming other regression models.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Final Project.ipynb"
   ```

## Contributors
- **Gerard Corrales**
- **Sahil Wadhwa**
- **Anahit Shekikyan**
