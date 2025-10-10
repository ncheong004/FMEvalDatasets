# 🧠 FMEvalDatasets

**FMEvalDatasets** is a curated dataset of historical price data across **equities, bonds, commodities, REITs, ETFs, cryptocurrencies, and FX**, designed for evaluating foundation models on **forecasting, regime detection, and time-series reasoning**.

The dataset provides a **structured, high-quality benchmark** for assessing the performance of foundation models—particularly large language and time-series models—on tasks involving **historical financial market data**.
It enables standardized evaluation across forecasting, anomaly detection, pattern recognition, and temporal reasoning tasks in finance.

---

## 📊 Key Features

### **Multi-Asset Coverage**

| Financial Instrument | Count | Geographic Coverage / Remarks                                  |
| -------------------- | ----- | -------------------------------------------------------------- |
| **FX**               | 8     | G7 currency pairs                                              |
| **EM FX**            | 14    | Emerging markets (Asia, Latin America, Middle East)            |
| **Equities**         | 6     | USA, Europe, Singapore, Kazakhstan                             |
| **Crypto**           | 6     | Major cryptocurrencies (e.g., BTC, ETH, BNB)                   |
| **ETF**              | 5     | Global ETFs excluding US, plus US REIT ETF                     |
| **MSCI**             | 19    | Global indices covering all continents                         |
| **Rates**            | 10    | Sovereign yields across US, Europe, Japan, Malaysia, Singapore |
| **REIT**             | 5     | Real estate investment trusts (US and China)                   |
| **Volatility**       | 22    | Volatility across the 22 FX pairs                              |

---

### **Rich Temporal Span**

* ~10 years of historical coverage
* Includes bull, bear, and high-volatility regimes for robustness testing

---

### **Evaluation-Ready Format**

* Cleaned, aligned, and normalized time series
* Organized into **train/validation/test** splits with optional rolling windows
* Optional derived features: *returns, volatility, moving averages, technical indicators*

---

### **Benchmark Tasks**

* **Price Direction Forecasting** (classification)
* **Return Prediction** (regression)
* **Volatility Estimation**
* **Market Regime Detection**
* **Event Impact Analysis** (price behavior around known market events)

---

### **Intended Use**

* Benchmarking foundation models for **financial time-series tasks**
* Evaluating **generalization** across asset classes and market conditions
* Fine-tuning or pretraining models on **market structure and dynamics**

---

### **Target Audience**

* Financial ML researchers and quantitative modelers
* Developers of **financial foundation models** (LLMs + time-series models)
* Institutions focused on **systematic trading**, **risk management**, or **macroeconomic modeling**

---
