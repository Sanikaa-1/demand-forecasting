# 📦 Demand Forecasting with ARIMA & SARIMA

This project focuses on forecasting weekly demand using classical time series models — ARIMA and SARIMA — in Python. The final model predicts demand for the next 52 weeks and evaluates performance using industry-standard metrics.

---

## 📈 Project Overview

- Forecasted future demand using time series data (weekly)
- Performed seasonal decomposition to analyze trend and seasonality
- Built and evaluated multiple forecasting models:
  - ARIMA (1,1,1)
  - ARIMA (2,1,2)
  - SARIMA (1,1,1)(1,1,1,52)
- Selected SARIMA as the final model based on MAE and RMSE

---

## 📊 Model Evaluation

| Model               | MAE (₹)     | RMSE (₹)    |
|--------------------|-------------|-------------|
| ARIMA(1,1,1)        | 3,063,005   | 3,711,065   |
| ARIMA(2,1,2)        | 3,178,152   | 3,777,270   |
| **SARIMA(1,1,1)(1,1,1,52)** | **2,971,262** ✅ | **3,625,030** ✅ |

---

## 🔧 Tools & Libraries

- Python
- pandas, matplotlib, numpy
- statsmodels (for ARIMA/SARIMA)
- scikit-learn (for evaluation metrics)

---

## 📁 Files Included

- `demand_forecasting.ipynb` – Jupyter notebook with full code
- `final_forecast.csv` – Forecasted demand for the next 52 weeks
- `README.md` – Project documentation

---

## 📌 How to Use

1. Clone the repo or download the files
2. Open the Jupyter notebook and run all cells
3. Modify the code if you'd like to forecast your own time series

---

## 🚀 Future Improvements

- Automate model tuning with grid search or AIC-based selection
- Integrate external regressors (price, promotions, etc.)
- Build an interactive dashboard using Streamlit or Plotly Dash

---

## 👩‍💻 Created by

Sanika Mungekar  
