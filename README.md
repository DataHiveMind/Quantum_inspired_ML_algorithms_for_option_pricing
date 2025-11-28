# Quantum-Inspired Machine Learning for Option Pricing

## 📌 Overview

This repository explores **quantum-inspired machine learning algorithms** for option pricing.  
The project integrates **stochastic modeling**, **quantum kernel methods**, and **hybrid ML architectures** to evaluate derivative pricing beyond classical models such as Black-Scholes and Monte Carlo.

Key features:

- Modular **Python/C++ hybrid implementation**
- **ArcticDB** for scalable time-series storage
- **MLflow** for experiment tracking and reproducibility
- Real-time dashboards for risk and pricing visualization

---

## 🧮 Research Motivation

Traditional option pricing models often fail under:

- Non-Gaussian returns
- Volatility clustering
- Market microstructure noise

Quantum-inspired ML offers:

- Richer feature spaces via **quantum kernels**
- Hybrid classical–quantum models for **nonlinear pricing surfaces**
- Potential computational speedups in **Monte Carlo simulations**

---

## ⚙️ Project Structure

- `src/models/` → Quantum kernels, neural SDEs, hybrid ML models  
- `src/pricing/` → Classical and quantum-inspired pricing engines  
- `config/` → MLflow + ArcticDB configs  
- `docs/` → Literature review, methodology, reproducibility notes  
- `dashboards/` → Risk and pricing monitoring  

---

## 📊 Metrics (Current Placeholder Values)

| Metric                          | Value |
|---------------------------------|-------|
| RMSE (Option Price Prediction)  | NaN   |
| MAE (Option Price Prediction)   | NaN   |
| Sharpe Ratio (Strategy Backtest)| NaN   |
| PnL (Backtest, % Return)        | NaN   |
| Calibration Error (Vol Surface) | NaN   |
| Training Time (per epoch, sec)  | NaN   |
| Inference Latency (ms)          | NaN   |
| Memory Footprint (MB)           | NaN   |

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/quantum-option-pricing-ml.git
   ```

2. Create the Conda Environment:
    conda env create -f environment.yml
    conda activate quantum-option-pricing

3. Run experiments with MLflow:

    python src/experiments/train.py --config/model_params.json

## 📚 Documentation

- docs/literature_review.md → Academic grounding

- docs/methodology.md → Research methodology

- docs/reproducibility.md → Workflow + environment notes
