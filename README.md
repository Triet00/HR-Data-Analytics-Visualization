# HR-Data-Analytics-Visualization

🌟 Overview
This project began with a simple question: What can HR data reveal about the people who make an organization run?  
Using a Snowflake‑modeled dataset containing employee demographics, satisfaction levels, and performance reviews, I built an interactive Power BI dashboard that transforms raw HR records into a clear narrative about workforce composition and employee experience.

The data model centers on a FactPerformanceRating table, supported by dimension tables for employees, education, satisfaction, and rating levels . This structure allowed me to explore the relationships between identity, performance, and compensation with precision and clarity.

🧩 Data Model
The dataset follows a Snowflake schema, designed for analytical depth and clean relational modeling:

FactPerformanceRating — performance reviews, satisfaction metrics, training activity

DimEmployee — demographics, job role, salary, tenure

DimEducationLevel — highest qualification

DimRatingLevel — performance rating categories

DimSatisfiedLevel — satisfaction categories

This structure made it possible to slice insights across multiple dimensions without redundancy or ambiguity.

🔍 What the Data Reveals
As I explored the dataset, several patterns emerged that paint a nuanced picture of the workforce:

👥 A Young, Early‑Career Workforce
Most employees fall between 20–29 years old, suggesting a company with strong junior‑level representation and potential long‑term growth opportunities.

♀️ Gender Representation
Atlas Labs employs 2.7% more women than men, indicating a slight but meaningful female majority.

🌈 Gender Diversity
Employees identifying as non‑binary make up 8.5% of the organization — a notable level of representation compared to many industry benchmarks.

💰 Salary & Ethnicity
A deeper dive into compensation revealed disparities worth attention:

Employees identifying as White earn the highest average salary.

Those from Mixed or Multiple Ethnic Groups earn one of the lowest average salaries.

These findings highlight areas where HR leaders may want to investigate equity, pay structure, and progression pathways.

🎨 Dashboard Focus
The Power BI dashboard brings these insights to life through:

Demographic breakdowns

Salary and equity analysis

Satisfaction and performance trends

Training opportunities vs. training uptake

Attrition and tenure patterns

Each visual is designed to help HR teams move from intuition to evidence‑based decision‑making.

🎯 Project Goals
Build a clean, intuitive HR analytics dashboard

Identify demographic and compensation patterns

Surface potential equity gaps

Provide actionable insights for HR strategy and workforce planning

🛠️ Tools & Technologies
Power BI for modeling, DAX, and visualization

Snowflake‑style relational schema for structured analysis

Excel/CSV as source data

GitHub for version control and documentation
