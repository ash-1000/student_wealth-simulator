# 💰 Student Wealth Simulator

**Build smart portfolios. Understand risk. Visualize your financial future.**

---

## 📌 Overview

The **Student Wealth Simulator** is an interactive web application built using Streamlit that helps users explore how different investment strategies can impact long-term wealth.

By combining real historical stock data with portfolio allocation and compounding logic, this app allows users to simulate realistic financial growth scenarios and understand the relationship between **risk, diversification, and returns**.

---

## 🚀 Features

* 📊 **Portfolio Builder**
  Create a custom portfolio by selecting stocks and assigning weight percentages.

* 📈 **Real Market Data**
  Uses historical stock data via Yahoo Finance (`yfinance`) for realistic return estimation.

* 💹 **Wealth Simulation**
  Calculates long-term wealth using compound growth based on portfolio performance.

* ⚖️ **Risk Indicator**
  Classifies portfolios as:

  * 🛡️ Conservative
  * ⚖️ Balanced
  * 🚀 Aggressive

* 🧠 **Portfolio Insights**
  Provides contextual feedback on diversification and stability.

* 📉 **Stock Explorer**
  View recent performance of selected stocks.

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **yfinance**
* **matplotlib**
* **pandas / numpy**

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/student-wealth-simulator.git
cd student-wealth-simulator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
streamlit run finance_app.py
```

---

## 🧠 How It Works

1. Historical price data is fetched for selected stocks (typically 5 years).
2. The app calculates **CAGR (Compound Annual Growth Rate)** for each asset.
3. Portfolio returns are weighted based on user allocation.
4. Monthly investments are compounded over time to estimate final wealth.

---

## ⚠️ Important Disclaimer

> This application is intended **for educational and informational purposes only**.

* It does **not** provide financial or investment advice.
* Returns are based on **historical data**, which does not guarantee future performance.
* Real markets are influenced by unpredictable factors such as:

  * economic changes
  * global events
  * company-specific risks

Users should **not rely on this tool for actual investment decisions** and are encouraged to conduct their own research or consult a financial advisor.

---

## ✨ Key Takeaway

This tool is designed to help you understand:

> “How different investment choices *could* impact long-term wealth — not what *will* happen.”

---

## 👩‍💻 Author

**Aashritha G**
Built as a learning project to explore finance, data, and real-world applications of programming.

---

## 📌 Future Improvements (Optional)

* Benchmark comparison (NIFTY / S&P 500)
* Volatility-based risk scoring
* Scenario analysis (best / worst case)
* UI enhancements & deployment

---
