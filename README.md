# Market Regime Detection Using Unsupervised Learning

This project applies **unsupervised machine learning** techniques to identify **latent market regimes** in historical financial market data. The objective is to uncover distinct market states—such as calm growth periods, transitional phases, and crisis regimes—using only price-based features, **without any labeled outcomes**.

The project uses both **probabilistic modeling (Gaussian Mixture Models)** and **K-Means clustering** to demonstrate how different unsupervised approaches detect structure in market behavior.

---

## 📌 Project Objectives

- Engineer informative time-series features from raw market prices  
- Detect latent market regimes using unsupervised learning  
- Compare probabilistic and geometric clustering approaches  
- Interpret regimes using economic return–risk metrics  
- Validate regimes through visualization and persistence analysis  

---

## 🧠 Techniques Used

- Feature engineering on financial time series  
- Gaussian Mixture Models (probabilistic regime detection)  
- K-Means clustering (baseline method)  
- Rolling volatility, trend, and drawdown analysis  
- Regime frequency, persistence, and transition analysis  
- Economic and financial interpretation of latent states  

---

## 📂 Project Structure

market-regime-detection/
│
├── data/
│   └── sp500.csv
│
├── notebook/
│   └── market_regimes.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore


---

## 🔍 Core Features

- Daily log returns  
- 21-day rolling volatility  
- 63-day rolling return trend  
- 63-day rolling drawdown  

---

## 🤖 Models Implemented

- **Gaussian Mixture Model (GMM)** — Probabilistic regime detection  
- **K-Means Clustering** — Baseline unsupervised comparison  

---

## 📊 Evaluation Metrics

- Bayesian Information Criterion (BIC)  
- Silhouette score  
- Regime frequency  
- Regime persistence (average duration)  
- Regime-conditioned return and volatility  
- Visual regime validation on price and volatility  

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
