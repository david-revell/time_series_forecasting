# Sales Forecasting with Time Series and Machine Learning

This project explores time series forecasting techniques to model weekly and monthly book sales using Nielsen BookScan data. Two well-known titles — *The Alchemist* and *The Very Hungry Caterpillar* — are used as case studies to compare classical, machine learning, deep learning, and hybrid approaches.

---

## Project Overview

The objective is to forecast book sales across two time horizons — 32 weeks (weekly) and 8 months (monthly) — and assess model performance across different methodologies. Each approach is implemented and compared using a structured, consistent evaluation framework.

**Models evaluated:**
- Classical: Auto ARIMA, SARIMA
- Machine learning: XGBoost (with lag features and tuning)
- Deep learning: LSTM (with KerasTuner optimisation)
- Hybrid: SARIMA + LSTM (sequential and parallel)

*Full PDF report included in the repo.*

---

## Key Steps

1. Resample and clean weekly sales data
2. Explore trends, seasonality, and stationarity
3. Engineer lag features and time-based inputs
4. Train and evaluate forecasting models using MAE and MAPE
5. Compare predictions across weekly and monthly aggregations

---

## Targets

- **Weekly forecast:** Final 32 weeks  
- **Monthly forecast:** Final 8 months

---

## Status

All code and analysis are contained in a single Jupyter Notebook.  
The notebook is fully annotated and includes all necessary steps for data prep, modelling, and evaluation.

