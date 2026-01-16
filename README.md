# Retail Sales Forecasting Dashboard

This project focuses on forecasting future retail sales using historical transaction data and presenting the results through an interactive business intelligence dashboard.

The goal of the project is to help retail businesses understand past sales trends, anticipate future demand, and support data-driven planning decisions.

---

## 📊 Project Overview

- Historical retail sales data was cleaned and aggregated at a monthly level
- A time-series forecasting model was built using Facebook Prophet in Python
- Forecasted sales along with confidence intervals were generated
- An interactive Power BI dashboard was created to visualize:
  - Historical sales trends
  - Future sales forecasts
  - Uncertainty ranges
  - Key decision-support metrics

To maintain clarity and readability, historical actual sales and future forecasts are visualized in separate charts.

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, Prophet)
- **Jupyter Notebook** (data cleaning, EDA, forecasting)
- **Power BI Desktop** (dashboard creation)
- **CSV** files for data exchange
- **GitHub** for version control and documentation

---

## Repository Structure

data/
├── superstore.csv
└── processed/
    ├── monthly_actuals.csv
    └── sales_forecast.csv

notebooks/
└── sales_analysis.ipynb

powerbi/
└── Retail_Sales_Forecasting_Dashboard.pbix

requirements.txt
README.md

---

## 📈 Dashboard Features

- Historical sales trend (monthly)
- Sales forecast with upper and lower confidence bounds
- KPI cards for average and peak forecasted sales
- Time-based slicer for interactive exploration
- Clear separation of historical and forecasted views for readability

---

## 🔍 Methodology

1. Cleaned and structured historical sales data
2. Aggregated sales at a monthly level
3. Built a time-series forecasting model using Prophet
4. Generated future sales predictions with confidence intervals
5. Visualized insights using Power BI

---

## ⚠️ Limitations & Future Scope

- Forecasting was performed at an aggregate sales level
- Category-wise or region-wise forecasts were not included
- Future improvements could include:
  - Segment-level forecasting
  - Model comparison (ARIMA, XGBoost)
  - Deployment via Power BI Service or web-based dashboards

---

## 📌 How to Use

1. Run the Jupyter notebook to reproduce the forecasting results
2. Use the generated CSV files in the `data/processed` folder
3. Open the Power BI `.pbix` file to explore the interactive dashboard

---

## 📄 Author

**Tanmay Kumar**  
Student | Aspiring Data Analyst  