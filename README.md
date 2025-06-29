# Imputing-Missing-Data---Final-Year-Project

## Project Overview

**Mind the Gap – Dealing with Missing Data** is a final-year individual project completed as part of a BSc Computer Science degree at King’s College London.

This project investigates the challenge of missing data in real-world datasets, with a focus on medical data where completeness is often critical. The aim was to evaluate and compare the effectiveness of several imputation methods across different levels of missingness, using robust performance metrics.

### Key Objectives

- Examine and implement selected data imputation techniques.
- Test models across varying levels of missing data (5% to 25%).
- Evaluate each model using MAE, MSE, and RMSE performance metrics.
- Identify the most accurate and reliable approach to data imputation.

### Methods Implemented

- k-Nearest Neighbours (KNN)
- Random Forest (MissForest)
- Linear Regression
- Multiple Imputation by Chained Equations (MICE)

### Dataset

The project uses the **Diabetes** dataset from scikit-learn, which includes 442 entries and 10 features relevant to patient health (e.g., BMI, age, blood pressure).

### Results Summary

MICE emerged as the most effective model, consistently outperforming others in accuracy and robustness, especially at higher levels of missing data. Linear regression performed well at lower levels of missingness, while KNN struggled with sparsity and outliers. Random Forest proved to be a strong alternative, particularly when handling non-linear patterns.

### Technologies Used

- Python (Jupyter Notebook)
- pandas, NumPy, scikit-learn
- missingpy
- Agile development methodology

### Conclusion

This project highlights the importance of choosing an appropriate imputation strategy when working with incomplete data. It also demonstrates how performance can vary based on dataset characteristics and missingness level, reinforcing the need for empirical evaluation in real-world scenarios.
