# Course-Completion-Engagement-Analysis-Excel-SQL-BI-


**Project Overview**

This project analyzes e-learning course completion and engagement data to understand how student behavior, payment status, and platform interactions influence course outcomes.

The dataset was cleaned, transformed, and modeled using SQL Server (SSMS), then structured for business intelligence dashboards (Power BI / Tableau / Excel).

The goal is to demonstrate:

Real-world data cleaning

Defensive SQL practices

Dimensional modeling (Star Schema)

KPI-ready data preparation for visualization



**Business Questions Addressed**

Do paid learners complete courses at higher rates than free users?

How does employment status affect course completion and engagement?

Are notifications and reminders associated with higher progress?

What behaviors distinguish high-completion vs low-completion learners?

Which courses and categories show the strongest engagement?



**Dataset Description**

The dataset contains anonymized student, course, engagement, and payment information.

Key Columns Include:

Student Info: Age, Gender, Education Level, Employment Status, City

Course Info: Course Name, Category, Level, Duration, Instructor Rating

Engagement Metrics:

Video Completion Rate

Login Frequency

Time Spent (Hours)

Quiz Scores

Assignments Submitted / Missed

Payment & Completion:

Fee Paid

Payment Amount

Completed (Yes/No)



**Data Cleaning & Preparation (SQL Server)**
Cleaning Steps Performed

Trimmed whitespace and standardized categorical text values

Validated and converted date fields using TRY_CONVERT

Detected and handled impossible values (e.g. percentages > 100)

Created binary flags for analysis:

Paid_Flag (1 = Paid, 0 = Free)

Completed_Flag (1 = Completed, 0 = Not Completed)



**Data Modeling (Star Schema)**

To optimize performance and visualization, the raw table was transformed into a star schema:

Dimension Tables

DimStudent – student demographics

DimCourse – course attributes

DimPlatform – device and connection details

Fact Table

FactCourseEngagement – measurable events and KPIs such as:

Progress Percentage

Video Completion Rate

Quiz Scores

Time Spent

Completion Flag

This structure is optimized for BI tools and analytical queries.


**Calculated Metrics**

Several analytics-ready fields were created directly in SQL:

Engagement Score (weighted combination of progress, video completion, and quiz scores)

Inactive Flag (based on days since last login)

These metrics are used directly in dashboards without extra transformation.



**Tools Used**

SQL Server (SSMS) – data cleaning, transformation, modeling

Excel / Power BI 

GitHub – version control and portfolio presentation



**Key Skills Demonstrated**

SQL data cleaning & validation

Handling real-world dirty data

Date conversion and datatype enforcement

Dimensional modeling (fact & dimension tables)

KPI engineering for dashboards



**Student Engagement Analytics Dashboard**
The dashboard provides insights into student engagement, course performance, completion rates, inactivity risk, and payment behavior, supporting data-driven decision-making for online education platforms.

Dashboard Features

KPI cards:

Completion Rate

Total Students

Average Engagement Score

Inactivity Rate

Course analytics:

Completion Rate by Category

Engagement by Course

Quiz Performance by Course Level

Student behavior insights:

Days Since Last Login distribution

Engagement by Education Level

Monetization insights:

Paid vs Free student distribution

Interactive slicers:

Course Category

Course Level

City

Enrollment Date

Education Level











Analytics storytelling


