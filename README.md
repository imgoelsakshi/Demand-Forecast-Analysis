# **Electricity Demand Forecasting**

This project develops machine learning models to improve hourly electricity demand forecasting using historical demand and weather data. Accurate forecasting helps reduce imbalance fees and supports stable power supply operations.

## **Overview**

The workflow includes:

* Data preprocessing and cleaning
* Exploratory data analysis (EDA)
* Feature engineering using weather, calendar, and lag features
* Model development (Linear Regression + tree-based models)
* Model evaluation using MAE, RMSE, and MAPE
* Explainability using feature importance and SHAP
* Business impact estimation

All work is implemented in a Google Colab notebook.

## **Models**

* **Linear Regression** (baseline for interpretability)
* **XGBoost / Random Forest** (captures nonlinear patterns and seasonal trends)

## **Key Insights**

* Demand is strongly driven by previous-day and previous-week patterns
* Temperature and humidity refine predictions
* Calendar effects capture weekday/weekend behavior

## **Business Impact**

Improved forecasting can reduce imbalance fees, minimize manual adjustments, and increase operational efficiency.

## **Future Work**

* Use higher-resolution weather data
* Test deep learning models (LSTM/Transformers)
* Add probabilistic forecasting and automated retraining

