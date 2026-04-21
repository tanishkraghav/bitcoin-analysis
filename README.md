# 📊 Bitcoin Sentiment vs Trader Performance Analysis  
### Hyperliquid Historical Data × Fear & Greed Index  

**Author:** Tanishk Raghav  
**Domain:** Data Analytics / Data Science  
**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn  

---

## 📌 Project Overview  

This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader performance** using historical trading data.

The goal is to uncover patterns in trader behavior and profitability under different market sentiments, and to derive **data-driven trading insights and strategies**.

---

## 📂 Dataset  

- **Trading Data:**  
  - ~211,000+ trades  
  - Source: Hyperliquid (2024)  
  - Includes timestamp, trade details, PnL, etc.

- **Sentiment Data:**  
  - 2,644 daily records  
  - Source: Bitcoin Fear & Greed Index (2018–2025)

---

## ⚙️ Tech Stack  

- Python 🐍  
- Pandas & NumPy (Data Processing)  
- Matplotlib & Seaborn (Visualization)  
- Jupyter Notebook  

---

## 🔍 Key Steps  

### 1. Data Loading & Preprocessing  
- Loaded trading and sentiment datasets  
- Converted timestamps and aligned data formats  
- Merged datasets on date for analysis  

---

### 2. Exploratory Data Analysis (EDA)  
- Distribution of trades and profits  
- Sentiment trend analysis  
- Identification of outliers and patterns  

---

### 3. Sentiment vs Performance Analysis  
- Compared trader profitability across:
  - Extreme Fear  
  - Fear  
  - Neutral  
  - Greed  
  - Extreme Greed  
- Identified which sentiment leads to higher/lower returns  

---

### 4. Trading Behavior Analysis  
- Trade frequency under different sentiments  
- Risk-taking patterns  
- Position sizing trends  

---

### 5. Time-Series Analysis  
- Market sentiment trends over time  
- Correlation with trading performance  
- Seasonal or cyclical behavior  

---

### 6. Insights & Strategy Recommendations  

Key findings include:

- 📉 Traders tend to perform better during **Fear/Extreme Fear** (buy opportunities)  
- 📈 Overconfidence in **Greed phases** may reduce profitability  
- ⚖️ Balanced strategies outperform emotional trading  

---

## 📊 Results & Insights  

- Sentiment significantly impacts trading behavior  
- Contrarian strategies (buy during fear, sell during greed) show potential  
- Emotional bias is a major factor in trading outcomes  

---

## 🚀 How to Run  

1. Clone the repository  
git clone <your-repo-link>

2. Install dependencies  
pip install pandas numpy matplotlib seaborn

3. Run the notebook  
jupyter notebook  

4. Open:  
bitcoin_sentiment_analysis_executed.ipynb  

---

## 📁 Project Structure  

├── bitcoin_sentiment_analysis_executed.ipynb  
├── data/  
│   ├── trades.csv  
│   └── sentiment.csv  
├── README.md  

---

## 🎯 Future Improvements  

- Apply Machine Learning models for prediction  
- Real-time sentiment integration  
- Dashboard using Power BI / Streamlit  
- Strategy backtesting  

---

## 🤝 Acknowledgment  

This project was developed as part of a **Data Analytics / Data Science assignment**, focusing on real-world financial data analysis and insight generation.

---

## 📬 Contact  

**Tanishk Raghav**  
Aspiring Data Scientist  
