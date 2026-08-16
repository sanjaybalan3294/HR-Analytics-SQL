# `HR_ANALYTICS.sql` – SQL queries used to analyze employee attrition, compensation, departments, job roles, overtime, work experience, and employee satisfaction.

## 📊 Project Overview

This project analyzes employee data using MySQL and SQL to generate
business insights related to employee attrition, salary, departments,
job roles, overtime, work experience, work-life balance, and promotions.

The analysis covers employee attrition rate, salary by job role,
hourly rate analysis, income comparison, department-level experience,
work-life balance, overtime, and the relationship between attrition
and years since last promotion.

## 🛠️ Tools & Technologies

- MySQL
- SQL

## 🔍 Business Questions

The project answers the following business questions:

1. What is the total number of employees?
2. What is the employee attrition rate?
3. What is the average salary for each job role?
4. What is the average hourly rate of male Research Scientists?
5. How does attrition relate to monthly income?
6. What is the average working experience for each department?
7. What is the average work-life balance for each job role?
8. How does attrition rate vary based on years since the last promotion?
9. How many employees work overtime?
10. Which employee has the highest monthly income?

## 💻 SQL Concepts Used

- SELECT
- COUNT()
- AVG()
- SUM()
- MIN()
- MAX()
- CASE Statements
- JOIN
- GROUP BY
- ORDER BY
- WHERE
- Subqueries
- Conditional Aggregation
- ROUND()
- LIMIT

## 📈 Analysis Results

### Employee & Attrition Analysis

| Analysis | Result |
|---|---:|
| Employee Records Analyzed | 25,000+ |
| Overall Attrition Rate | 50.21% |

### Attrition & Monthly Income

The analysis compared monthly income between employees who stayed
and employees who left the organization.

| Analysis | Result |
|---|---:|
| Income Range Observed | $25.8K – $26.4K |
| Attrition vs Income | Compared using AVG, MIN, MAX and SUM |

### Department Analysis

Calculated average working years across departments using SQL
JOIN and aggregation.

| Analysis | Result |
|---|---|
| Department Working Experience | Calculated using AVG(TotalWorkingYears) |
| Department Attrition | Compared using conditional aggregation |

### Job Role Analysis

Analyzed salary and work-life balance across different job roles.

| Analysis | Result |
|---|---|
| Average Salary by Job Role | Calculated using AVG(MonthlyIncome) |
| Work-Life Balance by Job Role | Calculated using AVG(WorkLifeBalance) |

### Work-Life Balance

The analysis identified differences in work-life balance across
job roles.

| Analysis | Result |
|---|---:|
| Lowest Work-Life Balance Segment | Sales |
| Sales Work-Life Balance Score | 2.469 / 5.0 |

### Attrition & Promotion Analysis

Analyzed employee attrition rates based on the number of years
since the employee's last promotion.

| Analysis | Result |
|---|---|
| Promotion Factor | Years Since Last Promotion |
| Analysis Method | Conditional Attrition Rate |

### Overtime Analysis

Analyzed the number of employees working overtime using SQL
filtering on the `OverTime` field.

### Highest Monthly Income

Identified the employee with the highest monthly income using
`ORDER BY MonthlyIncome DESC` and `LIMIT 1`.

## 🔍 Key Insights

- Analyzed **25,000+ employee records** to understand workforce
  trends and employee attrition.
- Identified a **50.21% company-wide attrition rate** through SQL
  aggregation and conditional calculations.
- Compared employee attrition with monthly income and observed a
  relatively narrow income range of approximately **$25.8K–$26.4K**.
- Analyzed employee working experience across different departments
  using SQL JOIN and AVG functions.
- Compared work-life balance across different job roles.
- Identified **Sales** as the lowest work-life-balance segment with
  a score of **2.469/5.0**.
- Evaluated the relationship between **years since last promotion**
  and employee attrition.
- Analyzed overtime employees to understand its relationship with
  workforce attrition.
- Compared average salary across different job roles using SQL
  aggregation.
- Identified the employee with the highest monthly income using
  sorting and `LIMIT`.

## 🎯 Key Skills Demonstrated

- SQL Data Analysis
- Data Aggregation
- Data Filtering
- JOIN Operations
- Conditional Aggregation
- Employee Attrition Analysis
- Salary Analysis
- Department Analysis
- Job Role Analysis
- Workforce Analysis
- Business Insight Generation

## 📁 Project Files

- [HR Analytics SQL Queries](./HR_ANALYTICS.sql) – SQL queries used
  to perform the complete HR analytics analysis.

## 👤 Author

**Sanjay Balan**
