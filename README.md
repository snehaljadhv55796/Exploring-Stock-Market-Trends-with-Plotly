# 📈 Exploring Stock Market Trends with Plotly

## 📌 Project Overview

This project analyzes historical stock market data using **Python, Pandas, NumPy, and Plotly**.

The main objective is to explore stock price movements, trading activity, turnover, returns, and volatility through interactive visualizations.

The project uses historical stock data containing daily Open, High, Low, Last, and Close prices along with Total Trade Quantity and Turnover.

---

## 🎯 Objectives

- Analyze historical stock price trends
- Compare Opening and Closing prices
- Analyze daily High and Low prices
- Visualize stock price movements using Candlestick charts
- Analyze Total Trade Quantity
- Analyze Turnover trends
- Calculate Daily Returns
- Identify the best and worst trading days
- Calculate 20-day and 50-day Moving Averages
- Analyze stock volatility
- Perform monthly stock market analysis
- Create interactive visualizations using Plotly

---

## 📂 Dataset

The dataset contains the following columns:

| Column | Description |
|---|---|
| Date | Trading date |
| Open | Opening stock price |
| High | Highest price during the trading day |
| Low | Lowest price during the trading day |
| Last | Last traded price |
| Close | Closing stock price |
| Total Trade Quantity | Total number of shares traded |
| Turnover (Lacs) | Total trading value in lakhs |

### Dataset Size

- **Rows:** 2,035
- **Columns:** 8

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Stock Closing Price Trend

Analyzed how the closing price changed over time.

### 2. Open vs Close Price

Compared daily opening and closing prices to understand price movements.

### 3. High vs Low Price

Analyzed the daily trading range using the High and Low prices.

### 4. Candlestick Chart

Created an interactive candlestick chart using:

- Open
- High
- Low
- Close

### 5. Last Price vs Close Price

Compared the last traded price with the closing price.

### 6. Trading Quantity Analysis

Analyzed changes in Total Trade Quantity over time.

### 7. Turnover Analysis

Analyzed the stock's daily and monthly turnover.

### 8. Daily Returns

Calculated daily percentage returns using the Closing Price.

### 9. Moving Averages

Calculated:

- 20-Day Moving Average
- 50-Day Moving Average

These help identify the overall stock price trend.

### 10. Volatility Analysis

Calculated rolling volatility using daily returns to identify periods of higher price fluctuations.

### 11. Monthly Analysis

Analyzed:

- Monthly average closing price
- Monthly turnover
- Trading activity

### 12. Best and Worst Trading Days

Identified trading days with the highest and lowest daily returns.

---

## 📊 Key Visualizations

The project includes interactive Plotly visualizations such as:

- 📈 Closing Price Trend
- 📊 Open vs Close Price
- 📉 High vs Low Price
- 🕯️ Candlestick Chart
- 📈 Last vs Close Price
- 📊 Trading Quantity
- 💰 Turnover Trend
- 📈 Daily Returns
- 📉 Moving Averages
- 🔄 Volatility
- 📅 Monthly Analysis

---

## 📁 Project Structure

```text
Exploring-Stock-Market-Trends-with-Plotly/
│
├── data/
│   └── Stock_data.csv
│
├── notebooks/
│   └── Stock_Market_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
