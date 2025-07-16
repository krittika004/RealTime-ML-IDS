# RealTime-ML-IDS 🚀  
*A MATLAB-Python framework for real-time evaluation of ML-based Intrusion Detection Systems in cloud environments.*

---

## 📌 Overview

**RealTime-ML-IDS** is a simulation-driven benchmarking framework—built using Python and MATLAB—that evaluates machine learning-based Intrusion Detection Systems (IDS) under real-time constraints. This project introduces **CyberStrike Sim**, a cloudlet-based simulator that models live network traffic and tests IDS performance using both traditional metrics (accuracy, ROC-AUC, MCC) and operational metrics (latency, throughput).

> 📊 Supports datasets: NF-ToN IoT, NSL-KDD, UNSW-NB15  
> ⚙️ Models: Random Forest, XGBoost, Hypergraph Ensemble  
> 🔁 Traffic simulation: 290,953 cloudlets under 0.00 ms avg latency  

---

## ✨ Features

- Unified multi-dataset ML pipeline (Python)
- Protocol normalization and attack category harmonization
- Real-time inference simulation via MATLAB cloudlets
- Performance reporting (Accuracy, ROC-AUC, MCC, Cohen's Kappa)
- Latency-aware analysis for deployment-readiness

---

## 📂 Project Structure

```plaintext
RealTime-ML-IDS/
│
├── data/                  # Merged and preprocessed dataset
├── models/                # Trained models (RandomForest, XGBoost, Hypergraph Ensemble)
├── matlab_sim/            # MATLAB scripts for cloudlet simulation
├── notebooks/             # Jupyter notebooks for training and evaluation
├── results/               # Summary reports, plots, and metrics
├── utils/                 # Preprocessing, encoding, and evaluation functions
├── requirements.txt       # Python dependencies
├── README.md              # This file
