# Linear_REgression_Task3
Housing Price Prediction using Linear Regression
# 🏠 Linear Regression - Housing Price Prediction

This project implements **Simple & Multiple Linear Regression** to predict house prices using the **Housing Price Prediction Dataset**.  
It was created as part of **AI & ML Internship - Task 3**.

---

## 📌 Project Overview
- **Goal:** Implement and understand simple & multiple linear regression.
- **Tools Used:**  
  - Python (Pandas, NumPy, Matplotlib, Scikit-learn)  
  - Google Colab for execution  
  - Google Drive for dataset access  

---

## 📂 Dataset
Dataset used: [Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

**Target Variable:** `price`  
**Example Features:** `area`, `bedrooms`, `bathrooms`, etc.

---

## ⚙️ Steps Performed
1. **Load dataset from Google Drive** (CSV file).  
2. **Preprocessing:**
   - Handle categorical features using one-hot encoding.
   - Remove unnecessary columns.
3. **Split dataset** into Train (80%) and Test (20%) sets.
4. **Train Linear Regression Model** using `sklearn.linear_model.LinearRegression`.
5. **Evaluate** using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
6. **Plot regression line** for simple regression.
7. **Interpret coefficients** for feature impact.

---

## 📊 Results
MAE: 112934.45
MSE: 19834567890.23
R² Score: 0.8423


Example metrics from run:

