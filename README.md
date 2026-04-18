# HR Analytics Dashboard – Power BI

This is a Power BI project where I worked with an HR dataset and built a report around employee income, job satisfaction, years at company and promotion-related patterns.

The goal was to create a dashboard that makes the data easier to explore and compare, especially across departments and job roles.  

## What I wanted to find out

The main questions behind the report were:

- How is income different between departments and job roles?
- Which roles have the highest average monthly income?
- How do job involvement, satisfaction, work-life balance and performance compare across departments and job roles?
- How long do employees usually stay in the company, in their role, and with the same manager?
- What does the data show about years since last promotion? 

## Report pages

### Executive Overview

The first page gives a quick summary of the main HR metrics.

It includes:
- average monthly income
- median monthly income
- average years at company
- job satisfaction by salary band
- years at company by department
- average monthly income by tenure group

This page is meant to give a fast overview before going into more details.

![Executive Overview](screenshots/executive-overview.png)

### Income

This page focuses on compensation.

I used it to compare:
- average and median hourly rate by department and job role
- average monthly income by job role
- average monthly income compared with years at company by job role  

This made it easier to compare income levels between roles and departments, and to see how income changes with years at the company.

![Income](screenshots/income.png)

### Survey

This page looks at employee experience.

It includes:
- average job satisfaction
- high performance rate
- work-life balance by age group
- a matrix with average job involvement, satisfaction, work-life balance and performance
- high performance by job role

I used this page to compare satisfaction, work-life balance, involvement, and performance across employee groups.

![Survey](screenshots/survey.png)

### Years at Company

This page focuses on years at company, time in role, time with current manager, and years since last promotion.

It includes:
- total employees
- first-year employees
- average years in current role
- employee count by years at company
- employee count by years in current role
- employee count by years with current manager
- employee count by years since last promotion
- years since last promotion by department

I used year ranges to make the page easier to read and to compare employee history more clearly. 

![Years at Company](screenshots/years-at-company.png)

## What I used

- Power BI dashboard design
- Power Query data preparation
- DAX measures and calculated columns
- KPI cards and interactive slicers
- Matrix visuals for department and role comparison
- Grouped categories with custom sorting
- Bar charts and scatter plots for HR analysis

## Key observations

- Manager and Research Director roles show the highest average monthly income.
- Many employees have been with the company for 5–10 years, making this one of the most visible experience groups in the dashboard.
- Survey scores are quite close across departments, so role-level differences are more interesting to look at.
- Many employees are in the 0–1 years since last promotion group, meaning their last promotion was recent.

## Files in this repository

- `HR Analytics.pbix` – Power BI report
- `screenshots/` – dashboard screenshots
- `README.md` – project notes

## Notes

This project is part of my Power BI portfolio and was created to practice building a complete dashboard from an HR dataset.

The goal was to create a clear Power BI report that makes HR data easier to explore and compare.

Feedback is welcome.
