# HR-Analytics-Dashboard-for-Employee-Insights
The primary goal of this HR Analytics project is to provide key insights into employee performance, attrition trends, and overall workforce demographics. By leveraging Power BI, we aim to assist HR departments in making data-driven decisions regarding employee retention, promotions, and work-life balance improvements.
Key Business Questions:

# This dashboard helps answer the following HR-related questions:

What is the overall attrition rate in the company?

Which departments have the highest employee turnover?

How does salary distribution vary across different job roles?

What is the correlation between performance rating and attrition?

How long do employees typically stay before getting a promotion?

Does work-life balance impact attrition rates?
Dashboard Insights & Features:

# The Power BI dashboard consists of multiple interactive visuals that provide actionable insights, including:

KPI Cards: Display overall attrition rate, average salary, and average years at the company.

Attrition Analysis: A bar chart showing attrition percentage by department.

Salary Insights: A box plot or histogram displaying salary distribution by job role.

Performance vs. Attrition: A heatmap or scatter plot analyzing performance ratings and attrition.

Work-Life Balance Trends: A line graph depicting work-life balance ratings over different departments.

Promotion Trends: A clustered bar chart showing time taken for promotions across job roles.

# DAX Measures Implemented:

To enhance insights, the following DAX measures were created in Power BI:

Attrition Rate (%) = (Total Employees Who Left / Total Employees) * 100

Average Salary per Department = AVERAGE(Salary)

Average Tenure (Years at Company) = AVERAGE(Years_at_Company)

Employees Eligible for Promotion = COUNTROWS(FILTER(Employees, Employees[Last_Promotion] > 5))

# Key Findings & Recommendations:

High Attrition in Sales & IT Departments: The attrition rate in Sales and IT is significantly higher compared to other departments. HR should investigate job satisfaction and provide retention strategies.

Salary Disparities Across Job Roles: There is a considerable salary gap between job roles. Salary benchmarking can help ensure fair compensation.

Performance Rating vs. Attrition: Employees with lower performance ratings are more likely to leave. This suggests a need for better performance improvement programs.

Long Promotion Cycles: Many employees go several years without a promotion, which may contribute to higher attrition. HR should consider more frequent promotions based on performance.

Work-Life Balance Matters: Employees with lower work-life balance ratings tend to have a higher attrition rate. Implementing flexible work policies may improve retention.

# Conclusion:

This HR Analytics Dashboard serves as a critical tool for HR teams to understand employee trends, improve retention, and create a more effective workforce strategy. By integrating Power BI’s interactive features with DAX measures, we provide deep insights that drive data-driven HR decision-making.

