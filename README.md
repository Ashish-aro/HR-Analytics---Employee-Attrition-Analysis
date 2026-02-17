# 👥 HR Analytics – Employee Attrition Analysis

## 📌 Project Overview

This project analyzes **employee attrition patterns** using a real-world HR dataset to understand **why employees leave an organization**.
The analysis focuses on **demographics, job roles, compensation, experience, satisfaction levels, and work-life balance** to support **data-driven HR decisions**.

The project uses **Excel as the data source** and **Power BI for data modeling, DAX calculations, and interactive dashboards**.

---

## 🗂 Dataset Information (Verified)

* **Source File:** `HR-Employee-Attrition.xlsx`
* **Rows:** 1,470 employees
* **Columns:** 35 HR attributes

### Attrition Breakdown

| Attrition Status | Count |
| ---------------- | ----- |
| No               | 1,233 |
| Yes              | 237   |

---

## 📊 Dataset Columns (Actual)

### Employee & Demographics

* Age
* Gender
* MaritalStatus
* Education
* EducationField

### Job & Organization

* Department
* JobRole
* JobLevel
* JobInvolvement
* BusinessTravel

### Compensation

* MonthlyIncome
* DailyRate
* HourlyRate
* MonthlyRate
* PercentSalaryHike
* StockOptionLevel

### Experience & Tenure

* TotalWorkingYears
* NumCompaniesWorked
* YearsAtCompany
* YearsInCurrentRole
* YearsSinceLastPromotion
* YearsWithCurrManager

### Satisfaction & Performance

* JobSatisfaction
* EnvironmentSatisfaction
* RelationshipSatisfaction
* WorkLifeBalance
* PerformanceRating
* TrainingTimesLastYear

### Work Conditions

* OverTime
* DistanceFromHome
* StandardHours
* Over18

### Target Variable

* **Attrition (Yes / No)**

---

## 🛠 Tools & Technologies

* **Microsoft Excel** – HR data source
* **Microsoft Power BI** – Data modeling, DAX measures, and dashboards

---

## 🔄 Data Preparation & Modeling

Performed in Power BI:

* Verified and standardized categorical fields (Attrition, Gender, OverTime)
* Converted numeric columns for aggregation and analysis
* Created calculated measures for HR KPIs
* Optimized data model for slicing by department, role, and demographics

### Key Measures Created

* Total Employees
* Attrition Count
* Attrition Rate (%)
* Average Monthly Income
* Average Years at Company

---

## 📈 Analysis & Dashboard Focus

The Power BI dashboard answers key HR questions:

### 📉 Attrition Insights

* Overall attrition rate
* Attrition by **Department and Job Role**
* Attrition by **OverTime status**

### 👥 Demographic Analysis

* Attrition by **Age group**
* Attrition by **Gender and Marital Status**

### 💰 Compensation Analysis

* Monthly income comparison between **Attrition vs Non-Attrition**
* Impact of salary hikes on retention

### 🧠 Satisfaction & Work-Life Balance

* Relationship between **Job Satisfaction and Attrition**
* Effect of **WorkLifeBalance scores** on employee retention

### 🏢 Experience & Tenure

* Attrition vs **Years at Company**
* Attrition trends for early-career vs experienced employees

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/hr-employee-attrition-analysis.git
   ```
2. Open `HR-Employee-Attrition.xlsx` to inspect raw data
3. Open `HR - Analytics Employee Attrition Analysis.pbix` in Power BI Desktop
4. Use slicers to analyze attrition by:

   * Department
   * Job Role
   * Gender
   * Overtime
   * Age

---

## 🎯 Business Value

* Identifies **roles and departments with high attrition risk**
* Highlights the impact of **overtime and satisfaction levels**
* Supports **retention strategy and workforce planning**
* Enables proactive HR decision-making

---

## 👤 Author

**Ashish Kumar**
Data Analyst | Power BI | SQL | Excel
