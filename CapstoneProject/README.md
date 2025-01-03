This is the Capstone Project folder

# Capstone Project: Handling Market Regime Shifts

## Overview
This Capstone Project is part of my Master of Science in Financial Engineering (MScFE) program. The project focuses on identifying and handling market regime shifts using advanced machine learning techniques, including autoencoders, Transformers, and reinforcement learning. These methods aim to detect volatility anomalies, analyze transitions between volatility regimes, and evaluate the effectiveness of different trading strategies.

The project provides a comparative analysis of traditional volatility models like GARCH and novel machine learning approaches in predicting regime shifts and improving trading outcomes.

---

## Objectives
1. **Volatility Anomaly Detection**:
   - Use autoencoding techniques to detect anomalies in market volatility data.
   
2. **Regime Transition Analysis**:
   - Investigate how identified anomalies correlate with regime shifts in financial markets.
   
3. **Trading Strategy Evaluation**:
   - Test the efficacy of anomaly detection in two contexts:
     - A buy-and-hold strategy.
     - A reinforcement learning-based trading strategy.

4. **Comparative Benchmarking**:
   - Compare the performance of machine learning models with traditional methods (e.g., GARCH) in regime-switching markets.

---

## Methodology
### 1. Data Collection & Preprocessing
- **Sources**: [Describe your data sources, e.g., Yahoo Finance, Bloomberg, or proprietary datasets].
- **Processing**: Clean and preprocess the data to remove outliers, normalize values, and create time-series features.

### 2. Model Development
- **Autoencoders**:
  - Train autoencoders to identify anomalies in volatility data.
  - Measure reconstruction errors to signal potential anomalies.
- **Transformers**:
  - Implement Transformer models to capture temporal dependencies and improve anomaly detection.
- **Reinforcement Learning**:
  - Design a reinforcement learning agent that uses detected anomalies to optimize trading strategies.

### 3. Comparative Analysis
- **Baseline Model**: Use GARCH models to predict volatility and benchmark against machine learning approaches.
- **Evaluation Metrics**:
  - Precision, recall, and F1-score for anomaly detection.
  - Sharpe ratio, maximum drawdown, and cumulative returns for trading strategies.

### 4. Implementation
- **Programming Languages & Tools**:
  - Python, with libraries such as:
    - `pandas`, `numpy` for data processing.
    - `TensorFlow`/`PyTorch` for machine learning.
    - `gym` for reinforcement learning.
    - `matplotlib`, `seaborn` for visualization.
- **Hardware**:
  - [Describe the computational resources, e.g., local machine, cloud services].

---

## Folder Structure
```plaintext
CapstoneProject/
├── Code/
│   ├── data_preprocessing.py         # Scripts for data cleaning and preprocessing.
│   ├── autoencoder_training.py       # Scripts for training autoencoders.
│   ├── transformer_model.py          # Implementation of the Transformer model.
│   ├── rl_trading_agent.py           # Code for reinforcement learning strategy.
│   └── utils.py                      # Utility functions used across scripts.
├── Data/
│   ├── raw_data.csv                  # Raw data files (not uploaded to GitHub).
│   ├── processed_data.csv            # Preprocessed data ready for modeling.
│   └── README.md                     # Description of datasets and sources.
├── Results/
│   ├── plots/
│   │   ├── anomaly_detection.png     # Visualization of detected anomalies.
│   │   └── regime_transitions.png    # Regime transition analysis results.
│   ├── trading_strategy_metrics.csv  # Metrics from trading strategy evaluations.
│   └── summary_statistics.txt        # Summary of results.
└── README.md                         # This file.
