# Gold Price Time Series Forecasting

## 📌 Project Overview

This project focuses on analyzing historical gold prices and forecasting future gold prices using Time Series Analysis and Machine Learning techniques.

The dataset contains monthly gold prices from 1950 to 2020. The project includes data preprocessing, exploratory data analysis, visualization, time-based analysis, and forecasting using Linear Regression.

## 🎯 Objectives

- Analyze historical gold price data.
- Understand gold price trends over time.
- Perform monthly, yearly, quarterly, and decade-wise analysis.
- Visualize gold price trends.
- Calculate yearly mean, standard deviation, and coefficient of variation.
- Split the dataset into training and testing data.
- Build a Linear Regression forecasting model.
- Evaluate the forecasting model using Mean Absolute Percentage Error (MAPE).

## 📊 Dataset

The dataset contains historical monthly gold prices.

### Dataset Features

- `Date` - Date/month of the observation
- `Price` - Gold price

### Dataset Period

- Start: January 1950
- End: July 2020
- Total observations: 847

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas:

```python
df = pd.read_csv("monthly_csv.csv")