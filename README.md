# FMEvalDatasets
A curated dataset of historical price data across equities, bonds, commodities and FX for evaluating foundation models on forecasting, regime detection, and time-series reasoning.

The *FMEvalDatasets* dataset is a structured, high-quality benchmark designed to evaluate the performance of foundation models—particularly large language and time-series models—on tasks involving **historical price data across diverse financial assets**. This dataset enables standardized evaluation across forecasting, anomaly detection, pattern recognition, and temporal reasoning tasks in finance.

**Key Features:**

* **Multi-Asset Coverage**:

  * Equities (individual stocks, indices)
  * Fixed Income (government and corporate bond yields)
  * Commodities (e.g., oil, gold, agricultural)
  * Foreign Exchange (major and minor currency pairs)

* **Rich Temporal Span**:

  * Historical coverage of 10 years
  * Includes bull, bear, and volatile market regimes for robustness testing

* **Evaluation-Ready Format**:

  * Cleaned, aligned, and normalized time series
  * Organized into train/validation/test splits with optional rolling windows
  * Optional derived features: returns, volatility, moving averages, technical indicators

* **Benchmark Tasks**:

  * **Price Direction Forecasting** (classification)
  * **Return Prediction** (regression)
  * **Volatility Estimation**
  * **Market Regime Detection**
  * **Event Impact Analysis** (price behavior around known market events)

* **Intended Use**:

  * Benchmarking foundation models for financial time-series tasks
  * Evaluating generalization across asset classes and market conditions
  * Fine-tuning or pretraining models with a focus on market structure and dynamics

**Target Audience**:

* Financial ML researchers and quantitative modelers
* Developers of financial foundation models (LLMs + time-series models)
* Institutions focused on systematic trading, risk management, or macroeconomic modeling
