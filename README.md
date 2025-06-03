# 📊 Data Science & Analytics Project

This repository contains our final project for the **Data Science and Analytics** course. In this project, we perform a **multivariate time series prediction** using the **Vector AutoRegression (VAR)** model to forecast the **IDR/USD exchange rate** based on several macroeconomic variables.

## 👨‍💻 Team Members

- Mukhtada Billah Nasution  
- Imelda Agustin  
- Megawati Ananda Putri  
- Afsil Aiman


## 📌 Project Overview

Exchange rates are influenced by a variety of economic indicators. Understanding and predicting these fluctuations is crucial in economics, finance, and policy-making. In this project, we explore how multiple variables interact over time and use this data to model and predict future values of the IDR/USD exchange rate.

### 🔍 Objective
To build a predictive model for the IDR/USD exchange rate using multivariate time series data and the Vector AutoRegression (VAR) method.

## ⚙️ Methodology

1. **Data Collection**  
   We gathered historical data for variables influencing the IDR/USD exchange rate, such as:
   - Interest rates  
   - Inflation rate  
   - Crude oil prices  
   - Stock indices  
   - Foreign exchange reserves  

2. **Data Preprocessing**  
   - Handling missing values  
   - Data normalization/scaling  
   - Stationarity checks using ADF test  
   - Differencing the data if necessary  

3. **Modeling with VAR**  
   - Lag order selection using AIC/BIC  
   - Fitting the VAR model  
   - Forecasting future values  
   - Inverse transformation of differenced data (if applied)  

4. **Evaluation**  
   - RMSE (Root Mean Squared Error)  
   - MAE (Mean Absolute Error)  
   - Visual inspection of actual vs predicted exchange rates  

## 📦 Dependencies

To run this project, make sure you have the following Python libraries installed:

```bash
pandas
numpy
matplotlib
statsmodels
seaborn
scikit-learn
```
You can install them using pip:
```bash
pip install pandas numpy matplotlib statsmodels seaborn scikit-learn
```
