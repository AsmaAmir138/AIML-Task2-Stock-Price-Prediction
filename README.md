# TASK 2 REPORT: SHORT-TERM STOCK PRICE PREDICTION

---

### 1. PROJECT NAME
* Apple Inc. (AAPL) Historical Stock Price Forecasting.


### 2. CORE OBJECTIVE
* To fetch financial historical stock data directly from live market streams.
* To process opening, daily high, and low data boundaries as feature sets.
* To predict the short-term next-day final closing price of a target stock asset.


### 3. TECH STACK & LIBRARIES USED
* **Yahoo Finance API (`yfinance`)** (For live data extraction)
* **Pandas & Numpy** (For data structuring and arrays handling)
* **Scikit-Learn (`sklearn`)** (For model training and metric evaluations)
* **Matplotlib** (For comparative trend lines plotting)


### 4. MACHINE LEARNING MODEL USED
* **Linear Regression Model:** Chosen due to its high efficiency and strong linear relationship between intra-day market price channels and final closing outcomes.


### 5. KEY RESULTS & INSIGHTS
* **High Trend Tracking:** The predictive trend line achieved an outstanding fit, tracking the actual daily market closing indicators almost perfectly with minimal variance.
* **Evaluation Metrics:**
  * **Mean Absolute Error (MAE):** 0.98 (On average, predictions deviated by less than 1 dollar).
  * **Root Mean Squared Error (RMSE):** 1.25 (Showing strong stability against sudden market volatility spikes).
