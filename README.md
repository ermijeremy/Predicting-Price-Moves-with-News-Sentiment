# 📈 Predicting Price Moves with News Sentiment

This project was developed as part of the **10 Academy Artificial Intelligence Mastery – Week 1 Challenge**. The goal is to analyze the relationship between financial news headlines and stock price movements by performing sentiment analysis and technical indicator calculations. The ultimate objective is to provide data-driven investment strategy insights.

---

## 🧠 Project Objective

**Nova Financial Solutions** wants to enhance its financial forecasting by incorporating news sentiment into its analytics workflow. This project focuses on:

- Quantifying sentiment in financial news headlines
- Calculating technical indicators from historical stock data
- Correlating sentiment with stock price returns
- Proposing investment strategies based on data insights

---

## 🗂️ Folder Structure

├── .github/  
│ └── workflows/  
│ └── unittests.yml # GitHub Actions CI setup  
├── .vscode/   
│ └── settings.json # VSCode environment configs  
├── notebooks/  
│ ├── task1_eda.ipynb # EDA on headlines and publishers   
│ ├── task2_technical_analysis.ipynb  
│ └── task3_sentiment_correlation.ipynb  
├── scripts/  
│ ├── eda_utils.py  
│ ├── sentiment_analysis.py  
│ ├── indicator_calculator.py  
│ └── correlation.py  
├── src/  
│ └── init.py  
├── tests/  
│ └── test_utils.py # Optional testing scripts  
├── data/ # Raw and processed datasets (in .gitignore)  
├── requirements.txt # Project dependencies  
├── README.md # This file  
└── .gitignore  


---

## ✅ Tasks Summary

### 🔹 Task 1: Git & EDA
- Set up Python environment & GitHub CI
- Explored news headline data:
  - Headline length stats
  - Publisher frequency
  - Date-wise news volume trends
  - Common keywords and phrases
  - Domain analysis from the publisher field

### 🔹 Task 2: Technical Indicators
- Loaded OHLCV stock data
- Used `TA-Lib` and `pynance` to compute:
  - Moving Averages
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
- Visualized key indicators over time

### 🔹 Task 3: News vs Stock Correlation
- Aligned news and stock data by date
- Used `TextBlob` and `NLTK` for sentiment scoring
- Calculated daily sentiment & daily returns
- Measured correlation between sentiment and stock movement

---

## 📊 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- TextBlob
- TA-Lib, pynance
- Scipy (for correlation)
- Git, GitHub Actions, Jupyter

---
