# 🚗 AutoPricePredictor

Predicting car prices using Linear Regression and Lasso Regression models.

## 📌 Project Overview

This project aims to build a machine learning model that can predict the price of a car based on various features such as engine size, mileage, fuel type, and brand. We compare Linear Regression with Lasso Regression to evaluate which model offers better performance and generalization.

## 📁 Project Structure
AutoPricePredictor/
│
├── data/ # Dataset files (CSV)
├── notebooks/ # Colab for EDA & model building
├── src/ # Source code files
│ ├── preprocess.py # Data cleaning and preprocessing functions
│ ├── model_train.py # Model training and evaluation
│
├── model/ # Trained models (optional)
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## 🔍 Features Used

- Car Brand
- Model Year
- Engine Size
- Mileage
- Fuel Type
- Transmission
- Number of Doors

## 🧪 Models Used

- **Linear Regression**
- **Lasso Regression (L1 Regularization)**

## 📊 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Sample Results

| Model            | R² Score | MAE     | RMSE    |
|------------------|----------|---------|---------|
| Linear Regression| 0.87     | ₹45,000 | ₹65,000 |
| Lasso Regression | 0.85     | ₹47,500 | ₹67,000 |

## Author
- Joyti Das
