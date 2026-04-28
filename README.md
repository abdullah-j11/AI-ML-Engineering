1. Iris Dataset - Exploration & Visualization
 A beginner-friendly data analysis project using the Iris dataset.
 What This Project Does
- Loads and inspects the Iris dataset using Pandas
- Generates summary statistics with `.info()` and `.describe()`
- Visualizes data using Matplotlib and Seaborn
  - Scatter Plot (feature relationships)
  - Histograms (value distributions)
  - Box Plots (outlier detection)
Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

2. Stock Price Prediction using Machine Learning
A machine learning project that predicts the next day's closing price
of Apple Inc. (AAPL) stock using historical market data.
What This Project Does
- Fetches real-time historical stock data using **yfinance** API
- Inspects and explores the dataset (shape, stats, missing values)
- Engineers features from Open, High, Low, and Volume
- Trains two ML models:
  - Linear Regression
  - Random Forest Regressor
- Evaluates models using MAE, RMSE, and R² score
- Plots Actual vs Predicted closing prices for comparison
- Shows Feature Importance from Random Forest

Libraries Used
- Python
- Pandas & NumPy
- yfinance
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook


3. Heart Disease Prediction & Analysis
This project implements a machine learning pipeline to predict the likelihood of heart disease in patients based on clinical parameters. It covers the full lifecycle of a data science project, from Exploratory Data Analysis (EDA) to Model Evaluation and Feature Importance analysis.

Project Objective
To build and evaluate a binary classification model that accurately identifies patients at risk of heart disease using the UCI Heart Disease Dataset.

Skills & Tools
Languages: Python 3.10+

Libraries: Pandas, NumPy, Scikit-Learn

Visualization: Matplotlib, Seaborn

Techniques: Data Cleaning, Feature Scaling, Logistic Regression, Decision Trees.

Dataset Overview
The dataset contains 14 key features used to predict the presence of heart disease (Target = 1), including:

Age & Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Serum Cholesterol (chol)

Maximum Heart Rate Achieved (thalach)

Key Features of the Implementation
Exploratory Data Analysis (EDA): Visualized feature correlations and distribution of heart disease cases.

Model Comparison: Implemented and compared Logistic Regression and Decision Tree classifiers.

Comprehensive Evaluation:

Accuracy Score to measure overall performance.

Confusion Matrix to analyze False Positives and False Negatives (critical in medical diagnostics).

ROC-AUC Curve to evaluate the model’s ability to distinguish between classes.

Feature Importance: Identified which medical factors (e.g., chest pain type or maximum heart rate) are the strongest predictors of heart disease.
