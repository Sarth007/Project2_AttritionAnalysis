📊 HR Insights Report
Employee Attrition & Workforce Analytics
1. Executive Summary

Employee attrition is a major challenge for organizations due to its impact on productivity, hiring costs, and team stability.
This analysis uses the IBM HR Analytics Attrition Dataset to identify key factors influencing employee turnover and provide actionable HR policy recommendations based on statistical evidence.

The study reveals that salary level, job role, early tenure, work-life balance, and career level are the strongest drivers of attrition.

2. Dataset Overview

Source: IBM HR Analytics Dataset (Kaggle)

Records: 1,470 employees

Target Variable: Attrition (Yes / No)

Key Feature Categories:

Demographics (Age, Gender)

Compensation (Monthly Income, Job Level)

Work Conditions (Work-Life Balance, Overtime)

Experience (Years at Company, Total Working Years)

Job Information (Department, Job Role)

3. Data Preparation & Cleaning

The following steps were performed:

Converted Attrition into binary format (1 = Yes, 0 = No)

Removed irrelevant constant columns:

EmployeeCount

EmployeeNumber

Over18

StandardHours

Segregated numerical and categorical variables for accurate analysis

This ensured clean, analysis-ready data.

4. Key Attrition Insights
4.1 Attrition vs Age

Younger employees show significantly higher attrition rates

Employees under 35 years are more likely to leave

📌 Interpretation:
Early-career professionals are more likely to explore better opportunities or experience job dissatisfaction.

4.2 Attrition vs Monthly Income

Employees with lower monthly income have higher attrition

Salary difference between attrition and non-attrition groups is statistically significant

📌 Interpretation:
Compensation is a critical retention factor, especially for junior employees.

4.3 Attrition vs Job Role

Job roles with higher attrition:

Sales Executive

Sales Representative

Laboratory Technician

Job roles with lower attrition:

Research Director

Manager

Healthcare Representative

📌 Interpretation:
Customer-facing and high-pressure roles experience more employee exits.

4.4 Work-Life Balance Impact

Employees with poor work-life balance have a much higher attrition rate

Attrition decreases significantly as work-life balance improves

📌 Interpretation:
Work-life balance is a strong non-monetary driver of retention.

4.5 Experience & Tenure Analysis

Highest attrition observed in employees with:

Less than 3 years at the company

Lower total working experience

Long-tenured employees show strong retention

📌 Interpretation:
The first 2–3 years are the most critical for employee retention.

5. Correlation & Statistical Findings
5.1 Correlation Analysis

Key numerical variables negatively correlated with attrition:

MonthlyIncome

JobLevel

YearsAtCompany

Age

TotalWorkingYears

📌 Meaning:
As income, experience, and seniority increase, attrition probability decreases.

5.2 Statistical Hypothesis Testing

T-Test: Monthly Income vs Attrition

Result shows statistically significant difference

Confirms salary as a strong predictor of attrition

📌 Conclusion:
Attrition is not random; it is driven by measurable factors.

6. HR Policy Recommendations

Based on analytical insights, the following strategies are recommended:

✅ Compensation & Benefits

Review salary bands for junior-level employees

Introduce performance-based incentives in high-attrition roles

✅ Early-Career Retention Programs

Structured onboarding and mentorship for first 2 years

Career roadmap clarity for new hires

✅ Work-Life Balance Initiatives

Flexible work hours or hybrid work models

Reduce overtime dependency in high-pressure roles

✅ Role-Specific Retention Strategy

Target Sales and Technical roles with tailored engagement plans

Improve workload distribution and recognition systems

✅ Career Growth & Learning

Upskilling and internal mobility programs

Promotion transparency to reduce early dissatisfaction

7. Business Impact

Implementing these recommendations can:

Reduce attrition-related hiring costs

Improve employee satisfaction and engagement

Increase workforce stability and productivity

Enable data-driven HR decision-making

8. Conclusion

This project demonstrates how data analytics and statistical methods can be used to:

Understand employee behavior

Identify attrition drivers

Translate insights into practical HR policies

The findings emphasize that employee attrition is predictable, measurable, and manageable when data-driven strategies are applied.

9. Tools & Technologies Used

Python

Pandas & NumPy

Seaborn & Matplotlib

SciPy (Statistical Testing)

Google Colab