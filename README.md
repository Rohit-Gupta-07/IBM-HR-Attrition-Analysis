# 👥 IBM HR Attrition Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-HR%20%26%20People%20Analytics-0078D4?style=for-the-badge)

---

## 📌 Project Overview

An **HR attrition analysis dashboard** built in Power BI to identify why employees are leaving IBM across departments, roles, and salary levels using **demographic, job, and satisfaction dimensions**.

**Business Question:** *Which employees are most likely to leave — and what factors are driving attrition across the organisation?*

---

## 🎯 Problem Statement

IBM's HR team needs to:
- Track **overall attrition rate** across the organisation
- Identify **high-risk departments and job roles**
- Understand the impact of **overtime, pay, and promotions** on employee exits
- Spot **at-risk employee profiles** before they resign

---

## 📊 Dataset Features

| Dimension | Description |
|---|---|
| Demographics | Age, Gender, Marital Status, Education |
| Job Details | Department, Job Role, Job Level, Business Travel |
| Compensation | Monthly Income, Salary Slab, Stock Option Level |
| Satisfaction | Job Satisfaction, Work-Life Balance, Environment Satisfaction |
| Tenure | Years at Company, Years in Role, Years Since Last Promotion |
| Target Variable | Attrition (Yes / No) |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, formatting, and preparation |
| Power BI | Interactive dashboard & DAX measures |
| DAX | Custom KPI calculations (attrition rate, headcount) |

---

## 🔍 Workflow

### 1️⃣ Data Preparation (Excel)
- Cleaned raw HR records (1,470 employees, 35 attributes)
- Standardised column names and categorical values
- Created salary slab groupings for income-level analysis

### 2️⃣ Data Modelling (Power BI)
- Loaded cleaned dataset into Power BI
- Created calculated columns (age group, tenure band, attrition flag)
- Built DAX measures for attrition rate, active headcount, and averages

### 3️⃣ Dashboard Design (Power BI)
- Overview KPI cards (attrition rate, headcount, avg income, avg tenure)
- Attrition by department, job role, and overtime status
- Demographic breakdown (age group, gender, marital status)
- Compensation and satisfaction analysis
- Tenure and promotion lag analysis

---

## 📈 Key Insights

✔ **Overall attrition rate is 16.1%** — 237 out of 1,470 employees left  
✔ **Sales Representatives** have the highest attrition rate of any job role  
✔ **Employees working overtime** are significantly more likely to resign  
✔ **26–35 age group** accounts for the largest share of departures  
✔ Most attrition is concentrated in the **lowest salary slab (up to ₹5K/month)**  
✔ Employees with **no promotion in 4+ years** show elevated exit rates  

---

## 💡 Business Impact

- Enables HR to make **data-driven retention decisions** before employees resign
- Identifies **which roles and departments** need immediate intervention
- Helps management adjust **overtime policy** to reduce avoidable exits
- Supports **compensation reviews** by showing where pay is below the retention threshold
- Guides **promotion cadence** conversations using tenure and role-stagnation data

---

## 🚀 Future Improvements

- [ ] Add predictive attrition model using Python (logistic regression)
- [ ] Integrate employee engagement survey scores
- [ ] Build department-level drill-through pages
- [ ] Deploy as live Power BI Service dashboard with HR team access

---

## 👨‍💻 Author

**Rohit Gupta**
📍 Mumbai, India | 🎓 BCA @ Amity University
🔗 [LinkedIn](https://linkedin.com/in/rohit-gupta-o7) | [GitHub](https://github.com/Rohit-Gupta-07)

---

⭐ *Found this useful? Give it a star!*
