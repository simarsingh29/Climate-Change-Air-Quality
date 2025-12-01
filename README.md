# Climate-Change-Air-Quality

# 📌 Overview

This project provides a comprehensive analysis of climate change patterns and air pollutant concentrations (AQI, PM2.5, NO₂, CO, O₃, SO₂).
It integrates climate data with air quality metrics, performs statistical and visual analysis, and builds machine learning models to forecast future pollution levels.

✔ Identifies pollution hotspots

✔ Detects seasonal and regional trends

✔ Builds forecasting models

✔ Generates interactive dashboards

✔ Actionable insights for policymakers & researchers

# 🎯 Objectives

- Analyze long-term pollution and climate patterns

- Explore correlations between temperature, humidity, and pollutant levels

- Predict future AQI using ML & time-series models

- Visualize trends using interactive dashboards

- Build a reusable and reproducible environment for researchers

# 🛠️ Tech Stack

| Component        | Tools                                     |
| ---------------- | ----------------------------------------- |
| Programming      | Python, SQL                               |
| Data Processing  | Pandas, NumPy                             |
| Machine Learning | Scikit-learn, XGBoost, Statsmodels, ARIMA |
| Visualization    | Matplotlib, Seaborn, Plotly               |
| Dashboard        | Streamlit / PowerBI                       |
| Forecasting      | SARIMA, LSTM (optional)                   |
| Deployment       | Streamlit Cloud                           |

# 📂 Project Structure

Climate-AQI-Analysis/
│
├── data/
│   ├── climate_data.csv
│   ├── air_quality_data.csv
│   ├── merged_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_forecasting_models.ipynb
│
├── models/
│   ├── random_forest_model.pkl
│   ├── arima_model.pkl
│
├── scripts/
│   ├── preprocess.py
│   ├── forecast.py
│   ├── visualize.py
│
├── dashboard/
│   ├── app.py
│
├── images/
│   ├── heatmap.png
│   ├── trends.png
│   ├── forecast.png
│
└── README.md

# 🤖 Machine Learning & Forecasting
# 📌 Models Used

Random Forest Regressor

- XGBoost Regressor

- SARIMA

- ARIMA

- LSTM (optional advanced)

# 🧩 Key Insights

. PM2.5 is the primary pollutant in most cities.

. AQI rises by 20–40% in winter due to temperature inversion.

. Humidity reduces ozone concentrations.

. Machine learning forecasting models show high predictive power (R² ~ 0.89).

. Interactive dashboard improves accessibility of insights.
