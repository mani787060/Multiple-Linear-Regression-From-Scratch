# Multiple Linear Regression from Scratch

-> This project demonstrates how to build **Multiple Linear Regression (MLR)** completely from scratch using **NumPy**, without relying on sklearn’s `LinearRegression` class.


## Objective:-
-> To understand and implement the **mathematical foundation** of Multiple Linear Regression — including coefficient derivation, prediction, and performance evaluation.


## Project Workflow:-

1️⃣ **Data Preparation**
-> Imported dataset and performed data preprocessing.  
-> Handled missing values and normalized data if required.  

2️⃣ **Manual Implementation**
-> Added bias (intercept) term manually to the feature matrix.  
-> Computed regression coefficients using the **Normal Equation**:  
  \[
  \beta = (X^T X)^{-1} X^T y
  \]
-> Generated predictions (`y_pred = Xβ`).

3️⃣ **Evaluation Metrics**
-> Implemented metrics manually:
  -> **Mean Absolute Error (MAE)**
  -> **Mean Squared Error (MSE)**
  -> **Root Mean Squared Error (RMSE)**
  -> **R² Score**

4️⃣ **Comparison**
-> Compared results with sklearn’s `LinearRegression` to verify correctness.

5️⃣ **Visualization**
-> Visualized predicted vs actual values and residuals using Matplotlib.

## Libraries Used:-

-> numpy 
-> pandas 
-> matplotlib
