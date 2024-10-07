# Employee-Insights-Dashboard
Employee Insights Dashboard

Overview
This Employee Insights Dashboard provides a comprehensive view of key workforce metrics, allowing stakeholders to analyze employee data across various dimensions. The dashboard was developed using Power BI with advanced DAX queries to derive insights such as Average Salary, Total Employees, Average Tenure, and Salary Costs. It includes multiple visualizations to make the analysis more intuitive and actionable.

Key Metrics:
Average Salary: The average salary of all employees.
Total Employees: Total number of employees in the organization.
Average Tenure: The average length of time employees have been with the organization.
Salary Cost: The total salary cost across all employees.
DAX Queries:
Here are some of the DAX queries used to calculate these key metrics:

Average Salary:
DAX
Copy code
AverageSalary = AVERAGE(Employee[Salary])
Total Employees:
DAX
Copy code
TotalEmployees = COUNT(Employee[EmployeeID])
Average Tenure:
DAX
Copy code
AverageTenure = AVERAGE(Employee[Tenure])
Salary Cost:
DAX
Copy code
SalaryCost = SUM(Employee[Salary])
Visualizations:
Donut Chart: Total Employees by Current Employee Rating

Displays the breakdown of total employees based on their current performance rating, helping HR managers identify the distribution of employee performance.
Ribbon Chart: Total Employees by Business Unit and Gender

Shows the total employees across various business units, segmented by gender. The ribbon chart helps visualize how gender distribution varies across business functions over time.
Stacked Bar Chart: Total Employees by Separation Reason and Gender

Analyzes the reasons for employee separations (e.g., resignations, retirements) with a gender breakdown. This helps HR understand any gender-specific trends in employee attrition.
Matrix: Cost Center, Total Employees, Salary Cost, and Average Tenure

Provides a tabular breakdown of total employees, salary cost, and average tenure across various cost centers. The matrix helps to compare these metrics across different departments or units.
Tree Map: Total Employees by Cost Center

The tree map visualizes the number of employees in each cost center, allowing for a quick visual understanding of employee distribution across departments.
