# 🧠 Trader Sentiment Behavior Analysis

This project analyzes how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and performance using real-world data from Hyperliquid and the Crypto Fear & Greed Index.

---

## 📊 Key Objectives

- Merge historical trade data with market sentiment
- Explore how sentiment affects trader PnL, leverage, and strategy
- Identify behavioral patterns in different market moods

---

## 🗃️ Dataset Description

### 1. historical_data.csv
- Account, Coin, Execution Price, Size, Side, Closed PnL, etc.
- ~210,000+ trades with timestamps

### 2. fear_greed_index.csv
- Daily sentiment scores and labels (Fear, Greed, etc.)

---

## 📈 Key Insights

- **Higher average PnL** during periods of *Greed*
- **More short trades** observed during *Fear* and *Extreme Fear*
- **Risk appetite** (via leverage/fees) increases significantly in *Extreme Greed*
- Some traders show **consistency across all sentiment types**

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `analysis_notebook.ipynb` | Jupyter notebook with full analysis |
| `merged_trader_sentiment.csv.gz` | Cleaned + merged dataset (compressed) |

---

## 🔗 How to Use

1. Download the notebook or open in Jupyter
2. Run each section for insights and visuals
3. Use merged dataset for further modeling

---

## 📥 Download Merged Dataset

> If CSV is too large on GitHub, you can also download it here:  
> [https://drive.google.com/file/d/10eiGmNpI9D7k7ylAI2gfQ3SX9zF49iB4/view?usp=sharing — if you uploaded it]

---

## 👤 Author

**Khushi Tripathi**  



