# Student Performance Prediction Using Linear Regression

This project demonstrates how to predict student performance using linear regression models. We analyze the impact of various features on a student's **Performance Index** and compare the results of simple and multiple linear regression.

---

## Dataset

- Source: `student_performance_dataset.csv`
- Features:
  - Hours Studied
  - Previous Scores
  - Extracurricular Activities (Yes/No)
  - Sleep Hours
  - Sample Question Papers Practiced
- Target:
  - Performance Index

---

## Project Overview

### 1. Data Exploration & Cleaning
- Inspected dataset for missing values and data types.
- Converted the categorical feature **Extracurricular Activities** from strings ("Yes","No") to numeric values (1,0).

### 2. Feature Scaling
- Standardized numerical features to have zero mean and unit variance using `StandardScaler`.

### 3. Outlier Detection
- Visualized numerical features with boxplots to check for outliers.

### 4. Correlation Analysis
- Plotted a heatmap to understand relationships between features and the target variable.
- Found **Previous Scores** to be strongly correlated with **Performance Index**.

### 5. Simple Linear Regression
- Built a regression model using only **Previous Scores**.
- Evaluated model performance using MAE, MSE, RMSE, and R² score.

### 6. Multiple Linear Regression
- Built a regression model using all features.
- Observed improved performance over the simple linear model.

---
## Summary
- The multiple linear regression model better captures the complexity of student performance.
- Feature engineering and scaling helped improve model accuracy.

### Thank You
