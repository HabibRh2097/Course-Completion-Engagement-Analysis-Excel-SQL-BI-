**Course Completion & Engagement Analysis**

SQL Server • Power BI • Dimensional Modeling

**Project Overview**

This project analyzes e-learning student engagement and course completion behavior using SQL Server and Power BI.
Raw data was cleaned, transformed, and modeled into a star schema to support KPI-driven analytics and dashboarding.

The goal is to demonstrate real-world data preparation, defensive SQL practices, and business-ready BI modeling.

**Business Questions Answered**

Do paid learners complete courses at higher rates?

Which courses and categories show the strongest engagement?

What behaviors are associated with high vs low completion?

How does inactivity impact engagement and outcomes?

**Data Preparation & Modeling**

Cleaned and standardized raw data in SQL Server (SSMS)

Validated dates, handled invalid values, and normalized categories

Created binary flags for analytics:

Paid_Flag

Completed_Flag

Inactive_Flag

**Modeled data using a star schema:**

Dimensions: DimStudent, DimCourse

Fact: FactCourseEngagement

**Calculated Metrics**

Engagement Score (weighted progress, video completion, quiz performance)

Completion Rate

Inactivity Rate

All metrics are SQL-generated and dashboard-ready.

**Dashboard Highlights**

KPI cards: Completion Rate, Total Students, Avg Engagement, Inactivity %

Course performance by category and level

Student engagement and inactivity trends

Paid vs free learner comparison

Interactive slicers (Category, Course Level, City, Date)

**Tools Used**

SQL Server (SSMS) – data cleaning, transformation, modeling

Power BI / Excel – visualization and analytics

GitHub – version control and portfolio presentation

**Key Skills Demonstrated**

SQL data cleaning & validation

Dimensional (star schema) modeling

KPI engineering for BI dashboards

Analytics-driven storytelling


