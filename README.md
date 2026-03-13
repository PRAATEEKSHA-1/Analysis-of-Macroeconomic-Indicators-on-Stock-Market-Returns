# Analysis-of-Macroeconomic-Indicators-on-Stock-Market-Returns
# 📊 Analysis-of-Macroeconomic-Indicators-on-Stock-Market-Returns

## 📌 Project Overview
This project investigates how major macroeconomic indicators influence the stock returns of **HDFC Bank** using econometric and time-series techniques.

The study uses monthly data from **January 2010 – August 2025** to examine whether variables such as inflation, industrial production, money supply, gold price, oil price, and exchange rate impact HDFC Bank’s stock performance.

The analysis includes **Exploratory Data Analysis, Regression Models, Stationarity Testing, VAR Modeling, and Granger Causality Tests**.

---

## 🎯 Research Questions
1. Do macroeconomic variables influence HDFC Bank stock returns?
2. Which macroeconomic variable has the strongest effect?
3. Can macroeconomic variables predict HDFC stock price movements?
4. Are the relationships stable enough for time-series models?

---

## 📂 Dataset Description

The dataset consists of **187 monthly observations** with the following variables:

| Variable | Description |
|--------|-------------|
| HDFC_Stock_Close | Closing price of HDFC Bank stock |
| CPI | Consumer Price Index (Inflation) |
| IIP | Index of Industrial Production |
| M3 | Money Supply |
| Gold_Price | Price of gold |
| Oil_Price | Price of crude oil |
| Exchange_Rate | INR/USD exchange rate |

Data characteristics:

- Monthly time-series data
- Secondary data sources
- No missing values
- Converted to **percentage returns for econometric analysis**

:contentReference[oaicite:1]{index=1}

---

## 🧪 Methodology

The following econometric techniques were used:

### 1. Exploratory Data Analysis (EDA)
- Time series visualization
- Correlation matrix
- Trend analysis

### 2. Data Preprocessing
- Conversion to **percentage returns**
- Handling non-stationarity

### 3. Stationarity Testing
- Augmented Dickey Fuller (ADF)
- KPSS Test
- Phillips Perron Test

### 4. Regression Analysis
- Ordinary Least Squares (OLS)
- Variance Inflation Factor (VIF) for multicollinearity

### 5. Time Series Modeling
- Vector Autoregression (VAR)
- Granger Causality Tests
- Forecast Error Variance Decomposition (FEVD)

---

## 📈 Key Results

### Regression Findings
- R² = **0.047**
- Only **Gold Price Returns** statistically significant

Interpretation:
- A **1% increase in gold price → ~0.069% increase in HDFC stock returns**

### Multicollinearity
- VIF values < **1.1**
- No multicollinearity detected

### Granger Causality
No macroeconomic variables significantly predict HDFC stock returns.

### Variance Decomposition
- ~80% of variation explained by stock's own shocks
- Gold explains about **6%**
- Other macro variables explain **2–4%**

---

## 📊 Main Findings

- Macroeconomic variables have **very weak influence** on HDFC stock returns.
- **Gold price shows a small but statistically significant relationship.**
- Most stock price movements are driven by **company-specific factors**.
- Evidence supports the **Efficient Market Hypothesis**.

---

## ⚠️ Limitations

- Limited sample size (187 observations)
- Monthly data may miss short-term relationships
- VAR models showed instability
- Linear models may not capture nonlinear effects

---

## 🛠️ Tools & Libraries

Python libraries used:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- arch

---


