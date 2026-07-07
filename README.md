# Workforce-Management-and-Human-Resources-Analytics-Project

This project applies data analytics to synthetic HR data—demographics, performance, attendance, and training—to optimize workforce management. By identifying trends, it improves operational efficiency and HR strategies, showcasing how data-driven insights support informed decision-making in talent management, retention, and productivity.

# Project Objectives

The primary objectives of this project are to:

1. Analyze Employee Attrition: Investigate factors influencing employee turnover and predict potential attrition risks.

2. Evaluate Performance Trends: Assess employee performance patterns across various departments and job roles.

3. Optimize Attendance and Leave Management: Identify patterns in employee absenteeism and leave utilization, and their operational impact.

4. Measure Training Effectiveness: Determine the impact of training programs on employee performance and development.

5. Understand Workforce Demographics: Provide a comprehensive overview of the workforce composition for strategic planning.

## Datasets

This project utilizes four interconnected synthetic datasets, generated using Python, to simulate real-world HR data:

hr_employees.csv: Contains employee demographics, job titles, hire/termination dates, salary, and performance scores.

hr_performance_reviews.csv: Records individual employee performance review ratings and dates.

hr_attendance_leave.csv: Tracks employee leave (sick, vacation, personal) with durations.

hr_training_records.csv: Details completed training courses and scores.

## Tools and Technologies

*Python (Pandas, NumPy): Used for data generation, cleaning, transformation, and exploratory data analysis.

*SQL (Conceptual): Applied for data querying, joining, and aggregation (demonstrating database interaction principles).

*Power BI / Tableau (Conceptual): Intended for creating interactive dashboards and visualizations to present findings.

## Key Questions to be Answered

This analysis seeks to answer critical questions relevant to HR and operations:

1. Attrition: What are the primary drivers of employee attrition? Which employee segments have the highest attrition rates? Can we predict employees at high risk of leaving?

2. Performance: How do performance ratings vary across departments? Is there a correlation between training and performance? Which teams are high-performing?

3. Attendance & Leave: What are the absenteeism rates? Are there specific periods or departments with high leave utilization? What is the average duration of different leave types?

4. Training: Which training courses are most effective? Is there a measurable impact of training on performance or retention? Are there training gaps?

5. Workforce Composition: What is the current distribution of employees by department, job title, and employment status? How has this changed over time?

## Repository Structure

•
generate_hr_data.py: Databricks SQL script used to generate the synthetic datasets.

•
hr_employees.csv, hr_performance_reviews.csv, hr_attendance_leave.csv, hr_training_records.csv: The generated synthetic datasets.

•
hr_data_usage_guide.md: A detailed guide explaining each dataset and potential analysis areas.


Workforce_HR_Analytics_Project_Description.md: The detailed project description.


README.md: This file.

How to Use This Repository

1.
Clone the repository: git clone [repository-url]

2.
Generate Data: Run generate_hr_data.py to create the CSV files.

3.
Explore Data: Use the hr_data_usage_guide.md to understand the datasets and potential analyses.

4.
Perform Analysis: Apply your data analysis skills using Python, SQL, or Power BI/Tableau to answer the key questions.

5.
Visualize & Document: Create dashboards and reports to present your findings and insights.

This project provides a robust framework for developing and showcasing your data analysis capabilities in the HR and Operations domain.

