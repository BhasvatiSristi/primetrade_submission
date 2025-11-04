# 🧠 Trader Behavior vs Market Sentiment Analysis

**Author:** Bhasvati Sristi  
**Role Applied:** Junior Data Scientist – Trader Behavior Insights  
**Organization:** Web3 Trading Team / PrimeTrade.AI  

---

## 📘 Overview
This project explores how trader performance and market sentiment interact in crypto trading.  
Using the **Hyperliquid Historical Trader Data** and **Bitcoin Fear & Greed Index**, this analysis identifies patterns linking trader activity, profit, and risk-taking behavior with overall market sentiment.

---
## ⚙️ Project Workflow
1. **Data Loading & Cleaning**  
   - Converted timestamps, handled missing values, standardized column names.
2. **Data Merging**  
   - Merged sentiment data with trading data on the `Date` field.
3. **EDA (Exploratory Data Analysis)**  
   - Explored trade count, total volume, PnL, and leverage across different sentiment states.
4. **Visualization & Insights**  
   - Generated charts to visually understand trader behavior under Fear vs. Greed.
5. **Report Creation**  
   - Compiled results and insights into `ds_report.pdf`.

---

## 📈 Key Insights
- Trading activity and volume rise significantly during **Greed** phases.  
- **Fear** phases show lower leverage and smaller trade sizes, indicating risk aversion.  
- Average **PnL is higher during Greed**, suggesting sentiment-driven profitability trends.  
- Integrating sentiment signals could improve algorithmic trading strategies.

---

## 🧩 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy)** | Data cleaning and analysis |
| **Matplotlib, Seaborn** | Data visualization |
| **Google Colab** | Notebook execution |
| **GitHub / Drive** | Project submission and storage |

---
