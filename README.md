# 🫀 Kidney Transplant Digital Twin — AI-Powered Prediction System

A machine learning pipeline that predicts kidney transplant success, simulates patient deterioration, and generates counterfactual recommendations using a Digital Twin approach.

---

## 🚀 Quick Start (Google Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kruthikajimme/kruthika/blob/main/Welcome_To_Colab.ipynb)

1. Click the badge above to open in Google Colab
2. Upload your CSV dataset (optional — synthetic data auto-generates if none)
3. Run all cells

---

## 📌 Project Overview

| Feature | Details |
|---|---|
| **Domain** | Healthcare AI / Digital Twin |
| **Problem** | Predicting kidney transplant success & monitoring patient risk |
| **ML Models** | Random Forest + Gradient Boosting (Ensemble) |
| **Dataset** | Kidney Organ Supply Chain Dataset (or synthetic) |
| **Language** | Python 3 |
| **Platform** | Google Colab |

---

## 🧠 Key Features

- **Transplant Success Prediction** — Ensemble ML model (RF + GBM) with ROC-AUC scoring
- **Digital Twin Simulation** — Simulates patient health over 180 days
- **Feature Impact Analysis** — Shows which factors help or hurt outcomes
- **Counterfactual Generator** — Suggests what changes improve success probability
- **Deterioration Simulator** — Natural decline vs. intervention comparison
- **Population Statistics** — Distribution analysis across success/failure groups

---

## 📊 Output Visualizations

| File | Description |
|---|---|
| `evaluation_dashboard_1.png` | ROC Curve, Precision-Recall, Confusion Matrix |
| `evaluation_dashboard_2.png` | Probability Distribution, Feature Importance, Metrics |
| `population_stats.png` | Feature distributions — Success vs Failure |
| `feature_impact.png` | Per-feature impact on individual patient |
| `counterfactual_trajectory.png` | Optimisation path to target probability |
| `counterfactual_changes.png` | Before vs After feature changes |
| `deterioration_trajectory.png` | 180-day health trajectory |
| `deterioration_risk.png` | Risk zone analysis with rolling average |
| `deterioration_final.png` | Final probability comparison across scenarios |

---

## 🗂️ Repository Structure
kruthika/
├── Welcome_To_Colab.ipynb     # Main Colab notebook
├── kruthikajimme              # Supporting file
└── README.md                  # Project documentation

---

## ⚙️ How to Use

### Option 1 — With your own CSV
```python
CSV_PATH = "/content/Kidney_Organ_SupplyChain_RawDataset.csv"
EXPLICIT_TARGET = "transplant_success"   # your target column name
```

### Option 2 — Synthetic data (no CSV needed)
```python
CSV_PATH = None
EXPLICIT_TARGET = None
```

---

## 🧪 ML Pipeline Steps

1. **Load Data** — Real CSV or auto-generated synthetic dataset (500 samples)
2. **Preprocessing** — Label encoding, null handling, auto target detection
3. **Train Ensemble** — Random Forest (300 trees) + Gradient Boosting (200 estimators)
4. **Evaluation** — Accuracy, ROC-AUC, Precision, Recall, F1
5. **Digital Twin** — Patient-level simulation with feature impact & counterfactuals
6. **Deterioration Simulation** — 180-day trajectory with optional intervention

---

## 📦 Dependencies
scikit-learn
pandas
numpy
matplotlib
seaborn
> All dependencies auto-install in Google Colab.

---

## 👩‍💻 Team

| Name | GitHub |
|---|---|
| Kruthika | [@Kruthikajimme](https://github.com/Kruthikajimme) |

---

## 🏫 Project Info

- **Degree**: BE — Computer Science & IT
- **Year**: 4th Year, Phase 1
- **Domain**: Healthcare AI + IoT
- **Submission**: Phase 1 — 10th June 2026
