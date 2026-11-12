# **Employee Attrition Analysis**

## **Project Overview**

This project analyzes employee data to identify key factors associated with employee attrition, examine workforce patterns, and generate insights to support employee retention strategies and workforce planning.

## **Project Details**

- **Tools:** Microsoft Excel, Pivot Tables, Google Looker Studio
- **Dataset:** IBM HR Analytics Employee Attrition Dataset
- **Total Records:** 1,470
- **Original Columns:** 35
- **Final Clean Columns:** 21

## **Objectives**

- Identify the overall employee attrition rate.
- Analyze attrition patterns across departments and job roles.
- Examine the relationship between overtime and employee attrition.
- Evaluate how tenure and income levels relate to attrition.
- Identify employee segments with higher attrition rates.

## **Analysis Process**

### **1. Data Overview & Validation**

Performed initial data exploration and validation to assess dataset completeness, consistency, and structure.

**Key Findings:**

- 1,470 employee records were included in the dataset.
- No duplicate records were found.
- No missing values were identified.
- All data types were verified and standardized.
- Identified unnecessary columns that could be removed before analysis.

### **2. Data Cleaning & Preparation**

Performed data cleaning and feature engineering to prepare the dataset for further analysis.

**Key Activities:**

- Removed unnecessary columns, including EmployeeNumber, EmployeeCount, Over18, StandardHours, and HourlyRate.
- Created additional analytical features:
  - Age Group
  - Income Group
  - Years at Company Group
  - Distance Group
  - Experience Level
  - Attrition Flag
- Finalized the dataset with 1,470 records and 21 columns.

### **3. Exploratory Data Analysis (EDA)**

Used Excel Pivot Tables to examine employee attrition patterns across different workforce characteristics.

**Business Questions:**

- Which departments and job roles have the highest attrition rates?
- How does overtime relate to employee attrition?
- How does employee tenure influence attrition?
- How do income levels relate to employee attrition?
- How does business travel frequency relate to employee attrition?

**Key Findings:**

- Sales Representatives recorded the highest attrition rate at 39.76%.
- Employees working overtime had an attrition rate of 30.53%.
- Employees with 0–2 years of service recorded the highest attrition rate at 29.82%.
- Low-income employees had the highest attrition rate at 21.76%.

### **4. Employee Attrition Dashboard**

Developed an interactive dashboard using Google Looker Studio to visualize employee attrition patterns and compare workforce segments.

**Dashboard Metrics:**

- Total Employees: 1,470
- Employees Who Left: 237
- Overall Attrition Rate: 16.12%

**Key Analysis:**

- Employee Distribution by Department
- Attrition by Job Role
- Attrition by Overtime
- Attrition by Business Travel
- Attrition by Years at Company
- Attrition by Income Group

**Interactive Dashboard:**

[**View Live Dashboard – Google Looker Studio**](https://datastudio.google.com/reporting/082b7024-088b-4b2e-a91e-e2dbd149dbc0)

## **Key Business Recommendations**

- Strengthen retention programs for employees in their early career stages.
- Review workload and overtime policies to reduce employee turnover.
- Develop targeted retention strategies for high-risk job roles, particularly Sales Representatives.
- Evaluate compensation and employee support programs for lower-income employees.
- Monitor employee attrition patterns to support better workforce planning.

## **Excel Skills Applied**

- Data Exploration
- Data Cleaning & Preparation
- Data Validation
- Data Standardization
- Feature Engineering
- Pivot Tables
- Data Segmentation
- Attrition Rate Calculation
- Exploratory Data Analysis (EDA)
- Dashboard Development
- Data Visualization
- Business Insights & Recommendations

## **Project Files**

- `employee_attrition_analysis.xlsx` – Excel file containing data cleaning, feature engineering, and exploratory data analysis.
- `employee_attrition_dashboard.jpg` – Dashboard preview.
- `README.md` – Project documentation.

## **Conclusion**

The analysis identified job role, overtime, employee tenure, and income level as important factors associated with employee attrition. These findings provide insights that can help organizations develop targeted employee retention strategies and improve workforce planning.
