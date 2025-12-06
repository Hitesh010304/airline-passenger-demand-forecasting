# ✈️ Airline Passenger Demand Forecasting (1949–1962)

This project performs an end-to-end **time series forecasting** workflow on the classic Airline Passengers dataset.  
It combines **Python (SARIMA + Prophet)** for modeling and a **Tableau dashboard** for visual storytelling.

---

## 📌 Project Objectives

- Analyze historical monthly airline passenger data (1949–1960)
- Understand **trend** and **seasonality** patterns
- Build and compare **SARIMA** and **Prophet** forecasting models
- Forecast passenger demand for **1961–1962**
- Export forecast results and build a **Tableau dashboard** to present:
  - Historical trend
  - Forecasted values
  - 95% confidence intervals
  - Business insights

---

## 🗂 Repository Structure

```bash
airline-passenger-demand-forecasting/
│
├─ data/
│  ├─ AirPassengers.csv              # Original dataset
│  ├─ historical_data.csv            # Cleaned historical data (for Tableau)
│  └─ forecast_data.csv              # Forecast output (for Tableau)
│
├─ notebooks/
│  └─ airline_passenger_forecasting.ipynb    # Clean, structured analysis notebook
│
├─ reports/
│  └─ Airline Passenger Analysis & Forecast (1949–1962).pdf   # Tableau dashboard export
│
├─ README.md
└─ requirements.txt
