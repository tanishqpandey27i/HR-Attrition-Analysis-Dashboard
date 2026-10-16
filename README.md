# HR-Attrition-Analysis-Dashboard
An interactive Power BI dashboard that analyzes employee attrition, workforce distribution, department-wise trends, job roles, overtime patterns, and reasons for employee exits to support data-driven HR decision-making.
## Project Overview

The **HR Attrition Analysis Dashboard** is an interactive Power BI report designed to explore employee attrition patterns across departments, job roles, gender, overtime status, and reported reasons for leaving. It brings key workforce metrics and visual comparisons into one place to support data-informed human resource analysis.

## Objectives

- Monitor overall employee headcount and the number of employees who left.
- Review the overall attrition rate.
- Compare attrition across departments and job roles.
- Explore employee exits by primary reason and reason category.
- Examine attrition patterns in relation to overtime status and gender.

## Key Metrics

- **Total Employees:** Overall employee count represented in the report.
- **Employees Left:** Count of employees who left the organization.
- **Attrition Rate:** Percentage measure used to track employee exits.

## Dashboard Visualizations

The report includes the following visual analyses:

- **Department-wise attrition rate** using a clustered bar chart.
- **Job role-wise attrition rate** using a bar chart.
- **Employees left by primary reason** and by reason category.
- **Attrition rate by overtime status.**
- **Department-wise employees left.**
- **Total employees by overtime status.**
- **Employee count by gender.**
- **Department reference table** for a simple department listing.

## Tools and Technologies

- **Microsoft Power BI Desktop** — report creation and visualization.
- **Power Query / Power BI data model** — data preparation and organization, where applicable.
- **DAX measures** — KPI calculations used by the report.

## Data Model

The report references a fact table and dimension tables, including:

- `Fact_Attrition`
- `Dim_Employee`
- `Dim_department`

The dashboard fields include employee counts, attrition rate, department, job role, primary reason, reason category, overtime status, and gender.

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it with **Microsoft Power BI Desktop**.
3. If Power BI prompts for a data source or refresh, follow the prompt and confirm that the required source is available.
4. Explore the KPI cards and charts to compare attrition across the available workforce categories.
5. Select chart categories to explore related data where cross-filtering is enabled.

## Business Questions Explored

- What is the overall employee attrition rate?
- Which departments and job roles show different attrition patterns?
- What reasons are associated with employee exits in the dataset?
- How does attrition vary by overtime status?
- How is the employee population distributed by gender?

## Notes

This dashboard is an analytical view of the fields available in the underlying dataset. Visual associations should not be interpreted as proof that a factor causes employee attrition. Any conclusions should be validated with appropriate HR context and data-quality checks.

## Project Type

Independent data analytics project built with Microsoft Power BI.
