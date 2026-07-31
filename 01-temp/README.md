# Internship Program Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811)
![DAX](https://img.shields.io/badge/DAX-Measures-blueviolet)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-success)
![Dashboard](https://img.shields.io/badge/Interactive-Dashboard-blueviolet)
![CSV](https://img.shields.io/badge/Dataset-CSV-lightgrey)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

---

# Table of Contents

- Project Results
- Dashboard Preview
- Project Overview
- Project Objectives
- Dataset Information
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- EDA Visualizations
- Dashboard Features
- Technologies Used
- Project Structure
- Business Insights
- Key Findings
- Conclusion
- Future Improvements
- How to Run the Project
- Repository Contents
- Skills Demonstrated
- Author
- Acknowledgements

---

# Project Results

| Metric | Value |
|---------|--------|
| Dataset Records | 70,000 |
| Dataset Features | 17 |
| Missing Values | None |
| Duplicate Records | None |
| Data Cleaning | Completed |
| Exploratory Data Analysis (EDA) | Completed |
| Microsoft Power BI Dashboard | Completed |
| Dashboard Pages | 3 |
| Project Status | Completed |

---

# Dashboard Preview

The following screenshots showcase the three interactive dashboards developed for the **Internship Program Analysis** project using **Microsoft Power BI**.

The dashboards provide an overview of internship enrollment, completion status, intern performance, and demographic analysis through interactive KPI cards, DAX measures, slicers, and business visualizations.

---

## Executive Dashboard

<p align="center">
<img src="outputs/dashboard/01_Executive_Dashboard.png" width="1000">
</p>

The Executive Dashboard provides a high-level overview of the internship program by presenting key performance indicators, enrollment trends, completion statistics, department distribution, internship track distribution, and overall internship insights.

---

## Performance Dashboard

<p align="center">
<img src="outputs/dashboard/02_Performance_Dashboard.png" width="1000">
</p>

The Performance Dashboard focuses on internship performance by analyzing completed weeks, submitted tasks, mentor interactions, completion rates, department performance, internship tracks, and institute performance.

---

## Demographic Dashboard

<p align="center">
<img src="outputs/dashboard/03_Demographic_Dashboard.png" width="1000">
</p>

The Demographic Dashboard analyzes intern demographics including gender, age, education, institutes, cities, departments, and internship tracks.

---

# Project Overview

This project presents a complete **Internship Program Analysis** solution developed using **Python**, **Pandas**, **Jupyter Notebook**, and **Microsoft Power BI**.

The project follows a complete data analytics workflow beginning with data preprocessing and exploratory data analysis before developing interactive dashboards for business reporting.

The dashboards transform internship data into meaningful business insights through KPI cards, DAX measures, interactive filters, and professional visualizations that support data-driven decision-making.

---

# Project Objectives

The objectives of this project are:

- Perform data preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Analyze internship enrollment trends.
- Analyze internship completion status.
- Analyze internship performance.
- Analyze intern demographics.
- Build interactive Microsoft Power BI dashboards.
- Generate meaningful business insights.

---

# Dataset Information

**Dataset:** Internship Program 2025

**Project Type:** Business Intelligence Dashboard

**Domain:** Education & Internship Analytics

---

## Dataset Summary

| Attribute | Value |
|------------|-------|
| Dataset Name | Internship Program 2025 |
| Total Records | 70,000 |
| Total Features | 17 |
| Project Type | Business Intelligence Dashboard |
| Domain | Education & Internship Analytics |

---

# Dataset Features

The Internship Program dataset contains **17 features** that describe intern information, educational background, mentor assignments, internship progress, and completion status.

| Feature | Description |
|----------|-------------|
| Intern_ID | Unique identifier assigned to each intern |
| Intern_Name | Name of the intern |
| Gender | Gender of the intern |
| Age | Age of the intern |
| City | City of residence |
| Education | Educational qualification |
| Institute | Educational institute |
| Department | Internship department |
| Internship_Track | Internship specialization |
| Mentor_ID | Unique identifier assigned to each mentor |
| Mentor_Name | Name of the assigned mentor |
| Enrollment_Date | Internship enrollment date |
| Internship_Duration_Weeks | Total internship duration |
| Weeks_Completed | Number of weeks completed |
| Tasks_Submitted | Number of submitted tasks |
| Mentor_Interactions | Total mentor interactions |
| Status | Internship completion status |

---

# Data Preprocessing

Before creating the Microsoft Power BI dashboards, the dataset was prepared and validated using **Python**, **Pandas**, and **Jupyter Notebook**.

The preprocessing stage focused on understanding the dataset structure, validating data quality, checking business rules, and ensuring that the dataset was suitable for exploratory data analysis and dashboard development.

---

## Data Preparation

The following preprocessing tasks were performed:

- Imported the required Python libraries.
- Loaded the internship dataset.
- Converted the `Enrollment_Date` column into datetime format.
- Examined the dataset structure and information.
- Validated categorical values.
- Checked duplicate records.
- Verified business rules for numerical columns.
- Confirmed data consistency before analysis.

---

## Data Quality Assessment

The dataset quality assessment produced the following results.

| Assessment | Result |
|------------|--------|
| Missing Values | None |
| Duplicate Records | None |
| Invalid Categories | None |
| Business Rule Validation | Passed |
| Dataset Status | Ready for Analysis |

---

# Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was performed to understand internship participation, completion trends, department distribution, internship tracks, demographic characteristics, intern performance, and mentor engagement.

The insights generated during this phase were later used to design the Microsoft Power BI dashboards and produce meaningful business insights.

---

## Visualizations Performed

The following visualizations were created during the exploratory data analysis phase.

- Monthly Enrollment Trend
- Internship Completion Status
- Monthly Internship Completion Status
- Department-wise Distribution
- Monthly Department-wise Distribution
- Internship Track Distribution
- Monthly Internship Track Distribution
- Gender Distribution
- Age Distribution
- Education Distribution
- Institute Distribution
- City Distribution
- Status Distribution by Gender
- Status Distribution by Department
- Status Distribution by Internship Track
- Tasks Submitted Distribution
- Weeks Completed Distribution
- Mentor Interactions Distribution
- Correlation Heatmap

---

# EDA Visualizations

The following visualizations were created during the exploratory data analysis phase to examine internship enrollment patterns, completion status, demographic characteristics, department participation, internship tracks, mentor engagement, and overall internship performance.

---

## Monthly Enrollment Trend

<p align="center">
<img src="outputs/figures/01_monthly_enrollment_trend.png" width="550">
</p>

This visualization presents the monthly internship enrollment trend throughout 2025, helping identify peak enrollment periods and seasonal registration patterns.

---

## Internship Completion Status

<p align="center">
<img src="outputs/figures/02_internship_completion_status.png" width="550">
</p>

This chart compares completed and dropped internships, providing an overview of internship completion performance.

---

## Monthly Internship Completion Status

<p align="center">
<img src="outputs/figures/03_monthly_internship_completion_status.png" width="550">
</p>

This visualization compares monthly completed and dropped internships to understand completion trends throughout the internship program.

---

## Department-wise Distribution

<p align="center">
<img src="outputs/figures/04_department_wise_distribution.png" width="550">
</p>

This chart illustrates the distribution of interns across different internship departments.

---

## Monthly Department-wise Distribution

<p align="center">
<img src="outputs/figures/05_monthly_department_wise_distribution.png" width="550">
</p>

This visualization compares department-wise internship enrollments across different months.

---

## Internship Track Distribution

<p align="center">
<img src="outputs/figures/06_internship_track_distribution.png" width="550">
</p>

This chart presents the distribution of interns across various internship tracks.

---

## Monthly Internship Track Distribution

<p align="center">
<img src="outputs/figures/07_monthly_internship_track_distribution.png" width="550">
</p>

This heatmap illustrates monthly enrollment patterns across internship tracks.

---

## Gender Distribution

<p align="center">
<img src="outputs/figures/08_gender_distribution.png" width="550">
</p>

This visualization shows the gender distribution of interns participating in the internship program.

---

## Age Distribution

<p align="center">
<img src="outputs/figures/09_age_distribution.png" width="550">
</p>

This chart illustrates the age distribution of internship participants.

---

## Education Distribution

<p align="center">
<img src="outputs/figures/10_education_distribution.png" width="550">
</p>

This visualization presents internship participation across different educational qualifications.

---

## Institute Distribution

<p align="center">
<img src="outputs/figures/11_institute_distribution.png" width="550">
</p>

This chart compares internship participation across different educational institutes.

---

## City Distribution

<p align="center">
<img src="outputs/figures/12_city_distribution.png" width="550">
</p>

This visualization illustrates the geographical distribution of interns across different cities.

---

## Status Distribution by Gender

<p align="center">
<img src="outputs/figures/13_status_distribution_by_gender.png" width="550">
</p>

This chart compares internship completion status between male and female interns.

---

## Status Distribution by Department

<p align="center">
<img src="outputs/figures/14_status_distribution_by_department.png" width="550">
</p>

This visualization compares completed and dropped internships across different departments.

---

## Status Distribution by Internship Track

<p align="center">
<img src="outputs/figures/15_status_distribution_by_internship_track.png" width="550">
</p>

This chart compares internship completion status across different internship tracks.

---

## Tasks Submitted Distribution

<p align="center">
<img src="outputs/figures/16_tasks_submitted_distribution.png" width="550">
</p>

This visualization illustrates the distribution of tasks submitted by interns during the internship program.

---

## Weeks Completed Distribution

<p align="center">
<img src="outputs/figures/17_weeks_completed_distribution.png" width="550">
</p>

This chart presents the distribution of internship weeks completed by participants.

---

## Mentor Interactions Distribution

<p align="center">
<img src="outputs/figures/18_mentor_interactions_distribution.png" width="550">
</p>

This visualization analyzes the frequency of mentor interactions throughout the internship program.

---

## Correlation Heatmap

<p align="center">
<img src="outputs/figures/19_correlation_heatmap.png" width="550">
</p>

This heatmap illustrates the relationships among key numerical variables, supporting further analytical insights into internship performance.

---

# Dashboard Features

The Microsoft Power BI dashboard was developed to provide an interactive and comprehensive analysis of the internship program. The dashboard enables users to monitor internship participation, evaluate intern performance, analyze demographic information, and explore internship trends through interactive visualizations.

The dashboard is organized into three dedicated report pages, allowing users to examine the internship program from different analytical perspectives.

---

## Executive Dashboard

The Executive Dashboard provides a high-level summary of the internship program by presenting important performance indicators and overall internship trends.

The dashboard helps users quickly understand the overall status of the internship program without exploring detailed reports.

---

## Performance Dashboard

The Performance Dashboard focuses on internship progress and participant performance.

It enables users to evaluate internship completion, submitted tasks, completed weeks, mentor interactions, and overall internship engagement.

---

## Demographic Dashboard

The Demographic Dashboard provides demographic insights about internship participants.

It allows users to analyze gender, age, education, institute, city, department, and internship track distributions for better understanding of participant diversity.

---

# Dashboard Filters

Interactive filters are included throughout the dashboard to simplify data exploration and allow users to analyze internship information from different perspectives.

Users can filter dashboard visualizations according to available categories and instantly update all related charts and KPIs.

---

# Business Insights

The dashboard provides several business insights regarding internship participation, performance, and engagement.

Some important insights include:

- Internship enrollments vary throughout the year.
- Most interns successfully completed the internship program.
- Internship participation differs across departments.
- Internship track popularity varies among participants.
- Computing-related educational backgrounds contribute the highest number of interns.
- Major cities contribute a large portion of internship enrollments.
- Higher mentor interactions are associated with improved internship progress.
- Most interns successfully completed the full internship duration and submitted the required tasks.

---

# Key Findings

The exploratory data analysis and Power BI dashboard reveal several important findings regarding internship performance.

- Internship enrollments reached higher levels during the middle months of the year.
- Completed internships significantly outnumber dropped internships.
- Backend Development and Frontend Development recorded the highest department participation.
- PHP, Node.js, React, and Flutter attracted strong internship participation.
- Most interns completed the full internship duration.
- Most interns submitted the required internship tasks.
- Mentor interactions remained consistently high throughout the internship program.
- Strong positive relationships exist between completed weeks, submitted tasks, and mentor interactions.

---

# Conclusion

This project demonstrates how Python, Pandas, Jupyter Notebook, and Microsoft Power BI can be combined to transform internship data into meaningful business insights.

The project covers the complete analytics workflow, including data preparation, exploratory data analysis, visualization, and interactive dashboard development.

The generated dashboards support better understanding of internship participation, performance, and engagement while providing valuable information for data-driven decision-making.

---

# Future Improvements

The project can be extended in several ways to provide additional analytical capabilities.

Possible future improvements include:

- Real-time dashboard integration.
- Automated data refresh.
- Advanced DAX measures.
- Additional KPI indicators.
- Predictive analytics using machine learning.
- Integration with cloud-based data sources.

---

# Technologies Used

The following tools and technologies were used throughout the development of this project.

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Data Analysis | Pandas |
| Numerical Computing | NumPy |
| Data Visualization | Matplotlib |
| Statistical Visualization | Seaborn |
| Notebook Environment | Jupyter Notebook |
| Business Intelligence | Microsoft Power BI |
| Dashboard Calculations | DAX |
| Dataset Format | CSV |

---

# Project Structure

```text
01-Internship-Program-Analysis/
│
├── data/
│   └── raw/
│       └── internship_program_2025.csv
│
├── notebooks/
│   └── internship_program_analysis.ipynb
│
├── outputs/
│   ├── dashboard/
│   │   ├── 01_Executive_Dashboard.png
│   │   ├── 02_Performance_Dashboard.png
│   │   └── 03_Demographic_Dashboard.png
│   │
│   └── figures/
│       ├── 01_monthly_enrollment_trend.png
│       ├── 02_internship_completion_status.png
│       ├── 03_monthly_internship_completion_status.png
│       ├── 04_department_wise_distribution.png
│       ├── 05_monthly_department_wise_distribution.png
│       ├── 06_internship_track_distribution.png
│       ├── 07_monthly_internship_track_distribution.png
│       ├── 08_gender_distribution.png
│       ├── 09_age_distribution.png
│       ├── 10_education_distribution.png
│       ├── 11_institute_distribution.png
│       ├── 12_city_distribution.png
│       ├── 13_status_distribution_by_gender.png
│       ├── 14_status_distribution_by_department.png
│       ├── 15_status_distribution_by_internship_track.png
│       ├── 16_tasks_submitted_distribution.png
│       ├── 17_weeks_completed_distribution.png
│       ├── 18_mentor_interactions_distribution.png
│       └── 19_correlation_heatmap.png
│
├── powerbi/
│   ├── icons/
│   └── Internship_Program_Analysis_Dashboard.pbix
│
├── requirements.txt
│
└── README.md
```

---

# How to Run the Project

Follow the steps below to explore this project.

### 1. Clone the Repository

```bash
git clone https://github.com/huzaifawaheed2/InterneePK-Data-Analyst-Internship.git
```

### 2. Navigate to the Project Directory

```bash
cd InterneePK-Data-Analyst-Internship/01-Internship-Program-Analysis
```

### 3. Install the Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

Open the notebook located in the **notebooks** directory and execute all cells to perform the complete exploratory data analysis.

### 5. Open the Power BI Dashboard

Open the Power BI report located in the **powerbi** directory using **Microsoft Power BI Desktop**.

---

# Repository Contents

This repository contains all resources required to reproduce the project, including:

- Dataset
- Jupyter Notebook
- EDA Visualizations
- Microsoft Power BI Dashboard
- Dashboard Icons
- Requirements File
- Project Documentation

---

# Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Validation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Intelligence
- Dashboard Development
- Dashboard Design
- DAX
- Python
- Pandas
- Microsoft Power BI

---

# Author

## Muhammad Huzaifa Waheed

Data Analyst | Power BI Developer | QA Engineer

### Connect With Me

- GitHub: [huzaifawaheed2](https://github.com/huzaifawaheed2)
- LinkedIn: [Muhammad Huzaifa Waheed](https://www.linkedin.com/in/muhammad-huzaifa-waheed-70043338b)

---

# Acknowledgements

This project was developed as part of the **InterneePK Data Analyst Internship** to demonstrate practical skills in data analysis, business intelligence, exploratory data analysis, data visualization, and interactive dashboard development using Python and Microsoft Power BI.

---

⭐ **If you found this project useful, consider giving this repository a star!**