# Final Year Individual Project: Mind the gap - Dealing with missing data

**Mind the Gap – Dealing with Missing Data** is a final-year individual project completed as part of a BSc Computer Science degree at King’s College London.

This project investigates the challenge of missing data in real-world datasets, with a focus on medical data where completeness is often critical. The aim was to evaluate and compare the effectiveness of several imputation methods across different levels of missingness, using robust performance metrics.

## Key Objectives

- Examine and implement selected data imputation techniques.
- Test models across varying levels of missing data (5% to 25%).
- Evaluate each model using MAE, MSE, and RMSE performance metrics.
- Identify the most accurate and reliable approach to data imputation.

## Methods Implemented

- k-Nearest Neighbours (KNN)
- Random Forest (MissForest)
- Linear Regression
- Multiple Imputation by Chained Equations (MICE)

## Dataset

The project uses the **Diabetes** dataset from scikit-learn, which includes 442 entries and 10 features relevant to patient health (e.g., BMI, age, blood pressure).

## Results Summary

MICE emerged as the most effective model, consistently outperforming others in accuracy and robustness, especially at higher levels of missing data. Linear regression performed well at lower levels of missingness, while KNN struggled with sparsity and outliers. Random Forest proved to be a strong alternative, particularly when handling non-linear patterns.

## Technologies Used

- Python (Jupyter Notebook)
- pandas, NumPy, scikit-learn
- missingpy
- scipy

## Requirements

The project uses the following library versions:
- scikit-learn == 1.1.2
- scipy == 1.9.1
- missingpy == 0.2.0
- pandas == 2.2.1
- numpy == 1.24.4

## User Guide

### Setting up the Python Libraries

1. Download the `PRJ` folder to a location of your choice

2. Navigate to the folder location in your terminal

3. Execute the line in the terminal: `pip install -r requirements.txt`
    - This will ensure all the necessary Python libraries are updated to the versions required for this code to execute

### Running the files

1. In an IDE that supports Jupyter Notebook, open the four files:
    - `KNN.ipynb`
    - `RandomForest.ipynb`
    - `LinearRegression.ipynb`
    - `MICE.ipynb`

2. To execute each file and obtain an output, click the `Run All` button located at the top of the page
    - The output tables should be located at the bottom of the code cell
