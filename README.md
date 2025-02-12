# Vehicle Sales Layover Prediction

## 📌 Project Overview

This project aims to predict **LAID_UP_TIME**, the duration a vehicle remains at a dealership before being sold.
The model leverages **machine learning techniques** and a dataset containing various attributes such as **mileage,
construction year, horsepower, and color** to provide accurate predictions. The insights from this project can help
optimize inventory management and improve operational efficiency for dealerships.

## ⚙️ Methodology

1. **Data Preprocessing & Cleaning**

   - Handled missing values
   - Transformed categorical variables (e.g., reducing color complexity)
   - Scaled numerical variables

2. **Exploratory Data Analysis (EDA)**

   - Visualized correlations
   - Identified key predictive features

3. **Model Selection & Training**

   - **Random Forest Regressor** was chosen for its robustness and interpretability
   - **Hyperparameter tuning** using **RandomizedSearchCV**

4. **Evaluation & Optimization**
   - Used **Root Mean Squared Error (RMSE)** as the primary metric
   - Identified the most influential features in predicting layover time

## 🏆 Key Findings

- Features like **Scaled Inventorial Value, Mileage, Purchase Mileage, Year of Construction, and Manufacturer** were the most important factors.
- The **Random Forest model** provided strong predictive performance after tuning.

## 📈 Results

- The model successfully predicts **LAID_UP_TIME** with reasonable accuracy.
