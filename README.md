# Time Series Forecasting of Book Sales

This project explores time series forecasting techniques to model weekly and monthly book sales using Nielsen BookScan data. Two well-known titles — *The Alchemist* and *The Very Hungry Caterpillar* — are used as case studies to compare classical, machine learning, deep learning, and hybrid approaches.

## Objectives

- Forecast weekly book sales 32 weeks into the future
- Forecast monthly sales over an 8-month horizon
- Compare model accuracy and performance across forecasting approaches

## Models used

- **Classical:** Auto ARIMA, SARIMA
- **Machine learning:** XGBoost (with lag features and tuned pipeline)
- **Deep learning:** LSTM (Keras, with hyperparameter tuning via KerasTuner)
- **Hybrid models:** Sequential and parallel combinations of SARIMA + LSTM

## Key steps

1. Resample and clean weekly sales data
2. Explore trends, seasonality, and stationarity
3. Apply forecasting models and evaluate with MAE and MAPE
4. Compare predictions across methods and time scales (weekly vs monthly)

## Forecast Targets

- Final 32 weeks (weekly resolution)
- Final 8 months (monthly resolution)

---

📁 **Notebook**: All code and analysis is contained in the Jupyter Notebook  
📈 **Visual report**: Coming soon (to be linked)
