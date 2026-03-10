# 🏢 Employee Attrition Analysis — IBM HR Dataset

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Problem Statement
Employee attrition costs companies millions every year through recruitment, training and lost productivity. This project analyzes IBM's HR dataset of 1470 employees to identify **why employees leave** and provide actionable recommendations to HR teams to improve retention.

---

## 📂 Dataset
- **Source:** [IBM HR Analytics Attrition Dataset — Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Rows:** 1470 employees
- **Columns:** 35 features
- **Target:** Attrition (Yes/No)

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📁 Folder Structure
```
IBM_Attrition_Analysis/
│
|IBM.csv
│plot1_attrition_overview.png
│plot2_department_jobrole.png
│plot3_salary_distribution.png
│plot4_overtime_pie.png
│plot5_satisfaction_lineplot.png
│plot6_demographics.png
│plot7_business_travel.png
│plot8_correlation_heatmap.png
│IBM_Attrition.ipynb
└── README.md
```

---

## 💡 Key Insights
- 📉 Overall attrition rate is **16.1%** — 237 out of 1470 employees left
- 🚨 **Sales Representatives** have the highest attrition at **39.8%** — nearly 1 in 2 leaving
- ⏰ Overtime employees have **3x higher attrition** (30.5% vs 10.4%)
- 💰 Employees earning **below $3K** leave at 28.6% vs only 8.9% above $10K
- 👶 Age group **18-25** is most at risk with **35.8%** attrition
- ✈️ Frequent travelers have **24.9% attrition** vs 8% for non-travelers
- 💍 Single employees leave at **25.5%** vs 12.5% for married employees

---

## 📊 Visualizations

### Plot 1 — Overall Attrition Split
![plot1](plots/plot1_attrition_overview.png)

### Plot 2 — Attrition by Department & Job Role
![plot2](plots/plot2_department_jobrole.png)

### Plot 3 — Salary Distribution
![plot3](plots/plot3_salary_distribution.png)

### Plot 4 — Overtime Impact
![plot4](plots/plot4_overtime_pie.png)

### Plot 5 — Job Satisfaction & Work Life Balance
![plot5](plots/plot5_satisfaction_lineplot.png)

### Plot 6 — Demographics
![plot6](plots/plot6_demographics.png)

### Plot 7 — Business Travel
![plot7](plots/plot7_business_travel.png)

### Plot 8 — Correlation Heatmap
![plot8](plots/plot8_correlation_heatmap.png)

---

## ▶️ How to Run

1. Clone the repo
```bash
git clone https://github.com/nishhh2004/IBM_Attrition_Analysis.git
```

2. Install libraries
```bash
pip install pandas numpy matplotlib seaborn
```

3. Download dataset from Kaggle and place it in `data/` folder as `IBM.csv`

4. Open `IBM_Attrition.ipynb` in Jupyter or Google Colab and run all cells

---

## 📋 Summary Scorecard

| Metric | Value |
|---|---|
| Total Employees | 1470 |
| Employees Left | 237 |
| Attrition Rate | 16.1% |
| Highest Risk Dept | Sales (20.6%) |
| Highest Risk Role | Sales Rep (39.8%) |
| Overtime Attrition | 30.5% |
| Low Salary Attrition | 28.6% |
| Highest Risk Age | 18-25 (35.8%) |
| Strongest Predictor | TotalWorkingYears |

---

## ✅ HR Recommendations
- Fix overtime culture — limit hours and redistribute workload
- Revise entry level salaries for employees earning below $3K
- Create young talent retention program for 18-25 age group
- Review travel policies and introduce travel allowances
- Focus on Sales department with better incentives and career growth

---

## 🙋 Author
**Nishanth MS**
[LinkedIn](https://linkedin.com/in/nishanth-ms) | [GitHub](https://github.com/nishhh2004)
