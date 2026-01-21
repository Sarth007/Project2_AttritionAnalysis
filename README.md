📊 Employee Attrition & Workforce Analytics
📌 Project Overview

Employee attrition is a critical challenge for organizations as it directly impacts productivity, hiring costs, and workforce stability.
This project analyzes the IBM HR Analytics Attrition Dataset to identify key factors driving employee turnover using statistical analysis and data visualization.
The goal is to help HR teams make data-driven decisions to improve employee retention.

🎯 Objectives

Analyze why employees leave organizations
Identify key drivers of attrition
Perform statistical and correlation analysis
Visualize attrition patterns
Provide actionable HR policy recommendations

📂 Project Folder Structure

Project2_AttritionAnalysis/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   └── attrition_analysis.ipynb
│
├── visuals/
│   └── charts/
│       ├── attrition_vs_age.png
│       ├── attrition_vs_income.png
│       ├── worklife_vs_attrition.png
│       └── correlation_heatmap.png
│
├── report/
│   └── HR_Insights_Report.md
│
└── README.md

📊 Dataset Information

Source: IBM HR Analytics Dataset (Kaggle)
Records: 1,470 employees
Target Variable: Attrition (Yes / No)

Key Features:
Age
Monthly Income
Job Role
Work-Life Balance
Years at Company
Job Level
Total Working Years

🛠 Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy

Google Colab / Jupyter Notebook

🔍 Key Analysis Performed
✔ Data Cleaning
Converted Attrition into binary format
Removed constant and irrelevant colums
Separated numerical and categorical variables

✔ Exploratory Data Analysis (EDA)
Attrition vs Age
Attrition vs Monthly Income
Attrition vs Job Role
Attrition vs Work-Life Balance
Attrition vs Experience

✔ Statistical Analysis
Correlation analysis on numerical features
Hypothesis testing (T-Test) on salary vs attrition

✔ Data Visualization
Boxplots
Countplots
Stacked bar charts
Correlation heatmap

📈 Key Insights

Younger employees show higher attrition
Low monthly income significantly increases attrition risk
Sales and technical roles have higher turnover
Poor work-life balance strongly correlates with attrition
Employees in their first 2–3 years are most likely to leave

🧠 HR Policy Recommendations

Improve compensation for early-career employees
Introduce structured onboarding and mentorship programs
Promote work-life balance through flexible work arrangements
Develop role-specific retention strategies
Create clear career growth and promotion pathways

📄 Reports & Documentation

HR Insights Report:
report/HR_Insights_Report.md
(Detailed business interpretation and recommendations)

🚀 How to Run the Project

Clone the repository:
git clone https://github.com/Sarth007/Project2_AttritionAnalysis


Open the notebook:
notebooks/attrition_analysis.ipynb

Run all cells sequentially

💼 Business Impact

This project demonstrates how data analytics and statistical methods can be applied to:
Predict employee attrition risks
Reduce hiring and training costs
Improve workforce planning
Enable data-driven HR strategies

📌 Conclusion

Employee attrition is predictable and manageable when organizations leverage analytics.
This project highlights the importance of combining technical analysis with business insights to solve real-world HR problems.

✨ Author

Sarthak Revgade
IT & Electronics Engineering Student
Aspiring Data & Business Analyst
