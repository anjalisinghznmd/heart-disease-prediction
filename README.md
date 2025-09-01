# Heart Disease Prediction Project

## Overview

This project uses a classic dataset from the UCI Machine Learning Repository to build a machine learning model capable of predicting whether a patient has heart disease. The goal was to explore the end-to-end machine learning workflow, from data cleaning and model selection to hyperparameter tuning.

---

## Dataset

The data used is the **Heart Disease Dataset** from the University of California, Irvine. 
[Link to the dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

The dataset contains 14 attributes including age, sex, cholesterol levels, and a target variable indicating the presence of heart disease.

---

## Process

1.  **Data Cleaning:** Loaded the data, assigned column names, and handled missing values using imputation.
2.  **Modeling:** Experimented with three different models: Random Forest, Logistic Regression, and XGBoost.
3.  **Data Scaling:** Applied `StandardScaler` to normalize the feature data, which is a best practice for many models.
4.  **Hyperparameter Tuning:** Used `GridSearchCV` to find the optimal settings for the best-performing model.

---

## Results

After comparing the models, the final tuned **Logistic Regression model** achieved the best and most reliable performance.

* **Final Model Accuracy: 63.33%**

---

## How to Run

1.  Download the `heart_disease.csv` file and the `.ipynb` notebook file.
2.  Open the notebook in Google Colab or another Jupyter environment.
3.  Upload the `.csv` file when prompted by the notebook.
4.  Run the cells sequentially to see the process and final result.
