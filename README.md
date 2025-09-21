# California Housing Price Prediction

## Project Overview
This project focuses on predicting **median house values in California districts** using the **California Housing dataset** from scikit-learn.  
The notebook demonstrates a complete **machine learning workflow**: data preprocessing, exploratory data analysis (EDA), model training, evaluation, and result comparison.

---

## Dataset Description
- Source: `fetch_california_housing` from `sklearn.datasets`
- Features include:
  - Median income
  - Average number of rooms
  - Average house age
  - Population & households
  - Latitude & longitude
- Target variable: **Median House Value (MedHouseVal)**

---

## Installation
To run this project locally:

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
cd House-Price-Prediction
pip install -r requirements.txt

# Usage
## 1.Open the Jupyter Notebook file:
jupyter notebook House_Price_Linear_Regression.ipynb
## 2.Run each cell to:
- Load and preprocess the dataset
- Perform EDA (data visualization, correlations, distributions)
- Train regression models (Linear Regression, Random Forest)
- Evaluate performance

# Methodology & Workflow

## Data Preprocessing

- Handle missing values and outliers
- Scale features and correct skewed distributions

## Exploratory Data Analysis (EDA)

- Feature distribution plots
- Correlation heatmap
- Insights into relationships between variables

## Model Training
- Baseline: Linear Regression
- Advanced: Random Forest Regression

## Model Evaluation
- Metrics used: MSE, RMSE, MAE, R²

# Results & Evaluation

## Linear Regression
- MSE: 0.513
- RMSE: 0.716
- MAE: 0.546
- R²: 0.590

## Random Forest Regression
- MSE: 0.219
- RMSE: 0.468
- MAE: 0.465
- R²: much stronger performance

Conclusion: Random Forest outperforms Linear Regression by capturing complex feature interactions and non-linearities.

## Visualizations
- Feature distributions (histograms, density plots)
- Correlation heatmap
- Actual vs Predicted house prices

## Acknowledgments

- **Dataset:** [California Housing dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)  
- **Libraries:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`

## Project Info

- **Author:** Poorchista Jafari
- **Project Year:** 2025
