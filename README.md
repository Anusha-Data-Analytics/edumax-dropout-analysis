# EduMax Dropout Analysis

## 📌 Business Problem
Understanding why users drop out of courses and identifying key factors affecting retention.

---

## 📊 Project Overview
This project analyzes user behavior in an EdTech platform by combining multiple datasets including users, enrollments, sessions, and courses.

---

## ⚙️ Approach
1. Identified a non-linear engagement pattern where users with high session duration (~65+ mins) showed higher dropout (~70%+), challenging the assumption that more engagement improves retention

2. Discovered multi-stage churn behavior, with peak dropout occurring at early engagement (3–4 sessions) and mid-engagement (100–300 mins), revealing critical retention gaps across the user journey

3. Designed a behavioral segmentation framework (Binge, Moderate, Consistent, Low Engagement) and showed that high-intensity, irregular usage leads to higher churn than low engagement, indicating burnout-driven dropout

4. Built a two-layer analytical dashboard (business + behavioral) linking course categories with user behavior, identifying Competitive courses as the largest contributor to total dropout despite not having the highest dropout rate

5. Transformed raw multi-source data into decision-ready insights, enabling identification of fatigue-driven churn and engagement inefficiencies across user segments

---

## 🔍 Key Insights
- Competitive category contributes the highest dropout due to high enrollment
- Dropout occurs in multiple stages (early and mid engagement)
- High session duration correlates with higher dropout (fatigue effect)
- Consistent engagement performs better than binge usage

---

## 📈 Dashboard
![Overview Dashboard](dashboard_overview.png)
![User Behaviour Analysis](user_behaviour_analysis.png)

- Refer the Dynamic Dashboard : ![Dynamic Dashboard in PowerBI](Edumax_Dashboard.pbix)
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
