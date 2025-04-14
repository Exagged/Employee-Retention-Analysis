# Employee Retention Analysis 📈

**Dashboard Link:** [Looker Studio Dashboard](https://lookerstudio.google.com/reporting/ebaf8924-e647-4bb0-860b-1d9e1b40f7cd)

**Run the notebook here**: [Open in Google Colab](https://colab.research.google.com/drive/1fE4m31FoLCTwCr3egESpqIU2s8aSEc9l)


---

## Project Overview 📖

This analysis identifies employees at risk of leaving by leveraging predictive modeling and visualization tools on Google Cloud Platform (GCP). Insights empower stakeholders to proactively implement retention strategies.

---

## Problem Statement 🎯

Stakeholders requested a predictive solution to identify employees likely to churn, enabling targeted interventions to enhance retention.

**Key Questions:**
- What factors influence employee churn?
- Which departments face the highest churn risk?
- Which employees are most likely to leave?

---

## Methodology ⚙️

### 1. Data Collection and Preparation
- **Platform:** Google BigQuery
- **Datasets:** Historical and pilot employee data
- **Data Cleaning:** Handled missing values, encoded categorical variables (salary, department)

### 2. Exploratory Analysis and Feature Engineering
- **Tools:** Python (Google Colab, Pandas)
- **Features Analyzed:** Satisfaction level, tenure, workload, salary, department

### 3. Predictive Modeling
- **AutoML Library:** PyCaret
- **Model Selected:** Random Forest Classifier
- **Validation Approach:** 70% training data, 30% test data
- **Accuracy Achieved:** ~93%

### 4. Insights & Deployment
- Predicted churn probabilities for pilot employees
- Extracted feature importances
- Results exported back to BigQuery for visualization

---

## Dashboard Visualizations 📊

- **Primary KPI:** Churn prediction rate
- **Supporting KPIs:** Avg. satisfaction level, avg. tenure, avg. monthly hours, last evaluations
- **Churn Drivers:** Ranked feature importance (Employee satisfaction, tenure, workload)
- **Departmental Analysis:** Department-wise churn predictions
- **Interactive Filtering:** By department

---

## Key Insights & Recommendations 🔍

- **Main Churn Driver:** Low employee satisfaction
- **High-Risk Departments:** Technical, Support, Sales
- **Recommendations:**
  - Employee recognition programs to boost satisfaction
  - Professional development and training initiatives
  - Salary reviews focused on retention incentives for long-tenured employees

---

## Technologies Used 🛠

- **Cloud Platform:** Google Cloud (BigQuery)
- **Programming:** Python, PyCaret, Pandas
- **Environment:** Google Colab
- **Visualization:** Looker Studio
