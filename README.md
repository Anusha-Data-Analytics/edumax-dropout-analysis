# EduMax Dropout Analysis

## 📌 Business Problem
Understanding why users drop out of courses and identifying key factors affecting retention.

---

## 📊 Project Overview
This project analyzes user behavior in an EdTech platform by combining multiple datasets including users, enrollments, sessions, and courses.

---

## ⚙️ Approach
- Data cleaning and preprocessing
- Feature engineering (session count, time spent, avg duration)
- Behavioral segmentation (Binge, Moderate, Consistent, Low Engagement)
- Dropout analysis across categories, user segments, and age groups

---

## 🔍 Key Insights
1. Identified a non-linear engagement pattern where users with high session duration (~65+ mins) showed higher dropout (~70%+), challenging the assumption that more engagement improves retention

2. Discovered multi-stage churn behavior, with peak dropout occurring at early engagement (3–4 sessions) and mid-engagement (100–300 mins), revealing critical retention gaps across the user journey

3. Designed a behavioral segmentation framework (Binge, Moderate, Consistent, Low Engagement) and showed that high-intensity, irregular usage leads to higher churn than low engagement, indicating burnout-driven dropout

4. Built a two-layer analytical dashboard (business + behavioral) linking course categories with user behavior, identifying Competitive courses as the largest contributor to total dropout despite not having the highest dropout rate

5. Transformed raw multi-source data into decision-ready insights, enabling identification of fatigue-driven churn and engagement inefficiencies across user segments

---

## 📈 Dashboard
![Overview Dashboard](dashboard_overview.png)
![User Behaviour Analysis](user_behaviour_analysis.png)

---
## 📊 Power BI Dashboard File

Download and open the dashboard in Power BI Desktop:

[Download Dashboard](./Edumax_Dashboard.pbix)

---

## 🛠 Tools Used
- Python (Pandas)
- Power BI
- Data Visualization
- Business Analysis

---

## 🚀 Future Work
- Build predictive model for dropout
- Add time-based user journey analysis


EduMax Dropout Analysis & Behavioral Analytics
📌 Business Problem

Understanding why users drop out of online courses and identifying behavioral patterns affecting retention and engagement.

📊 Project Objective

Analyze multi-source EdTech platform data to:

identify churn drivers
study user engagement behavior
build behavioral segmentation
generate actionable business insights
🛠 Tools & Technologies
Python (Pandas, NumPy)
Power BI
Data Visualization
Exploratory Data Analysis (EDA)
KPI Analysis
📂 Dataset Used

The project combines multiple datasets including:

users
sessions
enrollments
courses
payments
assessments
⚙️ Key Analysis Performed
Data cleaning & preprocessing
Feature engineering
Behavioral segmentation
Churn analysis
KPI analysis
Dashboard development
🔍 Key Business Insights
✅ High engagement ≠ high retention

Users with very high session duration (~65+ mins) showed significantly higher dropout rates.

✅ Multi-stage churn behavior identified

Peak dropout occurred during:

early engagement (3–4 sessions)
mid engagement (100–300 mins)
✅ Behavioral segmentation revealed burnout-driven churn

High-intensity irregular learners had higher churn than low-engagement users.

✅ Competitive courses contributed highest total dropouts

Despite not having the highest dropout rate individually.

📈 Dashboard Preview
Executive Dashboard

User Behavior Analysis

📊 Power BI Dashboard

The .pbix dashboard file is included in this repository.

File:

Edumax_Dashboard.pbix
🚀 Business Impact

This analysis helps:

identify retention gaps
optimize engagement strategies
improve course-level performance
support data-driven business decisions
🔮 Future Improvements
Predictive churn modeling
Time-series engagement analysis
Personalized retention strategy recommendations
