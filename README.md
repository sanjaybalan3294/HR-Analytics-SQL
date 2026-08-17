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
| Total Employees | 50,000 |
| Overall Attrition Rate | 50.21% |
| Employees Working Overtime | 24,861 |

### Average Salary by Job Role

| Job Role | Average Salary |
|---|---:|
| Manager | 26,365.30 |
| Sales Executive | 26,131.83 |
| Sales Representative | 26,098.71 |
| Developer | 26,012.21 |
| Research Director | 26,008.09 |
| Laboratory Technician | 25,947.86 |
| Manufacturing Director | 25,937.43 |
| Healthcare Representative | 25,937.30 |
| Research Scientist | 25,916.69 |
| Human Resources | 25,794.76 |

### Male Research Scientist Analysis

| Analysis | Result |
|---|---:|
| Average Hourly Rate | 114.4469 |

### Attrition vs Monthly Income

| Attrition | Average Monthly Income | Minimum Income | Maximum Income | Total Income |
|---|---:|---:|---:|---:|
| Yes | 26,072.60 | 1,002 | 50,999 | 654,552,543 |
| No | 25,958.49 | 1,001 | 50,999 | 646,236,520 |

### Average Working Years by Department

| Department | Average Working Years |
|---|---:|
| Hardware | 20.48 |
| Support | 20.48 |
| Sales | 20.62 |
| Research & Development | 20.30 |
| Software | 20.65 |
| Human Resources | 20.45 |

### Job Role vs Work-Life Balance

| Job Role | Average Work-Life Balance |
|---|---:|
| Research Director | 2.49 |
| Sales Executive | 2.47 |
| Human Resources | 2.51 |
| Manufacturing Director | 2.50 |
| Developer | 2.51 |
| Manager | 2.50 |
| Sales Representative | 2.50 |
| Healthcare Representative | 2.51 |
| Laboratory Technician | 2.49 |
| Research Scientist | 2.51 |

### Attrition Rate vs Years Since Last Promotion

The analysis calculated attrition count, total employees, and attrition rate for **40 different years-since-last-promotion groups**.

| Years Since Last Promotion | Attrition Rate |
|---:|---:|
| 1 | 50.14% |
| 2 | 50.07% |
| 3 | 49.96% |
| 4 | 51.28% |
| 5 | 50.55% |
| 6 | 51.34% |
| 7 | 50.76% |
| 8 | 49.11% |
| 9 | 49.42% |
| 10 | 48.86% |

### Highest Monthly Income

| Employee ID | Monthly Income |
|---:|---:|
| 524 | 50,999 |
## 🔍 Key Insights

- Analyzed **50,000 employees** and identified an overall **50.21% attrition rate**.
- Found that **24,861 employees** were working overtime.
- **Managers** had the highest average salary at **26,365.30**, while **Human Resources** had the lowest at **25,794.76** among the analyzed job roles.
- Employees who left had a slightly higher average monthly income (**26,072.60**) compared with employees who stayed (**25,958.49**).
- **Software** had the highest average working experience at **20.65 years**, while **Research & Development** had the lowest at **20.30 years**.
- **Sales Executive** had the lowest average work-life balance score at **2.47**.
- Attrition rates varied across years since the last promotion, with the highest observed rate of **51.34%** at 6 years since the last promotion.
- Identified **Employee ID 524** as having the highest monthly income of **50,999**.
- Used SQL JOINs and aggregation to combine employee demographic and compensation data for workforce analysis.

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
