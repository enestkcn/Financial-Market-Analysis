# 📈 Financial Market Analysis Portfolio

Welcome to my Financial Data Analysis portfolio. This repository contains end-to-end Exploratory Data Analysis (EDA) and Time-Series projects focusing on both traditional equities (BIST100) and highly volatile cryptocurrency markets.

The goal of this repository is to demonstrate proficiency in data extraction, data cleaning, feature engineering, and translating complex financial datasets into actionable business insights.

---

## 📂 Projects Included

### 1. Traditional Equities: BIST100 Portfolio Analysis
**Focus:** Correlation, Relative Growth, and Risk Management.

* **Data Extraction:** Fetched real-time data for top Turkish blue-chip stocks (THYAO, TUPRS, KCHOL) using the `yfinance` API.
* **Feature Engineering:** Normalized stock prices to a base of 100 to accurately compare 1-year relative performance.
* **Insight Generation:** Calculated daily returns and built a **Correlation Heatmap** to analyze asset relationships. Identified inversely or highly correlated assets to simulate portfolio diversification strategies.

<img width="1095" height="419" alt="bist100" src="https://github.com/user-attachments/assets/bbb4a8ff-55ad-4aba-93a3-a26da7c3c6a0" />

### 2. Cryptocurrency: Market Trends & Volatility
**Focus:** Moving Averages, Volatility, and Trend Indicators.

* **Data Pipeline:** Pulled and cleaned historical data for BTC, ETH, and SOL. Handled missing values (NaN) inherent in live APIs.
* **Technical Analysis:** Programmed algorithms to calculate 7-Day and 30-Day **Moving Averages (MA)** to filter daily noise and identify macro trends.
* **Risk Profiling:** Visualized the distribution of daily returns using seaborn histograms to assess asset volatility and market risk.

<img width="1100" height="471" alt="crypto_chart" src="https://github.com/user-attachments/assets/ea97da1d-d5f7-49ee-a917-61376de33fe9" /><img width="766" height="604" alt="crypto_heatmap" src="https://github.com/user-attachments/assets/7372d2e2-a0dd-4244-9792-459fdffc46a7" />


---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **APIs:** Yahoo Finance (`yfinance`)
* **Environment:** Jupyter Notebook

---
*Feel free to explore the folders above for the detailed code and analysis steps.*
