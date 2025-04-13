# Stocks-Analysis

Project Link : https://colab.research.google.com/github/BASSASRILAKSHMI/Stocks-Analysis/blob/main/Copy_of_Candlestick_Chart_Fully_Working_Final.ipynb

 📉 Stock Candlestick Chart Visualization  
Visualize Financial Data Using Candlestick Charts – Data Analysis & Visualization

This project explores stock price trends using historical financial data. It utilizes interactive candlestick charts and moving averages to highlight market behavior for major companies like Microsoft, Apple, Google, and Reliance.

---

 📌 Features of the Project:

 ✅ Data Loading & Preprocessing
- Downloading stock data from Yahoo Finance using the yfinance library  
- Handling multi-index columns and parsing date information  
- Resampling daily data into weekly summaries for better trend analysis  

 🔍 Exploratory Data Analysis (EDA)
- Descriptive statistics of Open, Close, High, and Low prices  
- Calculating moving averages (20-day and 50-day) to identify trends  
- Identifying potential support/resistance levels and volatility  

 📊 Visualizations using Plotly & Matplotlib
- Interactive daily and weekly candlestick charts  
- Overlays of moving averages to detect crossovers  
- Comparative view of multiple stocks in subplot format  

 📂 Dataset:
The data is retrieved directly from [Yahoo Finance](https://finance.yahoo.com/) for stocks including:
- MSFT (Microsoft)  
- AAPL (Apple)  
- GOOG (Alphabet/Google)  
- RELIANCE.NS (Reliance Industries)

Historical data spans from *2022-01-01 to 2024-01-01*.

---

 🛠 Technologies Used:
- Python  
- yfinance (for fetching stock data)  
- Pandas, NumPy (for data handling and calculations)  
- Plotly, Matplotlib (for visualization)  
- Google Colab (for notebook execution)


 📝 How to Use:
1. Open the Stock_Candlestick_Visualization_Final.ipynb notebook in Google Colab  
2. Run all cells to fetch stock data and generate interactive charts  
3. Modify the list of stock tickers to explore other companies  
4. Use moving average trends to study bullish/bearish signals  


 📈 Key Insights:
- Moving average crossovers effectively highlight trend reversals  
- Tech stocks like AAPL and GOOG showed strong momentum  
- Weekly charts help smooth out short-term noise for better long-term analysis  
- Comparative charts support cross-sector performance analysis


Course-end project for *Data Analysis & Visualization*.
