# Trader_Behaviour_Insights 

## 📘 Project Overview  
This project analyzes how **market sentiment** — derived from the *Fear & Greed Index* — impacts **trader performance, behavior, and profitability**.  
Using real trading and sentiment data, it explores emotional patterns behind buying and selling behavior, volatility, and profit consistency across different sentiment conditions.  

---

## 🎯 Objectives  
- Study how emotions like **fear** and **greed** affect market participation and profitability.  
- Merge **trader transaction data** with **sentiment scores** for correlation analysis.  
- Identify the impact of **time, volatility, and transitions between sentiments** on trading outcomes.  
- Derive actionable insights for **strategy optimization** and **risk management**.  

---

## 📂 Dataset Description  
1. **Fear & Greed Index Data:**  
   - Columns: `timestamp`, `value`, `classification`, `date`  
   - Represents daily market sentiment from *Extreme Fear* to *Extreme Greed*.  

2. **Historical Trader Data:**  
   - Columns: `Account`, `Execution Price`, `Size USD`, `Side`, `Timestamp IST`, `Closed PnL`, etc.  
   - Captures real trading activity, trade volume, and profitability metrics.  

---

## 🧮 Methodology  
1. **Data Cleaning & Preprocessing**  
   - Converted timestamps to consistent date formats.  
   - Merged sentiment and trade data on daily basis.  

2. **Exploratory Data Analysis (EDA)**  
   - Missing value checks, summary statistics, and sentiment distribution.  

3. **Sentiment-Based Performance Metrics**  
   - Average and total PnL, trade volume, fee structure, and side distribution (BUY vs SELL).  

4. **Statistical Analysis**  
   - ANOVA and T-Tests to test significance between sentiment groups and trading sides.  

5. **Behavioral & Temporal Insights**  
   - Hourly performance, volatility impact, correlation of trade metrics, and sentiment transitions.  

---

## 📊 Key Insights  
- **Fear** phases showed highest trade volumes but unstable profitability.  
- **Extreme Greed** delivered top average PnL with moderate risk.  
- **Neutral** sentiment ensured stability and predictable performance.  
- **Late-night and morning hours** were most profitable.  
- **Moderate volatility** yielded better results than extreme market conditions.  
- **Sentiment transitions** (e.g., *Fear → Neutral*) often led to short-term profit spikes.  

---

## 📈 Visualizations  
- Average PnL vs Sentiment  
- Total Trade Volume by Sentiment  
- PnL Distribution (BUY vs SELL)  
- Correlation Heatmap of Trade Metrics  
- Hourly Trading Patterns  
- Volatility Impact Scatterplot  
- Sentiment Transition Bar Chart  

*(All plots generated using Python, Matplotlib, and Seaborn.)*  

---

## 🧩 Tools & Libraries  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)  
- **Jupyter / VS Code** for development  
- **CSV datasets** for historical trade and sentiment data  

---

## 🧠 Conclusion  
Market sentiment strongly influences trading outcomes.  
Traders aligning their strategy with **sentiment cycles**, **volatility trends**, and **optimal trading hours** can improve overall profitability while minimizing emotional bias.  

---

## 📁 Repository Structure  
├── fear_greed_index.csv

├── historical_data.csv

├── Trade_Analysis_report.pdf

├── Trade_Analysis_code.pdf

├── Trade_Analysis.ipynb

├── README.md



---

## 💼 Author  
**Rakesh Pathlavath**  
📧 rakeshpathlavath07@gmail.com 

💻 GitHub: https://github.com/RakeshPathlavath07
