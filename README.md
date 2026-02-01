# 📈 Commodity Price Time Series Analysis

## 📖 Overview
This project focuses on building and evaluating statistical time series models for the prices of five different commodities: cocoa, coffee, sugar, copper, and platinum, using data from 2020 to 2024.

The main objective is to analyze price behavior and volatility patterns and to determine the most suitable forecasting model for each commodity.

---

## 📊 Dataset
- Time Period: 2020 – 2024  
- Commodities:
  - Cocoa
  - Coffee
  - Sugar
  - Copper
  - Platinum
- Data Type: Historical price time series

The dataset was cleaned and preprocessed to handle missing values and ensure stationarity when required.

---

## 🛠️ Tools & Technologies
- Programming Language: Python  
- Environment: Jupyter Notebook  
- Libraries:
  - Pandas
  - NumPy
  - Statsmodels
  - Matplotlib / Seaborn
  - Arch (for ARCH/GARCH models, if applicable)

---

## 🔍 Methodology
All analysis is conducted in a single Jupyter Notebook and follows these main steps:

1. Data Collection and Preprocessing  
2. Stationarity Testing (ADF, KPSS)  
3. Model Identification  
4. Model Estimation  
5. Residual Diagnostics  
6. Model Comparison  
7. Forecasting and Evaluation  

Each step is documented within the notebook.

---

## ⚙️ Models Implemented
The following time series models are applied:

- Autoregressive (AR)  
- Moving Average (MA)  
- ARMA  
- ARIMA  
- ARCH  
- GARCH  

These models are used to analyze both price dynamics and volatility structures.

---

## 📈 Model Evaluation
Model performance is evaluated using:

- Information Criteria (AIC, BIC, HQIC)  
- Residual Analysis  
- Autocorrelation Tests  
- Volatility Diagnostics  

The most suitable model for each commodity is selected based on these criteria.

---

## 📊 Results
- Optimal models are identified for each commodity series.  
- Volatility clustering is observed in several markets.  
- GARCH-based models perform well in capturing price variability.  
- Forecasting results provide reasonable short-term predictions.

Detailed results and visualizations are available in the notebook.

---

