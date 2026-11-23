# IBM HR Attrition Analysis

## Project Overview

This project analyzes employee attrition using an IBM HR dataset and presents the findings through a two-page interactive dashboard. The report explores overall workforce information and examines how attrition varies across departments, age groups, income brackets, job satisfaction levels, business travel, and gender.

The objective is to understand where employee attrition is higher and identify workforce segments that may need further investigation.

## Sample Problem Statement

The HR department wants to understand employee attrition patterns across the organization. Although the organization has information about employees, it needs a clear view of how many employees have left and whether attrition is associated with factors such as department, age, income, job role, job satisfaction, business travel, and overtime.

**As a data analyst, the task is to analyze the HR data, build an easy-to-understand dashboard, identify employee groups with comparatively high attrition rates, and provide recommendations that can help HR investigate retention opportunities.**

## Project Objectives

- Summarize the total workforce and total employee attrition.
- Understand the split between employees who stayed and employees who left.
- Compare attrition counts across departments and job roles.
- Explore attrition patterns by business travel and gender.
- Compare attrition rates across age groups and income brackets.
- Examine the relationship between job satisfaction level and attrition.
- Present findings in a dashboard with filters for interactive analysis.

## Dashboard Screenshots

### Page 1 – IBM HR Attrition Analysis: 2024 Overview

This page provides a high-level view of the workforce, including KPI cards for total employees, total attrition, average monthly income, and average employee age. It also includes employee attrition split, gender distribution, attrition count by department, employees by job role, and attrition status by business travel.

![IBM HR Attrition Analysis – 2024 Overview](images/ibm_hr_attrition_dashboard_page_1.png)

### Page 2 – Advanced Attrition Analysis

This page focuses on attrition rates across departments, age groups, income brackets, job satisfaction levels, and department-wise gender comparisons. Filters are provided for job role, age group, income bracket, and overtime.

![Advanced Attrition Analysis](images/ibm_hr_attrition_dashboard_page_2.png)

## Key Metrics and Findings

The dashboard shows the following overall figures:

- **Total employees:** 1,470
- **Total attrition:** 237
- **Average monthly income:** ₹6,503
- **Average employee age:** 36.92
- **Employees who left:** 16.1% of the workforce
- **Employees who stayed:** 83.9% of the workforce

Additional observations visible in the dashboard:

- Research & Development has the highest attrition count among the three departments shown: 133, compared with 92 in Sales and 12 in Human Resources.
- The 18–25 age group has the highest displayed attrition rate at 35.77%.
- The 26–35 age group has a displayed attrition rate of 19.14%.
- The 36–45 age group has a displayed attrition rate of 9.19%, the lowest among the age groups shown.
- The lowest income bracket (below ₹3K) has the highest displayed attrition rate at 28.61%.
- The displayed attrition rate decreases across the higher income brackets, reaching 8.9% for the ₹10K+ bracket.
- The lowest job satisfaction level has the highest displayed attrition rate at 22.84%.

These are descriptive findings from the dashboard. They show associations and differences, not proof that any one factor causes employees to leave.

## Tools and Technologies

- **HR dataset:** IBM HR Attrition data
- **Data analysis:** [Add the tool or language used for data preparation, if applicable]
- **Dashboard and visualization:** [Add the BI tool used to create the report]
- **Documentation and version control:** GitHub

*Update the bracketed items with the exact tools used in your project before publishing.*

## Analysis Requirements

The analysis requires employee-level HR data with fields that support the dashboard dimensions and measures, such as:

- Employee attrition status
- Department
- Gender
- Job role
- Age or age group
- Monthly income or income bracket
- Business travel
- Overtime
- Job satisfaction

The dashboard also requires calculated measures for employee count, attrition count, average monthly income, average age, and attrition rate.

## Challenges Faced

- Selecting meaningful HR metrics to summarize employee attrition.
- Comparing attrition counts and attrition rates without confusing the two measures.
- Grouping continuous values such as age and monthly income into readable categories.
- Presenting multiple HR dimensions in a dashboard while keeping the report easy to interpret.
- Designing filters so users can explore attrition across different employee segments.
- Interpreting dashboard patterns carefully without assuming that correlation proves causation.

## Recommendations

Based on the patterns shown in the dashboard, HR could consider the following areas for further investigation:

1. **Review early-career retention:** Investigate why the 18–25 age group has the highest displayed attrition rate. Review onboarding, career development, manager support, and employee feedback for this group.
2. **Review lower-income segments:** Examine compensation competitiveness, pay progression, and role expectations for employees in the lowest income bracket.
3. **Investigate job satisfaction:** Conduct follow-up analysis and employee feedback reviews for groups reporting low job satisfaction.
4. **Compare departments:** Explore department-level differences in workload, management practices, career opportunities, and working conditions.
5. **Study overtime and travel:** Use the dashboard filters to investigate whether attrition patterns differ for employees working overtime or travelling for business.
6. **Monitor retention over time:** Track attrition rate regularly and compare results across periods to evaluate whether retention initiatives are effective.

These recommendations are investigation areas based on the displayed patterns; additional employee feedback and business context would be needed before taking action.

## Conclusion

The IBM HR Attrition Analysis dashboard provides an overview of employee attrition and highlights differences across workforce segments. The results indicate that attrition is not evenly distributed across age groups, income brackets, departments, and job satisfaction levels.

The analysis can help HR teams identify areas for deeper investigation and support more informed employee-retention decisions.

---
**Note:** The figures and observations in this README are transcribed from the two dashboard pages supplied for this project. Validate calculations against the source dataset before using them for formal HR decisions.
