Project Insights Dashboard

Overview

The Project Insights Dashboard is a business intelligence solution developed using SQL Server, Excel, Power BI, Power Query, and DAX. The project centralizes project-related data from multiple Excel files into a SQL Server database, performs data cleaning and transformation, and presents actionable insights through an interactive Power BI dashboard.

The dashboard enables users to analyze project budgets, capital allocation, employee information, departmental performance, and project costs using dynamic filters and visualizations, supporting informed decision-making.

---

Features

- Imported and consolidated data from five Excel files into SQL Server.
- Cleaned and transformed raw data using Power Query.
- Handled missing values and standardized inconsistent data formats.
- Created calculated columns and DAX measures for salary, project budget, and capital analysis.
- Designed an interactive Power BI dashboard with KPIs, charts, matrix tables, and employee profile cards.
- Implemented slicers for Employee ID, Department, and Project Status.
- Enabled drill-down analysis for department-wise project performance.

---

Technologies Used

- SQL Server
- Microsoft Excel
- Power BI
- Power Query
- DAX

---

Dataset

The project uses five Excel datasets containing information related to:

- Employees
- Departments
- Projects
- Salaries
- Budget and Capital Allocation

These datasets are imported into SQL Server before being transformed and visualized in Power BI.

---

Dashboard Overview

The dashboard provides the following insights:

Employee Information
- Employee ID
- Employee Headshot
- First Name
- Family Name
- Job Title
- Department
- Salary

Project Analysis
- Total Capital
- Total Project Budget
- Capital Distribution
- Budget Distribution

Department Analysis
- Department Goals
- Department-wise Budget
- Salary Cost
- Capital Allocation
- Two-Year Cost Analysis

Interactive Filters
- Employee ID
- Department Name
- Project Status

---

Dashboard Preview



Project Workflow

```text
Excel Files
      │
      ▼
SQL Server
      │
      ▼
Power Query
(Data Cleaning & Transformation)
      │
      ▼
DAX
(Calculated Columns & Measures)
      │
      ▼
Power BI Dashboard
      │
      ▼
Interactive Business Insights
```

---

Key Insights

- Centralized project data into a single SQL Server database.
- Automated data cleaning and transformation using Power Query.
- Reduced manual calculations through DAX measures and calculated columns.
- Provided interactive department-level and employee-level analytics.
- Enabled stakeholders to monitor project budgets, costs, and capital allocation through dynamic visualizations.

---

Project Structure

```text
Project-Insights-Dashboard/
│
├── Dataset/
│   ├── Employees.xlsx
│   ├── Departments.xlsx
│   ├── Projects.xlsx
│   ├── Salaries.xlsx
│   └── Budget.xlsx
│
├── SQL/
│   └── Database.sql
│
├── Power BI/
│   └── Project Insights Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

Future Enhancements

- Connect the dashboard to a live SQL Server database for real-time reporting.
- Implement Row-Level Security (RLS).
- Publish the dashboard to the Power BI Service.
- Schedule automatic data refresh.
- Incorporate forecasting and trend analysis.

---

Author

**Devanesh**

Final Year B.Tech Student (Artificial Intelligence and Data Science)

**Skills:** SQL Server, Power BI, Excel, Power Query, DAX, Python
