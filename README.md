# 📊 TCS Stock Data Analysis and Prediction

This repository contains an **end-to-end Machine Learning & Deep Learning project** for analyzing and predicting the stock price of **Tata Consultancy Services (TCS)** using historical data.

---

## 🚀 Project Overview
The project demonstrates:
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Visualization of stock trends  
- Feature engineering (lag features, moving averages, time-based features)  
- Predictive modeling with **Linear Regression** and **LSTM**  
- Model evaluation and comparison  

---

## 📂 Dataset
The dataset includes:
- **Date**: Trading date  
- **Open, High, Low, Close**: Stock price values  
- **Volume**: Number of shares traded  
- **Dividends**: Dividend payouts  
- **Stock Splits**: Number of stock splits  

> 📌 Data files: `TCS_stock_history.csv`, `TCS_stock_action.csv`, `TCS_stock_info.csv`

---

## 🛠️ Tools & Libraries
- **Languages:** Python, SQL, Excel  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras  
- **IDE:** Jupyter Notebook, VS Code  

---

## 📊 Exploratory Data Analysis
- Trend visualization (Open/Close/High/Low prices)  
- Volume, Dividends, Stock Splits over time  
- Moving averages (30-day, 50-day, 200-day)  
- Heatmaps & correlations  
- Distribution of daily percentage change  

---

## 🤖 Modeling
- **Linear Regression**  
  - Features: Open, High, Low, Volume, Previous Close, Month, Day of Week  
  - Evaluation: Mean Squared Error (MSE), R² Score  

- **LSTM Neural Network**  
  - Sequential model with time-series reshaping  
  - Trained with 30 epochs, batch size 15  
  - Evaluation: Mean Absolute Error (MAE ≈ 69.5)  

---

## 📈 Results
- High correlation among Open, High, Low, and Close prices  
- Moving average crossovers identified trading signals  
- LSTM model provided better predictive accuracy compared to Linear Regression  

---

## 🔮 Future Scope
- Hyperparameter tuning for LSTM  
- Use of Random Forest, XGBoost, and ARIMA  
- Incorporation of external market/news sentiment data  

---

