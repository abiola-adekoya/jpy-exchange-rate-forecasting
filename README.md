# JPY Exchange Rate Forecasting

A multi-horizon forecasting study of the Japanese Yen (JPY) against the U.S. Dollar (USD), incorporating macroeconomic and market variables.

## Project Overview

This project develops and evaluates a forecasting framework for the JPY/USD exchange rate across short-, medium-, and long-term horizons.

The analysis considers:

- Interest rate differentials
- Inflation
- Trade balance
- Geopolitical risk
- Historical exchange rates

## Methodology

The primary forecasting framework uses an **ARIMAX (ARIMA with exogenous variables)** approach to incorporate macroeconomic drivers alongside exchange-rate dynamics.

Alternative approaches, including **VAR** and **Random Forest**, were also considered for robustness.

## Model Evaluation

The forecasting model was evaluated using out-of-sample data from June–August 2025.

Evaluation metrics included:

- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Diebold-Mariano test

The ARIMAX model outperformed a naïve random-walk benchmark, with approximately **15% lower RMSE** and a **2.4% MAPE**.

## Scenario Analysis

The study evaluated the sensitivity of JPY/USD forecasts to key economic shocks:

- **+50 bps U.S. interest-rate shock:** approximately 2% USD/JPY increase
- **+2% Japan CPI shock:** approximately 2% JPY appreciation
- **Increased geopolitical risk:** approximately 5% JPY appreciation

## Tools & Techniques

- Python
- Time-Series Analysis
- ARIMAX
- VAR
- Forecasting
- Scenario Analysis
- Macroeconomic Analysis

## Author

**Abiola Adekoya**

MSc Finance | Quantitative Finance | Financial Analysis
