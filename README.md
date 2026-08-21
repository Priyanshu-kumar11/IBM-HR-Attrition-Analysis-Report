# HR Employee Attrition Analytics Dashboard

An interactive **Power BI dashboard** designed to analyze employee attrition and support data-driven HR decision-making. The project provides a centralized view of workforce demographics, attrition patterns, compensation trends, and employee satisfaction factors.

---

## 📌 Project Overview

Employee attrition can impact organizational productivity, operational costs, and employee morale. HR teams often rely on multiple reports and manual analysis to understand workforce trends and the factors associated with employees leaving the organization.

This project consolidates HR data into an interactive **Power BI dashboard**, enabling stakeholders to explore employee information, identify attrition patterns, and analyze key factors such as overtime, business travel, compensation, satisfaction, and work-life balance.

---

## 🎯 Business Objectives

* Analyze workforce composition and employee demographics.
* Identify key factors associated with employee attrition.
* Analyze attrition across departments, job roles, gender, overtime, and business travel.
* Compare compensation trends with attrition outcomes.
* Analyze the relationship between employee satisfaction and attrition.
* Provide HR stakeholders with a self-service reporting solution.
* Reduce dependency on manual HR MIS reporting.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** – Data transformation and preparation
* **DAX** – KPI and analytical calculations
* **IBM HR Analytics Employee Attrition Dataset**

---

## 📊 Dashboard Pages

### 1. Overview

Provides a high-level snapshot of workforce health using key KPIs:

* Total Employees
* Active Employees
* Employees Left
* Average Age
* Average Monthly Income
* Average Years at Company

The page also includes navigation buttons to access detailed analysis pages.

### 2. Workforce Demographics

Analyzes workforce composition using:

* Employees by Gender
* Employees by Overtime
* Employees by Marital Status
* Employees by Education
* Employees by Age Group

### 3. Attrition Analysis

Helps identify where employee attrition is concentrated by analyzing:

* Attrition vs Business Travel
* Attrition vs Job Role
* Attrition vs Department
* Attrition vs Gender
* Attrition vs Overtime
* Attrition vs Work-Life Balance
* Overall Attrition Rate

Interactive **Age Group** and **Gender** slicers allow users to explore specific employee segments.

### 4. Compensation Analysis

Analyzes salary distribution and its relationship with workforce characteristics and attrition:

* Salary vs Department
* Salary vs Job Role
* Salary vs Attrition
* Salary vs Gender
* Median Salary
* Salary Range

Age Group and Gender filters are synced with the Attrition Analysis page for consistent analysis.

### 5. Employee Satisfaction Analysis

Examines employee satisfaction factors associated with attrition:

* Job Satisfaction vs Attrition
* Environment Satisfaction vs Attrition
* Relationship Satisfaction vs Attrition
* Work-Life Balance vs Attrition

---

## 📈 Key DAX Measures

The dashboard uses DAX measures to calculate important workforce KPIs, including:

```DAX
Total Employees
Employees Left
Active Employees
Attrition Rate
Average Age
Average Monthly Income
Average Years at Company
Median Salary
Salary Range
```

### Key KPI Logic

* **Total Employees** – Total employee records
* **Employees Left** – Employees with `Attrition = "Yes"`
* **Active Employees** – Total Employees minus Employees Left
* **Attrition Rate** – Percentage of employees who left the organization
* **Average Monthly Income** – Average employee monthly income
* **Average Years at Company** – Average employee tenure

---

## 🔄 Data Preparation

The dataset was prepared and analyzed using **Power Query and Power BI**.

Key preparation and modeling activities include:

* Data type validation
* Creation of derived measures
* Age grouping for demographic analysis
* Mapping categorical and ordinal fields
* Logical sorting of satisfaction and work-life balance categories
* Interactive filtering using slicers
* Cross-page navigation using Power BI action buttons

---

## 📂 Project Structure

```text
HR-Employee-Attrition-Analytics/
│
├── HR Dasboard.pbix
├── HR_Attrition_Dashboard_BRD.pdf
├── Dataset/
│   └── HR_Employee_Attrition_Dataset
│
└── README.md
```

> Update the dataset filename and folder name according to your actual GitHub repository.

---

## 🚀 How to Use

1. Clone or download this repository.
2. Download and install **Microsoft Power BI Desktop**.
3. Open the `.pbix` file in Power BI Desktop.
4. Explore the dashboard using the navigation buttons.
5. Use the available slicers to filter the data.
6. Review workforce, attrition, compensation, and satisfaction insights across the five dashboard pages.

---

## 👥 Target Users

This dashboard is designed for:

* HR Managers and HR Business Partners
* Department Heads
* Senior Management
* Business Leaders
* Data and HR Analysts

---

## 📌 Project Scope

### Included

* Workforce demographic analysis
* Employee attrition analysis
* Compensation analysis
* Employee satisfaction analysis
* Interactive filtering
* Cross-page navigation
* KPI-driven reporting

### Not Included

* Real-time data integration
* Machine learning or predictive attrition modeling
* Live HRMS or payroll integration
* Employee-level personally identifiable reporting

---

## 🔮 Future Enhancements

Potential improvements for future versions include:

* Predictive attrition modeling using machine learning
* Automated dataset refresh
* Integration with HRMS or payroll systems
* Advanced drill-through analysis
* Employee retention risk scoring
* AI-generated insights and summaries
* Department-level performance benchmarking

---

## 👤 Author

**Priyanshu Kumar**
Data & Operations Analyst

**Skills:** Power BI | DAX | Power Query | SQL | Python | Advanced Excel

---

## 📄 Data Source

The project uses the **IBM HR Analytics Employee Attrition Dataset**, a fictional dataset created for analytics and research practice.

---

## ⭐ Portfolio Note

This project demonstrates practical skills in:

* Business Requirements Understanding
* HR Data Analysis
* Data Preparation
* Power Query
* DAX Calculations
* KPI Development
* Dashboard Design
* Interactive Reporting
* Business Insight Generation
