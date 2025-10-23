# Trader Behavior vs Market Sentiment  
**Candidate:** Tushar Singh  

---

## 📘 Overview  
This project analyzes the relationship between trader performance and overall Bitcoin market sentiment (Fear vs Greed).  
The objective is to uncover behavioral patterns — such as changes in leverage, trade volume, and profitability — across different sentiment regimes.

---

## 📊 Datasets  
1. **Historical Trader Data (Hyperliquid)**  
   - Columns: account, coin, execution price, size tokens/USD, side, timestamp, closedPnL, etc.  
   - Source: `historical_data.csv`

2. **Fear & Greed Index**  
   - Columns: Date, Classification (Fear / Greed)  
   - Source: `fear_greed_index.csv`

---

## ⚙️ Methodology  
1. Cleaned and normalized both datasets (handled inconsistent numeric formats and timestamps).  
2. Parsed timestamps (IST → UTC) and merged trades with daily sentiment classification.  
3. Engineered features:
   - `closedPnL`, `pnl_per_size`, `is_profit`, `leverage`, and `trade_volume`.  
4. Conducted exploratory data analysis (EDA):
   - Distribution of trades under Fear vs Greed.  
   - Leverage and PnL comparisons.  
   - Daily profitability and win rates.  
5. Generated visualizations for sentiment-driven trading insights.

---

## 📈 Key Insights  
- Traders showed **higher leverage and larger trade volumes** during *Greed* phases.  
- **Average PnL** slightly increased in Greed periods, but volatility and losses rose too.  
- During *Fear* phases, traders traded less frequently but achieved higher win rates.  
- These findings suggest potential for **sentiment-aware trading strategies** that adjust leverage and position sizing dynamically.

---

## 📁 Deliverables  
| File / Folder | Description |
|----------------|-------------|
| `notebook_1.ipynb` | Main analysis notebook (Google Colab) |
| `csv_files/` | Processed datasets & aggregated summaries |
| `outputs/` | Generated graphs and visualizations |
| `ds_report.pdf` | Final 2-4 page report summarizing results |
| `README.md` | This documentation file |

---

## 🚀 How to View  
- **Colab Notebook:** [View in Colab](https://colab.research.google.com/drive/1SyRN4qZ3NummEFjdSM3HONqWkm0uLlyO?usp=sharing)  
- **GitHub Repository:** [ds_TUSHAR_SINGH](https://github.com/tushars69/ds_TUSHAR_SINGH)

---

## 🧠 Conclusion  
This analysis demonstrates how sentiment affects trader behavior and profitability in crypto markets.  
Incorporating sentiment indicators like the Fear & Greed Index into risk-management systems can help traders reduce losses during high-Greed periods and exploit opportunities during Fear cycles.

---

### 🏷️ Author  
**Tushar Singh**  
Candidate — *Junior Data Scientist (Trader Behavior Insights)*  
Email: tusharsingh8734@gmail.com  

