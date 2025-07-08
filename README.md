# 🏡 Boston Housing Price Prediction - Machine Learning Project

This project aims to predict housing prices in Boston using multiple socio-economic and structural features. We leverage the **original Boston Housing Dataset** from Carnegie Mellon University and apply a **Linear Regression** model using Python's Scikit-learn library.

---

## 📌 Project Overview

- **Problem Statement**: Predict the median value of owner-occupied homes based on 13 features (e.g., crime rate, average rooms, population).
- **Dataset Source**: [CMU StatLib Archive](http://lib.stat.cmu.edu/datasets/boston)
- **Technique Used**: Linear Regression
- **Tools**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 🔍 Features Used

- `CRIM` – Per capita crime rate by town  
- `ZN` – Proportion of residential land zoned for large lots  
- `INDUS` – Proportion of non-retail business acres per town  
- `CHAS` – Charles River dummy variable  
- `NOX` – Nitric oxide concentration  
- `RM` – Average number of rooms per dwelling  
- `AGE` – Proportion of owner-occupied units built before 1940  
- `DIS` – Distance to employment centres  
- `RAD` – Index of accessibility to radial highways  
- `TAX` – Property-tax rate  
- `PTRATIO` – Pupil-teacher ratio  
- `B` – Proportion of Black population  
- `LSTAT` – % lower status of the population  
- **Target**: `PRICE` – Median value of homes (in $1000s)

---

## 🚀 Steps Followed

1. **Data Collection**: Parsed from CMU dataset using NumPy and Pandas.
2. **Data Preprocessing**: Cleaned and standardized feature values.
3. **Exploratory Data Analysis**: Plotted histograms, correlation heatmaps, pairplots.
4. **Model Training**: Used `LinearRegression()` from Scikit-learn.
5. **Evaluation**: Metrics like MSE and R² score were used.
6. **Visualization**: Plotted actual vs predicted prices.

---

## 📈 Results

- **Mean Squared Error (MSE)**: ~24.29  
- **R² Score**: ~0.74  
- Strong positive correlation observed with `RM` (rooms per dwelling), and negative correlation with `LSTAT` and `CRIM`.

---

## 📁 Project Structure





---

## 📌 Requirements

Install dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn






---

