# Regression-Modeling-with-Ridge-Lasso-and-Linear-Regression


This project demonstrates the implementation and comparison of **Linear Regression**, **Ridge Regression**, and **Lasso Regression** on the **California Housing dataset** using Python. The goal is to predict the median house value based on various features such as income, location, and housing attributes.

---

## Objectives

- Build predictive models for housing prices using different regression techniques.
- Apply **regularization** (Ridge and Lasso) to control model complexity and prevent overfitting.
- Evaluate model performance using metrics like **Mean Squared Error (MSE)** and **R² score**.
- Optimize hyperparameters using **GridSearchCV** and apply **cross-validation**.
- Perform residual analysis to assess model accuracy.

---

## Key Concepts

- **Linear Regression**: Minimizes the sum of squared residuals.
- **Ridge Regression**: Adds L2 regularization to reduce model variance.
- **Lasso Regression**: Adds L1 regularization to enforce sparsity in coefficients.
- **Grid Search**: Explores a range of `alpha` values to find the best regularization strength.
- **Cross-Validation**: Ensures that the model generalizes well to unseen data.

---

## Dataset

The dataset is sourced from `sklearn.datasets.fetch_california_housing()`.

Features include:
- Median income
- House age
- Average rooms
- Population
- Latitude, Longitude, etc.

Target:
- `MedHouseVal`: Median House Value

---

## Model Evaluation Metrics

- **Mean Squared Error (MSE)**
- **R² Score**
- **Cross-validation score**
- **Residual distribution visualization**
- **Scatter plot of actual vs predicted values**

---

## Technologies Used

- **Python 3**
- **scikit-learn**
- **NumPy & Pandas**
- **Matplotlib & Seaborn**
- **GridSearchCV (for hyperparameter tuning)**

---

## Structure

