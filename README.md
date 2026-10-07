# 🚗 Used Car Price Prediction Pipeline

An end-to-end Machine Learning project to predict used car prices based on features like mileage (`Kms_Driven`), vehicle age (`Car_Age`), fuel type, and transmission type. 

The best-performing model achieves an **R² Score of 86%** on unseen test data.

---

## 📊 Project Overview

- **Problem Type:** Regression
- **Target Variable:** `Selling_Price`
- **Key Features Used:** `Kms_Driven`, `Car_Age`, `Fuel_Type`, `Transmission`
- **Model Accuracy:** **86% ($R^2$ Score)**

---

## 🛠️ Data Preprocessing & Pipeline

1. **Feature Engineering:** Calculated `Car_Age` and handled skewed numeric distributions.
2. **Categorical Encoding:** Processed categorical features using `OneHotEncoder(drop='first', sparse_output=False)`.
3. **Feature Scaling:** Normalized numerical values using `StandardScaler` fitted on training data only.
4. **Data Splitting:** Partitioned the dataset using `train_test_split` (80% Train / 20% Test).
5. **Model Evaluation:** Evaluated using RMSE, MAE, and $R^2$ Score metrics.

