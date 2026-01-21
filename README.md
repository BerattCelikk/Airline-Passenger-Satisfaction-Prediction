<div align="center">

<img src="https://images.unsplash.com/photo-1436491865332-7a61a109cc05?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=60" width="650" alt="Airline Header" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">

# ✈️ Airline Passenger Satisfaction
**Predictive Intelligence for Enhancing In-Flight Experience**

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![CatBoost](https://img.shields.io/badge/CatBoost-GBDT-FF6F00?style=flat-square&logo=catboost&logoColor=white)](https://catboost.ai/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Production--Ready-brightgreen?style=flat-square)]()

---

[Project Overview](#-project-overview) • [The Data](#-the-data) • [Technical Methodology](#-technical-methodology) • [Benchmarks](#-performance-benchmarks) • [Installation](#-installation)

</div>

## 🌐 Project Overview
In a saturated market, airlines must differentiate through service quality. This project utilizes an advanced **CatBoost Gradient Boosting** architecture to classify passenger satisfaction levels. By processing high-dimensional data from over **100,000 flights**, the model identifies critical friction points in the passenger journey, allowing for data-driven operational improvements.

## 🧠 Technical Methodology
Unlike standard classifiers, this pipeline is optimized for the categorical nature of aviation surveys:

* **Native Categorical Handling:** Leveraging CatBoost’s unique ordered boosting and categorical encoding to prevent data leakage and preserve feature importance.
* **Feature Engineering:** * Managed zero-inflated delay data (Arrival/Departure).
    * Consolidated 14+ service touchpoints into a unified satisfaction index.
* **Robust Pipeline:** Built with **Scikit-Learn** wrappers for seamless cross-validation and hyperparameter tuning.



---

## 📊 The Data
The analysis covers 22 distinct variables across three domains:
1.  **Demographics:** Age, Gender, Customer Loyalty Type.
2.  **Logistics:** Flight Distance, Class (Business/Eco), Travel Type.
3.  **Touchpoints:** Inflight Wi-Fi, Ease of Online Booking, Food & Drink, Online Boarding, Seat Comfort, Inflight Entertainment, etc.

---

<div align="center">

## 📈 Performance Benchmarks
*Rigorous evaluation conducted on ~26k test samples*

| Metric | Score | Confidence |
| :--- | :---: | :---: |
| **Accuracy** | **0.XX** | 🟢 High |
| **Precision** | **0.XX** | 🟢 High |
| **Recall** | **0.XX** | 🟢 High |
| **F1-Score** | **0.XX** | 🟢 High |

*Note: Replace 0.XX with your specific model results for maximum impact.*

</div>

---

## 🚀 Quick Start

### 1. Requirements

Ensure you have **Python 3.9+** and the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost
```

### 2. Deployment

```bash
git clone [https://github.com/BerattCelikk/Airline-Passenger-Satisfaction-Prediction.git](https://github.com/BerattCelikk/Airline-Passenger-Satisfaction-Prediction.git)
cd Airline-Passenger-Satisfaction-Prediction
jupyter notebook main.ipynb
```

## 📂 Architecture

```bash

.
├── catboost_info/        # Model telemetry & diagnostic logs
├── data/                 # Training and Test corpora (CSV)
├── main.ipynb            # End-to-end pipeline (EDA → Model → Eval)
└── README.md             # Technical documentation

```

<div align="center">

## 🤝 Connect & Collaborate
Berat Erol Çelik Software Engineering Student & AI Researcher
If this research helps your work, please consider giving it a ⭐!
</div>
















