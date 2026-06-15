# Multiple Linear Regression From Scratch

## 📌 Project Overview

This project demonstrates how to implement **Multiple Linear Regression (MLR)** completely from scratch using **NumPy**, without relying on Scikit-Learn's `LinearRegression` model.

The notebook focuses on understanding the mathematical foundation behind regression by manually calculating regression coefficients using the **Normal Equation**, generating predictions, and evaluating model performance. The implementation is performed on the **Diabetes Dataset (`load_diabetes`)**.

---

## 🎯 Objectives

* Understand the mathematics behind Multiple Linear Regression
* Implement regression without using machine learning libraries
* Learn how regression coefficients are calculated
* Generate predictions manually
* Evaluate model performance using regression metrics

---

## 📂 Dataset

**Dataset Used:** `load_diabetes`

The Diabetes dataset contains multiple medical features that are used to predict a continuous target variable, making it ideal for demonstrating Multiple Linear Regression.

---

## 📖 Concepts Covered

* Multiple Linear Regression
* Normal Equation
* Regression Coefficients
* Matrix Operations
* Prediction
* Error Analysis
* Model Evaluation

---

## 🛠️ Libraries Used

* NumPy
* Pandas
* Matplotlib

---

## ⚙️ Implementation Steps

### Data Preparation

* Load the Diabetes dataset
* Create feature matrix and target vector
* Perform train-test splitting

### Manual Model Building

* Add bias (intercept) term
* Apply the Normal Equation

β = (XᵀX)⁻¹Xᵀy

* Calculate regression coefficients manually

### Prediction

* Generate predictions using calculated coefficients
* Compare actual and predicted values

### Model Evaluation

* Calculate Mean Absolute Error (MAE)
* Calculate Mean Squared Error (MSE)
* Calculate Root Mean Squared Error (RMSE)
* Calculate R² Score

### Validation

* Compare results with Scikit-Learn's LinearRegression model
* Verify correctness of implementation

---

## 🔍 Key Observations

* The Normal Equation provides a closed-form solution for regression coefficients.
* Manual implementation helps understand the internal workings of regression models.
* Results closely match Scikit-Learn's implementation.
* Matrix operations form the foundation of many machine learning algorithms.

---

## ✅ Advantages

* Builds strong mathematical intuition
* No dependency on pre-built regression models
* Improves understanding of linear algebra in ML
* Excellent foundation for advanced machine learning concepts

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib

---

## 🏁 Conclusion

Implementing Multiple Linear Regression from scratch provides a deeper understanding of how machine learning models learn from data. By manually calculating coefficients, predictions, and evaluation metrics, this project bridges the gap between theory and practical implementation.
