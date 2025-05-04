# 📈 Coca-Cola Stock Price Analysis

A comprehensive time-series analysis of Coca-Cola (KO) historical stock data aimed at deriving **insights for policy-making and strategic investment decisions**.

---

## 📂 Dataset Overview

- **Source:** Public historical stock data (Yahoo Finance or similar)
- **Period:** 1962 – 2025
- **Frequency:** Daily
- **Records:** 15,922
- **Features:**
  - `date`: Trading date
  - `open`: Opening price
  - `high`: Daily high
  - `low`: Daily low
  - `close`: Closing price
  - `adj_close`: Adjusted closing price (dividends/splits)
  - `volume`: Daily trade volume

---

## 🧹 Data Cleaning & Transformation

- Converted `date` column to datetime format
- Engineered new features:
  - `year`, `month`, `day`, `day_of_week`
  - `daily_return`: % daily change in closing price
  - `ma_30`, `ma_90`: 30- and 90-day moving averages

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Stock Trend Over Time
Line chart shows a long-term upward trend in Coca-Cola’s stock price, with volatility spikes during major economic events.

![image](https://github.com/user-attachments/assets/62bd7093-0aeb-4fc9-8478-4c4395a915e1)

### 🔹 Daily Return Distribution
Bell-shaped, but with visible outliers and fat tails—highlighting potential tail risk for short-term traders.
![image](https://github.com/user-attachments/assets/e537e2b0-aa76-4709-94b2-470b7c83f8b9)


### 🔹 Correlation Matrix
![image](https://github.com/user-attachments/assets/ae09e16a-aded-4c3c-9128-cbd5522f7f0b)


Strong positive correlation: open ↔ close, high ↔ low

Slight inverse correlation: daily returns ↔ volume


---

## 📅 Annual Performance Summary

| Year | Avg Close | Max Close | Min Close | Avg Volume |
|------|-----------|-----------|-----------|------------|
| 2021 | $54.08    | $59.21    | $48.15    | 15.8M      |
| 2022 | $61.68    | $66.21    | $54.39    | 16.0M      |
| 2023 | $59.87    | $64.30    | $52.38    | 13.7M      |
| 2024 | $63.98    | $73.01    | $58.06    | 13.9M      |
| 2025 | $67.08    | $73.18    | $60.81    | 18.3M      |

---

## 🔍 Insights for Policy & Investment Strategy

### ✅ Best Performing Years (Average Daily Return)

| Year | Avg Daily Return |
|------|------------------|
| 1989 | +0.229%          |
| 1991 | +0.227%          |
| 1975 | +0.195%          |
| 2025 | +0.192%          |
| 1982 | +0.175%          |

### ⚠️ Worst Performing Years

| Year | Avg Daily Return |
|------|------------------|
| 2004 | -0.073%          |
| 1979 | -0.088%          |
| 2001 | -0.091%          |
| 2008 | -0.096%          |
| 1974 | -0.308%          |

---

## 📌 Most Volatile Days

### 🔼 Top 5 Daily Gains
| Date       | Daily Return |
|------------|--------------|
| 1987-10-20 | +19.67%      |
| 2008-10-13 | +13.88%      |
| 1987-10-21 | +13.01%      |
| 2008-10-28 | +10.34%      |
| 2000-03-15 | +9.81%       |

### 🔽 Top 5 Daily Losses
| Date       | Daily Return |
|------------|--------------|
| 1987-10-19 | -24.69%      |
| 1974-11-18 | -11.14%      |
| 1974-09-27 | -10.96%      |
| 1998-08-31 | -10.48%      |
| 2002-10-16 | -10.06%      |

---

## 🧠 Policy Recommendations

- **Crisis Monitoring**: Large swings (1987, 2008) show the need for robust market circuit breakers and investor education.
- **Dividend Trust**: Peak years coincide with macroeconomic optimism and dividend reliability.
- **Pension Portfolios**: KO's long-term resilience makes it suitable for inclusion in retirement and low-risk investment portfolios.

---

## 🛠️ Tools Used

- **Python**: `pandas`, `matplotlib`, `seaborn`
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📌 How to Run

1. Clone or download the repository
2. Open the notebook `Coca-Cola_Stock_Analysis.ipynb`
3. Run all cells to reproduce the analysis
4. Dataset: `Coca-Cola Project.csv` must be present in the same directory

---

## 📬 Contact

Feel free to connect or collaborate:

- 📧 Email: thomasadjeibaidoo18@gmail.com
- 💼 LinkedIn: 

