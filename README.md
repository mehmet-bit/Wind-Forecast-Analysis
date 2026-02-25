# Greece Wind Forecast Dashboard (v14)

**Day-ahead Wind Power Forecasting System for the Greek Electricity Market** Advanced machine learning solution delivering accurate hourly wind generation forecasts using **Open-Meteo NWP** and **ENTSO-E** data.

![Wind Forecast Dashboard](Wind_Model.png)

## 📌 Project Overview
This project focuses on forecasting day-ahead wind power production in Greece with high volatility management. The system provides reliable 24-hour ahead predictions and real-time actual vs. forecast comparison for operational decision support in the Greek power market.

**Key Highlights:**
- **Feature Engineering:** Lag-120 strategy with LightGBM regressor.
- **Infrastructure:** Interactive Streamlit dashboard for real-time monitoring.
- **Coverage:** Approximately 6,000 MW of installed wind capacity in Greece.
- **Intellectual Property:** Proprietary model (code and model files are not publicly shared).

## 🏗️ High-Level System Architecture
Figure 1: End-to-end data pipeline from ENTSO-E/Open-Meteo ingestion to LightGBM inference.
![Flow Chart](Flow_Chart.png)

## 📊 Model Performance & Metrics (February 2026)

    Period: 1 – 28 February 2026

    Installed Capacity: 6,000 MW

    Total Actual Production: 2,567,636 MW·h

    Total Forecasted Production: 2,520,607 MW·h MWh

    Model Accuracy: R² = 0.85

Error Metrics:

    MAE: ≈ 322 MW

    RMSE: ≈ 406 MW

The model is fine-tuned to handle the inherent stochastic nature of wind energy in Greek geography, with a strong focus on capturing ramp-up and ramp-down events to minimize balancing costs.
## 🛠️ Tech Stack

    Core Engine: Python 3.9+

    Machine Learning: LightGBM, Scikit-learn

    Data Pipelines: ENTSO-E REST API, Open-Meteo API

    Data Science: Pandas, NumPy

    Frontend: Streamlit, Plotly

## 📝 Disclaimer & Confidentiality

This repository serves as a technical portfolio to demonstrate data engineering and machine learning capabilities in the energy sector.

    Note: The core model logic (.pkl files) and proprietary preprocessing scripts are not shared to protect intellectual property.

    Status: This is a demo version for portfolio purposes.



