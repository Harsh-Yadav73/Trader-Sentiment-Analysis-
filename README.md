# 📊 Trader Behavior Insights: Impact of Market Sentiment

## 🚀 Overview

This project analyzes the relationship between **Bitcoin market sentiment (Fear vs Greed)** and **trader behavior** using historical trading data from Hyperliquid.

The goal is to uncover how market sentiment influences:

* 📈 Profitability (PnL)
* ⚖️ Risk-taking behavior (leverage, position size)
* 🔄 Trading decisions (long vs short)

By combining sentiment data with real trading activity, this analysis provides **actionable insights for smarter trading strategies**.

---

## 📂 Dataset

The analysis is based on two primary datasets:

1. **Bitcoin Market Sentiment Dataset**

   * Columns: Date, Classification (Fear / Greed)

2. **Historical Trader Data (Hyperliquid)**

   * Columns: account, symbol, execution price, size, side, time, closedPnL, leverage, etc.

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Converted timestamps to datetime format
* Handled missing values
* Extracted date for merging datasets

### 2. Data Integration

* Merged trading data with sentiment dataset on date

### 3. Feature Engineering

* Created profit indicator (`is_profit`)
* Categorized trade sizes
* Derived sentiment-based features

### 4. Exploratory Data Analysis (EDA)

* PnL distribution across sentiment
* Win rate comparison
* Leverage behavior analysis
* Trade size and position analysis

### 5. Advanced Analysis

* Correlation between leverage, size, and PnL
* Aggregated performance metrics by sentiment

---

## 📊 Key Insights

* Traders tend to perform better during **Fear markets**, showing more stable returns
* **Greed sentiment leads to over-leveraging**, increasing risk exposure
* High leverage is strongly associated with **larger losses**
* Traders exhibit **cautious behavior during Fear** and **aggressive behavior during Greed**

---

## 📉 Behavioral Patterns

* 📌 Overconfidence during Greed → higher leverage usage
* 📌 Risk-averse behavior during Fear → smaller positions
* 📌 Market sentiment significantly impacts decision-making

---

## 💡 Recommendations

* Reduce leverage during **Greed phases**
* Apply strict risk management during **high sentiment volatility**
* Use sentiment indicators to **adjust position sizing and strategy**
* Avoid emotionally driven trading decisions

---

## 📁 Project Structure

```bash
Trader-Behavior-Insights/
│── Trader Sentiment Analysis.ipynb
│── README.md
```

---

## 📌 Conclusion

This project demonstrates that **market sentiment plays a critical role in shaping trader behavior and performance**.

Incorporating sentiment-aware strategies can significantly improve decision-making, reduce risk, and enhance trading outcomes in volatile crypto markets.

---

## 📬 Submission Details

**Role:** Junior Data Scientist – Trader Behavior Insights
**Author:** Harsh Yadav
**GitHub:** https://github.com/Harsh-Yadav73/Trader-Sentiment-Analysis-

---

⭐ If you found this project insightful, feel free to explore and connect!
