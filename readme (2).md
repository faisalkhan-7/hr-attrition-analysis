# HR Attrition Analytics & Financial Risk Modeling

An end-to-end data science project utilizing machine learning to predict voluntary employee resignation and quantify corporate turnover risk. By addressing severe class imbalances, this analysis identifies critical turnover drivers (such as overtime and compensation gaps) and translates predictive insights into an actionable, multi-million dollar business retention strategy.

---

## 🚀 Key Highlights & Business Value
* **Financial Risk Quantified:** Modeled an estimated potential attrition cost of over **$6.8M** across high-risk sectors if strategic interventions are not taken.
* **Class Imbalance Addressed:** Shifted focus from deceptive baseline accuracy (~84%) to optimizing **Recall and ROC-AUC** using class-weighted algorithms to catch "quiet flight risks."
* **Actionable Retention Levers:** Identified critical, addressable turnover triggers including overtime optimization, structured career progression, and monthly income equilibrium.

---

## 📁 Project Structure
```text
hr-attrition-analysis/
├── data/
│   └── ibm_hr_attrition.csv       # Dataset used for modeling
├── notebooks/
│   ├── 01_ibm_hr_analytics_eda.ipynb            # Exploratory analysis & visualizations
│   └── 02_hr_attrition_analysis_enhanced.ipynb   # Feature engineering, modeling, & financial evaluation
├── .gitignore                     # Standard Git ignore configurations
├── requirements.txt               # List of Python dependencies
└── README.md                      # Project documentation