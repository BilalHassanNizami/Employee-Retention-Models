# Employee Retention Analysis Project

##  Predicting Employee Attrition Using Machine Learning

It uses machine learning models to analyze HR data and predict employee attrition. The goal is to help organizations identify patterns behind employee turnover and offer data-driven recommendations for retention strategies.

---

##  Project Structure

- `HR_Attrition_Analysis.ipynb`: Complete analysis with preprocessing, modeling, evaluation, and visualizations.
- `HR_capstone_dataset.csv`: Cleaned dataset used for training/testing.
- `Final_Report.pdf`: Executive summary and stakeholder report, outlining key findings and recommendations.
- `requirements.txt`: List of required Python packages.
- `README.md`: This project overview and usage instructions.

---

##  Problem Statement

High employee turnover can be costly and disruptive. Using historical HR data, this project aims to:
- Identify key factors contributing to attrition
- Build predictive models to classify whether an employee will leave
- Recommend actionable HR policies to improve retention

---

##  Models Used

1. **Logistic Regression** – as a baseline for interpretability  
2. **Decision Tree Classifier** – to capture non-linear patterns  
3. **Random Forest Classifier** – for improved performance and generalization  

---

##  Key Findings

- Employees with **low satisfaction**, **high evaluation scores**, and **excessive working hours** were more likely to leave.
- Those with **multiple projects** and **over 4 years** in the company also showed higher attrition risk.
- Random Forest outperformed other models with:
  - Accuracy: **97.7%**
  - Precision: **97.6%**
  - Recall: **92.5%**
  - F1-score: **95.0%**
  - AUC: **98.1%**

---

##  Recommendations

- Limit project overload
- Reward long-term employees
- Adjust promotion and overtime policies
- Recalibrate performance evaluations

---

##  Requirements

Install dependencies using:

```bash
pip install -r requirements.txt

---

## Analyst
**Bilal Hassan Nizami**
