# 📊 Stock Portfolio Analyzer

A Streamlit-based application for analyzing and managing stock portfolios using historical data and financial metrics. The app is live and accessible at the link below:  
👉 **[Stock Portfolio Analyzer App](https://sotckportifolioapp.streamlit.app/)**

---

## 🚀 Project Overview

This application currently allows users to:
- Create and manage a portfolio of stocks with custom weights.
- Visualize historical stock price data.
- Calculate and display portfolio returns.

### 🌟 Future Features:
I'm actively working on adding advanced functionalities, including:
- **Machine Learning Models**: Predict portfolio behavior using models like Prophet or LSTM.
- **Stock Market Metrics**: Include additional financial metrics such as volatility, Sharpe ratio, and correlation.
- **Benchmark Comparisons**: Compare portfolio performance with indices like IBOV and S&P500.

---

## 🧠 Technologies Used

| Category         | Tools & Libraries                      |
|------------------|----------------------------------------|
| Web Interface    | Streamlit                              |
| Data Source      | Yahoo Finance API (via `yfinance`)     |
| Data Analysis    | Pandas, NumPy                          |
| Visualization    | Plotly                                 |
| Deployment       | Streamlit Community Cloud              |
| Database         | Firestore (used to store user-added tickers and    planned for future feature expansions) |

---

## 🗂️ Project Structure

```
stock_portfolio_app/
│
├── app.py                     # Main Streamlit app
├── requirements.txt           # Project dependencies
├── data/                      # Raw and processed data
│   └── tickers_file.csv       # List of stock tickers
├── utils/                     # Helper scripts
│   ├── data_loader.py         # Functions for data collection
│   ├── portifolio_analysis.py # Portfolio metrics and KPIs
│   ├── plots.py               # Visualization utilities
│   └── firebase.py            # Firebase integration
└── README.md                  # Project documentation
```

---

## 📦 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/stock_portfolio_app.git
cd stock_portfolio_app
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app locally
```bash
streamlit run app.py
```

---

## 🌐 Access the Production App

You can access the live version of the app here:  
👉 **[Stock Portfolio Analyzer](https://sotckportifolioapp.streamlit.app/)**

---

## 🛠️ Current Functionalities

1. **Portfolio Creation**: Select stocks and assign custom weights to create a portfolio.
2. **Historical Data Visualization**: View historical stock price data for selected tickers.
3. **Portfolio Returns**: Calculate and display daily and cumulative portfolio returns.

---

## 🔮 Future Roadmap

- **Machine Learning Integration**: Use models like Prophet or LSTM to predict portfolio behavior.
- **Advanced Metrics**: Add financial metrics such as volatility, Sharpe ratio, and correlation.
- **Benchmark Comparisons**: Compare portfolio performance with indices like IBOV and S&P500.
