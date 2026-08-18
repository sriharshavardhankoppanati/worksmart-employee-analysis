# 📊 WorkSmart Employee Productivity & Laziness Analysis

## 📌 Project Overview

This project analyzes employee productivity and workplace activity patterns using **Microsoft Power BI**.

The objective is to analyze employee behavior through a **Laziness Index**, identify productivity patterns, compare work modes and departments, and provide actionable insights for HR decision-making.

The project is based on **200 employee activity records** collected over one month. Each record represents an employee's weekly activity summary.

---

## 🎯 Business Objective

The HR department of **WorkSmart Pvt Ltd** wants to understand employee productivity and identify patterns associated with workplace laziness.

The analysis focuses on:

* Employee productivity
* Task completion
* Idle and break time
* Work mode
* Social media usage
* Missed deadlines
* Meeting attendance
* Salary level
* Department-level performance
* High-laziness employees

The project uses a **Laziness Index** to categorize employee productivity.

### Laziness Categories

| Laziness Index | Category      |
| -------------- | ------------- |
| `< 0.25`       | Productive    |
| `0.25 – 0.40`  | Moderate      |
| `> 0.40`       | High Laziness |

---

## 🗂️ Dataset

The dataset contains **200 employee activity records**.

### Main Columns

* Employee_ID
* Department
* Work_Mode
* Login_Hours
* Active_Work_Hours
* Idle_Time_Hours
* Break_Time_Hours
* Tasks_Assigned
* Tasks_Completed
* Deadline_Missed
* Meetings_Attended
* Social_Media_Usage_Hours
* Performance_Rating
* Salary_Level

These fields are used to analyze employee activity, productivity and laziness patterns.

---

## 🧹 Data Modeling

The Power BI model includes calculated columns for:

* **Task Completion %**
* **Laziness Index**
* **Productivity Category**

These calculations are used throughout the dashboard to measure employee productivity and identify high-laziness patterns.

---

## 📐 DAX Measures

The project includes DAX measures for:

* Total Employees
* Average Laziness
* Average Completion %
* High Laziness Employees

These measures are used to create the dashboard KPI cards and analytical visuals.

---

## 📊 Dashboard

### 1. Executive Dashboard

The main dashboard provides an overview of employee productivity and laziness.

### KPI Cards

* 👥 Total Employees
* 📉 Average Laziness Index
* ✅ Average Completion %
* ⚠️ High Laziness Employees

### Filters

Users can filter the analysis by:

* Department
* Work Mode
* Salary Level

The dashboard requirements specify these KPI cards and slicers.

### Visualizations

The dashboard includes:

* **Laziness Index by Department**
* **Work Mode vs Productivity Category**
* **Productivity Category Distribution**
* **Login Hours vs Tasks Completed**
* **Top 10 Most Lazy Employees**

The scatter plot also uses **Social Media Usage** as the bubble size to investigate the relationship between non-work browsing and productivity.

---

## 🔎 Insights & Analysis

A dedicated **Insights & Analysis** page was created to investigate the project's key business questions.

The analysis covers:

1. Which department has the highest average laziness?
2. Is WFH more associated with laziness?
3. Does salary level impact productivity?
4. What is the relationship between social media usage and missed deadlines?
5. Who are the top 5 most productive employees?
6. Is meeting attendance affecting task completion?
7. Which department needs HR intervention?

These questions are part of the original business analysis requirements.

---

## 👤 Employee Details

A dedicated **Employee Details** drillthrough page allows users to investigate individual employee activity.

The page provides information such as:

* Employee ID
* Department
* Work Mode
* Salary Level
* Laziness Index
* Task Completion %
* Performance Rating
* Deadline Status
* Activity details
* Break time
* Idle time
* Social media usage

This allows HR users to move from high-level analysis to employee-level investigation.

---

## 🌳 Laziness Drivers Analysis

A **Decomposition Tree** is included to analyze potential drivers of employee laziness.

The analysis can be broken down using dimensions such as:

* Department
* Work Mode
* Deadline Status
* Salary Level
* Performance
* Productivity Category

This supports deeper investigation into factors contributing to higher laziness levels.

---

## ⏱️ What-If Analysis

A **What-If Parameter** was implemented to simulate the impact of reducing employee break time.

The **Break Time Reduction %** parameter allows users to test different reduction scenarios and observe the potential impact on productivity/laziness.

The project requirements specifically include a What-If parameter for simulating reduced break time.

---

## 🎨 Dashboard Features

The project includes several Power BI features:

* Interactive slicers
* KPI cards
* Conditional formatting
* Drillthrough
* Dynamic dashboard title
* Decomposition Tree
* What-If Parameter
* Interactive charts
* Employee-level analysis

High-laziness values are highlighted using conditional formatting to make potential problem areas easier to identify.

---

## 💡 Key Business Insights

The dashboard is designed to help HR answer questions such as:

* Which departments require additional attention?
* Which work mode shows higher laziness?
* How does salary level relate to productivity?
* Does social media usage contribute to missed deadlines?
* Which employees demonstrate the strongest productivity?
* Does meeting attendance influence task completion?
* Where should HR prioritize intervention?

The project therefore goes beyond visualization and provides a framework for **data-driven HR decision-making**.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* Data Modeling
* Interactive Data Visualization

---

## 📁 Project Structure

```text
WorkSmart-Laziness-Analysis/
│
├── Dataset/
│   └── Employee Activity Dataset
│
├── PowerBI/
│   └── WorkSmart_Laziness_Analysis.pbix
│
├── Screenshots/
│   ├── Dashboard.png
│   ├── Insights_Analysis.png
│   └── Employee_Details.png
│
└── README.md
```

---

## 🚀 Project Highlights

✅ 200 employee activity records
✅ Employee productivity analysis
✅ Laziness Index calculation
✅ Productivity categorization
✅ Department-level analysis
✅ Work Mode comparison
✅ Salary-level analysis
✅ Social media usage analysis
✅ Missed deadline analysis
✅ Top employee analysis
✅ HR intervention analysis
✅ Drillthrough employee details
✅ Decomposition Tree
✅ What-If analysis
✅ Interactive Power BI dashboard

---

## 📌 Conclusion

The **WorkSmart Employee Productivity & Laziness Analysis** dashboard provides an interactive approach to understanding employee productivity and workplace behavior.

By combining **Power BI, DAX, data modeling and interactive visualizations**, the project transforms employee activity data into meaningful insights that can support HR teams in identifying productivity issues and prioritizing potential interventions.

---

## 👨‍💻 Author

**Harsha**

*Data Analytics | Power BI | SQL | Python | Excel*
