# 📊 AAPL Stock Price Analysis & Strategy Modeling

This project explores the time-series behavior of **Apple Inc. (AAPL)** stock using financial indicators, rolling statistics, and basic trading signals. The goal is to build a solid foundation for technical analysis, return modeling, and strategy development using Python.

---

## 🧠 Project Structure

### `main.ipynb`

Focuses on **data collection**, **return modeling**, and **technical indicator visualization** using:

* `yfinance` to fetch historical AAPL data
* Simple & Log returns computation
* Moving Averages (SMA-20, SMA-50)
* Rolling Volatility
* Cumulative Return Curve
* Basic Signal Generation for crossover strategies

### `challenge.ipynb`

Serves as a challenge notebook or extended experiment zone for:

* Further visualizations and validations
* Comparing strategies
* Exploratory trading signals or regression-based enhancements (based on file name context)

---

## 📦 Tech Stack

* **Python**
* **Libraries:** `yfinance`, `pandas`, `numpy`, `matplotlib`

---

## 🔍 Key Concepts Covered

### 📘 Return Metrics

* **Simple Return:**

  $$
  R_t = \frac{P_t - P_{t-1}}{P_{t-1}} = \frac{P_t}{P_{t-1}} - 1
  $$
* **Log Return (Continuous):**

  $$
  r_t = \ln\left(\frac{P_t}{P_{t-1}}\right)
  $$

### 📈 Indicators Used

* **SMA (Simple Moving Average):**
  Short-term (20-day) and Long-term (50-day)
* **Rolling Volatility:**
  20-day standard deviation of log returns
* **Cumulative Returns:**
  Simulates investment growth over time
* **Crossover Strategy Signal:**
  Basic trading logic using SMA crossovers

---

## ✅ Outputs

* Price and return plots
* Volatility trends
* SMA strategy visualization
* Cumulative return graph
* Initial signal-generation logic (long/short)

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/PranshuXI/your-repo-name.git
cd Quant Finance Day-1
```

### 2. Install dependencies
manually:

```bash
pip install yfinance pandas matplotlib numpy
```

### 3. Run the notebooks

Use Jupyter or VS Code to open and run `main.ipynb`.

---

## 📌 Future Work

* Add backtesting framework using `backtrader` or `vectorbt`
* Integrate more indicators (e.g. MACD, RSI)
* Portfolio optimization & Sharpe Ratio calculation
* Turn strategy into a reusable Python module

---

## 🧑‍💻 Author

**Pranshu Singh**
Aspiring Quant | ML + Finance Enthusiast?
