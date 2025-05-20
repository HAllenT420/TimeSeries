# 📈 Stock Price Forecasting with LSTM

<div align="center">
  <img src="https://img.shields.io/badge/DeepLearning-PyTorch-red" alt="DeepLearning">
  <img src="https://img.shields.io/badge/Model-LSTM-blue">
  <img src="https://img.shields.io/badge/Forecasting-TimeSeries-green">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg">
</div>

---

### 🔍 Predict future stock prices using powerful sequence models like **LSTM**, **XGBoost**, and **ARIMA**. Capture market patterns, visualize trends, and compare traditional vs deep learning approaches.

---

## 📌 Project Highlights

- 🔢 **Problem:** Forecasting daily Google stock prices.
- 🧠 **Models Used:**
  - Long Short-Term Memory (LSTM) - 🔥 Best performer
  - ARIMA - Classic statistical model
  - XGBoost - Tree-based machine learning
- 📉 **Approach:**
  - Sequence preparation using sliding windows
  - Stationarity analysis for ARIMA
  - Feature engineering for XGBoost
- 📊 **Visual Evaluation:** Compare model forecasts against actual prices

---

## 🧠 Model Comparison

| Model     | Strengths                            | Limitations                         |
|-----------|--------------------------------------|--------------------------------------|
| LSTM      | Captures temporal and nonlinear trends | Needs more data, slower to train     |
| ARIMA     | Good for stationary linear patterns    | Fails on non-stationary sequences    |
| XGBoost   | Strong tabular learner, fast training  | No sequence memory, needs features   |

✅ **Winner:** **LSTM** – Best accuracy on volatile periods and complex patterns

