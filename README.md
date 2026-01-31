# Medical Insurance Cost Prediction

**Group Project | Kaggle Dataset: [Medical Insurance Costs](https://www.kaggle.com/datasets/mirichoi0218/insurance)**

## Project Overview
This project aims to predict individual medical insurance costs based on personal and demographic information using regression models. The analysis was conducted as a **group project** with the goal of applying statistical modeling, feature engineering, and machine learning techniques to real-world healthcare data.

## Dataset
- Source: Kaggle ([Medical Insurance Costs](https://www.kaggle.com/datasets/mirichoi0218/insurance))
- Features include:
  - `age`: Age of the insured individual
  - `sex`: Gender
  - `bmi`: Body mass index
  - `children`: Number of children
  - `smoker`: Smoking status
  - `region`: Residential area
- Target variable: `charges` (individual medical insurance cost)

---

## Project Goals
- Predict medical insurance costs accurately using regression models.
- Compare multiple regression approaches to identify the most effective model.
- Demonstrate skills in **feature engineering**, **model evaluation**, and **interpretability**.

---

## Methods
1. **Data Cleaning & Preprocessing**
   - Checked for missing values and duplicates.
   - Encoded categorical variables (`sex`, `smoker`, `region`) for regression models.
   - Performed feature scaling for numeric variables.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed relationships between features and target variable.
   - Visualized distributions, correlations, and feature importance.

3. **Modeling**
   - Implemented regression models including:
     - Linear Regression
     - Ridge Regression
     - Lasso Regression
   - Evaluated models using:
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)
     - R² (coefficient of determination)

4. **Feature Engineering**
   - Created additional interaction features where relevant.
   - Encoded categorical features using one-hot encoding.

---

## Tools & Technologies
- **Languages:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## Contributions
- Responsibilities included:
  - Data cleaning and preprocessing
  - Model implementation and evaluation
  - EDA visualizations and report preparation
  - Feature engineering and interpretation

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/medical-insurance-prediction.git
