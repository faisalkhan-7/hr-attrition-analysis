# HR Attrition Predictive Analytics & Financial Risk Modeling

An end-to-end data science project using the IBM HR Analytics dataset to predict voluntary employee turnover and quantify financial exposure. This project addresses severe class imbalance to isolate high-risk attrition drivers (burnout, compensation gaps) and translates machine learning classification metrics into a $6.8M data-driven corporate retention strategy.

---

## 🎯 Executive Summary & Impact
* **Financial Risk Quantified:** Modeled an estimated potential attrition exposure exceeding **$6.8M** across high-risk business units if left unmitigated.
* **Class Imbalance Engineering:** Rejected deceptive baseline accuracy (~84%) in favor of optimizing **Recall and ROC-AUC** via class-weighted algorithms to accurately capture "quiet flight risks."
* **Strategic Levers:** Isolated overtime status, monthly income equilibrium, and role-specific stagnation as the top actionable predictive features.

---

## 📁 Core Architecture
```text
├── data/ib_hr_attrition.csv         # Raw workforce features (demographics, role, tenure)
├── notebooks/
│   ├── 01_eda_visualizations.ipynb  # Statistical distributions, correlation matrices & anomalies
│   └── 02_predictive_modeling.ipynb # Synthetic balancing, pipeline training, and cost modeling
├── requirements.txt                 # Minimum environment dependencies
└── README.md                        # Project documentation
