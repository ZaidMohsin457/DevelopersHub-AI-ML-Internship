# AI/ML Engineering Internship Tasks

This repository contains solutions to three core data science and machine learning tasks completed as part of an internship program. Each task demonstrates a different aspect of data analysis, modeling, and interpretation.

---

## Task 1: Exploring and Visualizing a Simple Dataset
**Objective:** Load, inspect, and visualize the Iris dataset to understand data trends and distributions.

- **Dataset Used:** Iris Dataset (from seaborn or CSV)
- **Key Steps:**
    - Loaded the dataset using pandas
    - Inspected shape, columns, and summary statistics
    - Visualized feature relationships with scatter plots, histograms, and box plots using matplotlib and seaborn
- **Key Findings:**
    - Clear separation between species in feature space
    - Some features show strong correlation (e.g., petal length vs. petal width)
    - Outliers and distribution shapes identified via box plots and histograms

---

## Task 2: Predict Future Stock Prices (Short-Term)
**Objective:** Use historical stock data to predict the next day's closing price.

- **Dataset Used:** Stock market data from Yahoo Finance (via yfinance library)
- **Models Applied:**
    - Linear Regression
    - Random Forest Regressor
- **Key Steps:**
    - Downloaded historical data for a selected stock (e.g., Apple)
    - Used Open, High, Low, and Volume to predict the next Close price
    - Trained regression models and compared actual vs. predicted prices
- **Key Findings:**
    - Both models captured short-term price trends, with Random Forest generally outperforming Linear Regression
    - Visualizations showed the models' ability to follow real closing price movements

---

## Task 3: Heart Disease Prediction
**Objective:** Build a model to predict whether a person is at risk of heart disease based on their health data.

- **Dataset Used:** UCI Heart Disease Dataset (Kaggle)
- **Models Applied:**
    - Logistic Regression
    - Decision Tree Classifier
- **Key Steps:**
    - Cleaned data and handled missing values
    - Performed EDA (class balance, feature distributions, correlations)
    - One-hot encoded categorical variables
    - Trained and evaluated models using accuracy, ROC curve, AUC, and confusion matrix
    - Analyzed feature importance
- **Key Findings:**
    - Both models achieved reasonable accuracy
    - ROC/AUC and confusion matrices provided insight into model performance
    - Feature importance analysis highlighted the most influential health indicators

---

Each notebook provides a complete workflow for its respective task, including data loading, preprocessing, modeling, evaluation, and visualization. These solutions can be adapted for similar problems in data science and machine learning.
