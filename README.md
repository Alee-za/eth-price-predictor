# 📈 Ethereum (ETH/USDT) Market Forecasting Using ARIMA

Welcome to the **Ethereum Time Series Forecasting** project! This repository showcases a comprehensive analysis and forecasting pipeline for Ethereum prices using the ARIMA statistical model. It pulls real-time data, visualizes trends, performs ARIMA modeling, evaluates results, and generates a 30-day forecast.

---

## 🧠 Project Highlights

* Fetches ETH-USD data from **Yahoo Finance** or **CoinGecko**.
* Includes a **fallback to synthetic data** for demonstration.
* Performs **Exploratory Data Analysis (EDA)** with price trends, volume, volatility, and returns.
* Constructs and optimizes **ARIMA models**.
* Evaluates predictions with **RMSE, MAE, MAPE**.
* Visualizes **forecast and confidence intervals**.
* Provides **trading insights** and disclaimers.

---

## 🗃️ Contents

```
├── data_fetching/           <- Functions to fetch ETH data
├── preprocessing/           <- Data cleaning & feature engineering
├── eda/                     <- Plots for EDA & statistical insights
├── modeling/                <- ARIMA modeling, tuning, and diagnostics
├── forecasting/             <- 30-day forecast generation
├── utils/                   <- Metrics and helper functions
├── ethereum_30day_forecast.csv <- Output CSV forecast file
└── main.ipynb or main.py    <- End-to-end execution script
```

---



### Core Libraries

* pandas, numpy
* matplotlib, seaborn
* statsmodels
* yfinance (optional)
* requests
* scikit-learn

---

## ▶ How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/ethereum-arima-forecast.git
cd ethereum-arima-forecast
```

2. **Run the script**

```bash
python main.py
```

---

## 🔍 Key Outputs

* Optimal ARIMA parameters via **grid search**
* 30-day price **forecast** with upper/lower bounds
* Comprehensive **visualizations** for:

  * Price trends
  * Daily returns
  * Volatility
  * ACF/PACF and residuals
* **Model Evaluation Metrics**:

  * RMSE
  * MAE
  * MAPE

---

## 📉 Sample Forecast Output

```
Current Price (Last): $2,030.45
Forecast in 7 days: $2,103.58
Forecast in 30 days: $2,258.73
30-day Forecasted Change: +11.23%
```

---

## ⚠️ Disclaimers

This project is intended for **educational and research purposes** only. Forecasts are purely statistical and **do not** reflect real-time market sentiment or fundamental analysis. Cryptocurrency markets are volatile, and model-based predictions **should not be used in isolation** for financial decisions.

---

## 🧾 License

MIT License. See `LICENSE` file for details.

---

## 🤝 Contributing

Pull requests, issues, and suggestions are welcome. Feel free to fork the project and propose improvements.

---

## 🙌 Acknowledgements

* [Yahoo Finance](https://finance.yahoo.com)
* [CoinGecko API](https://www.coingecko.com/en/api)
* [Statsmodels](https://www.statsmodels.org)
* [Scikit-learn](https://scikit-learn.org)

---

## 📬 Contact

For questions or collaborations:
**HAFIZA ALIZA MUSTAFA**
[Email](aleezamustafa11@gmail.com)
[LinkedIn](https://www.linkedin.com/in/aleeza-mustafa-3105b2293/)
