# <u>Waze Churn Prediction Project</u>
![Waze Logo](https://upload.wikimedia.org/wikipedia/commons/3/37/Waze_logo_2022.png)

**Status:** Completed | **Role:** Data Analyst (Simulation)  
**Certification:** Google Advanced Data Analytics Professional Certificate (Course 1–6)

This project simulates a real-world scenario where I act as a data analyst at Waze. The goal is to develop a machine learning model to predict user churn and generate actionable insights that support user retention strategies.

---

## Problem Statement

Waze wants to improve user retention by identifying users likely to stop using the app. Using behavioral engagement data, the task is to:

- Build a churn prediction model
- Evaluate different modeling techniques
- Communicate insights to technical and non-technical stakeholders

---
 ## 📁 Repository Structure
<pre lang="markdown">
waze-customer-churn/
├── data/ # Contains the Waze user dataset (.csv)
├── docs/ # For documentation and supporting files
├── notebooks/ # Jupyter notebooks for analysis and modeling
│  ├── 0_archive_raw_notebooks/ # Archived course notebooks
│  └── waze_churn_final.ipynb # Main polished notebook
├── visuals/ # Exported visuals (plots, charts)
└── README.md # Project overview and documentation
</pre>

---

## Workflow Overview (PACE Framework)

The project follows the PACE framework taught in the Google certification:

1. **Plan** – Define the project, scope, and stakeholders
2. **Analyze** – Perform EDA, statistical tests, and summarize insights
3. **Construct** – Build regression and machine learning models
4. **Execute** – Evaluate results and communicate to stakeholders

---

## Models & Evaluation

| Model              | Accuracy | Recall (Churn) | F1 Score (Churn) |
|-------------------|----------|----------------|------------------|
| Logistic Regression | 82.2%    | 0.07           | 0.13             |
| Random Forest       | 82.2%    | 0.07           | 0.12             |
| **XGBoost**         | 74.3%    | **0.38**       | **0.35**         |


**XGBoost outperformed other models in identifying churners.**

---

## Key Insights

- **`driving_days`** and **`n_days_after_onboarding`** are strong churn predictors
- Churn behavior is **not significantly different** between `iPhone` and `Android` users
- Early engagement is critical — churners often have fewer active days early on

---

## Business Recommendations

- Focus on improving **first 30 days** of user onboarding
- Identify and re-engage **low-driving-ratio users**
- Use a model to flag at-risk users monthly for proactive outreach

---

## Tools Used

- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- `Scikit-learn`, `XGBoost`, `SciPy`
- Jupyter Notebook (VSCode)
- Git & GitHub

---

## Certification Context

This project was developed as part of the **Google Advanced Data Analytics Professional Certificate**, and integrates learning outcomes from:

- Course 1: Foundations of Data Science  
- Course 2: Python for Analysis  
- Course 3: Translating Data into Insights  
- Course 4: Statistical Analysis  
- Course 5: Regression Modeling  
- Course 6: Machine Learning

-> View the full certification [here](https://www.coursera.org/professional-certificates/google-advanced-data-analytics)
---

## Notebook Preview

👉 [Open waze_churn_final.ipynb](https://github.com/venugvis/waze-customer-churn/blob/main/notebooks/waze_churn_final.ipynb)

---

## Contact

Made by [Vishnu Venugopal](https://www.linkedin.com/in/venugvis)  
Reach out for feedback or collaboration!