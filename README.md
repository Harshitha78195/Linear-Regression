# House Price Prediction using Linear Regression

This project implements **Simple and Multiple Linear Regression** models to predict house prices based on various housing features. It demonstrates the application of regression modeling using **Scikit-learn**, **Pandas**, and **Matplotlib**.

---

## Objective

To build a linear regression model that predicts the price of a house based on features such as area, number of bedrooms, presence of air conditioning, and furnishing status.

---

## Tools & Libraries

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## Dataset Description

The dataset includes real estate data with the following features:

| Feature            | Description                                          |
|--------------------|------------------------------------------------------|
| `price`            | Price of the house (Target Variable)                |
| `area`             | Area in square feet                                 |
| `bedrooms`         | Number of bedrooms                                  |
| `bathrooms`        | Number of bathrooms                                 |
| `stories`          | Number of floors                                    |
| `mainroad`         | Is house connected to a main road (yes/no)         |
| `guestroom`        | Presence of guest room (yes/no)                    |
| `basement`         | Presence of basement (yes/no)                      |
| `hotwaterheating`  | Hot water heating available (yes/no)               |
| `airconditioning`  | Has air conditioning (yes/no)                      |
| `parking`          | Number of parking spots                            |
| `prefarea`         | Located in preferred area (yes/no)                 |
| `furnishingstatus` | Furnishing status (furnished, semi-furnished, unfurnished) |

---

## Steps Performed

1. **Importing and exploring the dataset**
2. **Preprocessing**:
   - Encoding categorical values (Yes/No → 1/0)
   - One-hot encoding `furnishingstatus`
3. **Train-Test Split (80/20)**
4. **Model Training** using `LinearRegression` from Scikit-learn
5. **Model Evaluation** using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. **Visualization**:
   - Actual vs Predicted price scatter plot
7. **Model Interpretation**:
   - Intercept and feature coefficients

---

## Evaluation Metrics

| Metric | Value |
|--------|--------|
| MAE    | ₹9.7 Lakhs |
| MSE    | ~1.75 Trillion |
| RMSE   | ₹13.2 Lakhs |
| R²     | 0.65 |

> 📌 The model explains ~65% of the variance in house prices, which is a decent baseline. Further tuning and advanced models could improve performance.

---

## What I Learned

- How to prepare and preprocess real-world tabular data
- Building and interpreting a multiple linear regression model
- Evaluating model performance using standard regression metrics
- Visualizing predictions and understanding model behavior

---



