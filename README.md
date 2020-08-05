# Predicting Employee Churn

## Problem Statement
Employee turnover is a costly problem that many companies face today.  The actual cost for replacing an employe can be very significant.  According to a study conducted by the Center for American Progress, companies spend about 20% of an employees' salary to replace that individual.  The percentage can be significantly higher if a "key" employee or C-level executive needs to be replaced.  In addition to the monetary cost, substantial time is needed to replace that employee (i.e. interviewing potential candidates, onboarding, training, etc.).  Companies can spend a few weeks to a few months replacing employees, which can reduce a company's profitability and production over time.  

In this study, we will attempt to answer the following questions these companies face:
**1) What are the key factors that cause employees to leave a company?**
**2) What strategies/action plan can a company implement to minimize the effect of employees leaving?

## The Data
The dataset contains information from 15,000 employees for a particular company.  The target variable is labeled as 'turnover' and it is a binary type (0 = still with company, 1 = left company).  The remainig features are defined in the dictionary below:

| Variable | Description |
| -------- | ----------- |
| satisfaction_level | Level of satisfaction for the employee, ranging from 0 (lowest) to 1 (highest) |
| radius* | Distance from the center point to the perimeter |
