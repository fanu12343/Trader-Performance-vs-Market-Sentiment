# 📈 Trader Performance vs. Market Sentiment Analysis

## 🎯 Objective

The goal of this analysis is to explore the relationship between **market sentiment** (measured by the Fear/Greed Index) and **trader behavior/performance**.  
The project aims to identify how emotional market cycles impact profitability and decision-making.

### Key Areas of Analysis

- **Profitability:** Evaluating PnL (Profit and Loss) and Win Rates  
- **Trading Behavior:** Analyzing position sizing and long/short bias  
- **Sentiment Influence:** Correlating performance with market sentiment classifications  
- **Predictive Modeling:** Developing a model to estimate trade profitability  

---

## 📊 Datasets

The analysis utilizes two primary data sources:

### 1. Market Sentiment Data
Contains the Fear/Greed Index with daily values and classifications such as:
- Extreme Fear  
- Fear  
- Neutral  
- Greed  
- Extreme Greed  

### 2. Historical Trader Data
Includes detailed transaction logs such as:
- Execution prices  
- Position sizes  
- Trade side (Buy/Sell)  
- Closed PnL  
- Timestamps  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Environment:** Google Colab  

### Libraries Used
- `pandas` → Data manipulation and cleaning  
- `matplotlib` → Data visualization  
- `seaborn` → Statistical visualizations  

---

## ⚙️ Methodology

### 1. Data Cleaning & Preparation
- Both datasets were inspected and confirmed to have **no missing values**
- Timestamps were converted to standard `datetime` format
- A common **date column** was created to merge sentiment data with trade data

---

### 2. Analysis & Insights (Selected Findings)

#### 📈 Extreme Greed Efficiency
- Traders tend to achieve **higher win rates** during *Extreme Greed* conditions  
- Preference observed for **short positions with smaller position sizes**

#### 📉 Extreme Fear Risks
- *Extreme Fear* conditions often lead to:
  - Emotionally driven decisions  
  - Lower win rates  
  - Overuse of long positions (often poorly timed)

---

## 📌 Trading Rules of Thumb

Based on the analysis:

- 🎯 **Focus on Precision:**  
  In greed-heavy markets, prioritize smaller and more precise trades  

- ⚖️ **Avoid Directional Bias:**  
  During extreme fear, avoid heavy long positions  

- 🧠 **Consider Hedging:**  
  Use contrarian or risk-managed strategies during volatile sentiment phases  

---

## 🚀 Future Improvements

- Build predictive ML models for trade outcome prediction  
- Add real-time sentiment tracking  
- Develop a dashboard for live monitoring of trader performance vs sentiment  
