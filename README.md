# HR Attrition Predictive Analytics & Financial Risk Modeling - Case Study

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

## 📊 Presentation Slides

<details open>
<summary><b>📂 Click to collapse/expand presentation deck</b></summary>
<br>

![Slide 1](Presentation%20slides/1.png)
![Slide 2](Presentation%20slides/2.png)
![Slide 3](Presentation%20slides/3.png)
![Slide 4](Presentation%20slides/4.png)
![Slide 5](Presentation%20slides/5.png)
![Slide 6](Presentation%20slides/6.png)
![Slide 7](Presentation%20slides/7.png)
![Slide 8](Presentation%20slides/8.png)
![Slide 9](Presentation%20slides/9.png)
![Slide 10](Presentation%20slides/10.png)

</details>


