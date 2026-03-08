# HR Workforce Analytics Dashboard (Power BI)

## Project Overview

This project presents an **HR Workforce Analytics Dashboard** built using **Microsoft Power BI**. The objective of this project is to analyze employee demographics, workforce distribution, recruitment sources, performance metrics, and employee engagement using HR data.

The dataset used for this project contains information about **311 employees across multiple departments**, including details such as salary, performance scores, recruitment channels, satisfaction levels, and absenteeism.

The dashboard provides interactive visualizations that help identify patterns in employee performance, workforce composition, and HR operational effectiveness.

---

## Dataset

The dataset used in this project is **HRDataset_v14**, which contains **311 employee records and 36 variables**.

Key fields included in the dataset:

* Employee Name
* Department
* Position
* Salary
* Gender
* Race
* Marital Status
* Recruitment Source
* Performance Score
* Employee Satisfaction
* Engagement Survey Score
* Absences
* Days Late in Last 30 Days
* Employment Status
* Date of Hire and Termination

---

## Tools and Technologies

* **Power BI Desktop** – Data visualization and dashboard creation
* **Power Query** – Data cleaning and transformation
* **DAX (Data Analysis Expressions)** – Creation of calculated measures and metrics

---

## Data Preparation

Before building the dashboard, the dataset was cleaned and transformed using **Power Query**.

The following steps were performed:

* Removed unnecessary identifier columns
* Verified and corrected data types for numerical and date fields
* Handled missing or inconsistent values where necessary
* Prepared the dataset for analysis and visualization

---

## Key Metrics Created

The following key metrics were calculated using **DAX measures**:

* Total Employees
* Average Salary
* Average Employee Satisfaction
* Average Engagement Score
* Total Employee Absences

These metrics provide quick insights into workforce size, employee engagement, and overall organizational trends.

---

## Dashboard Features

The Power BI dashboard includes multiple visualizations to analyze workforce patterns:

* **KPI Cards** showing total employees, average salary, satisfaction, and engagement levels
* **Employee Distribution by Department**
* **Gender Distribution of Employees**
* **Recruitment Source Effectiveness**
* **Employee Performance Score Distribution**
* **Salary Comparison by Department**
* **Absenteeism Analysis by Department**

Interactive **filters and slicers** allow users to explore the data by department, gender, recruitment source, and employment status.

---

## Key Insights

Several insights were derived from the analysis:

* The majority of employees are concentrated in the **Production department**, highlighting the operational focus of the organization.
* **Indeed and LinkedIn** are the most effective recruitment platforms for hiring employees.
* Most employees **meet performance expectations**, while a smaller percentage exceed expectations or require improvement.
* The workforce shows **relatively balanced gender representation**.
* Average absenteeism across employees is moderate, though some departments exhibit higher absence rates.

---

## Project Objective

The primary goal of this project is to demonstrate the use of **Power BI for HR data analysis**, including:

* Data cleaning and preparation
* Creation of analytical measures using DAX
* Building interactive dashboards
* Extracting meaningful insights from workforce data

---

## Project Files

* `HRDataset_v14.csv` – Source dataset
* `HR_Analytics_Dashboard.pbix` – Power BI dashboard file
* `README.md` – Project documentation

---

## Conclusion

This project demonstrates how **Power BI can be used to analyze HR data and generate actionable insights about workforce composition, employee engagement, recruitment effectiveness, and performance trends**.

The dashboard enables HR professionals and decision-makers to better understand employee data and support data-driven human resource management strategies.
