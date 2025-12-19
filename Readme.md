🌫️ Delhi Air Quality Insights (2020–2023)

An end-to-end air quality analytics project using Python, Excel, and Power BI to uncover long-term pollution patterns in India’s capital.

<img width="1919" height="935" alt="Screenshot 2025-12-19 123035" src="https://github.com/user-attachments/assets/a3bb7ba9-5987-454e-98cf-2ecbfc33c9a8" />


📌 Project Overview

Delhi continues to face a severe air pollution crisis with serious health and environmental implications.
This project analyzes hourly air quality data from 2020 to 2023 to identify seasonal trends, dominant pollutants, air quality distribution, and the frequency of clean air days.

The project showcases a complete data analytics lifecycle — from raw data preprocessing and exploratory analysis to interactive dashboard-based storytelling.

📄 Project Report: [Uploading Delhi_Air_Crisis_Three_Year_Analysis.pdf…]()


🎯 Project Objectives

Clean and preprocess large-scale hourly air quality datasets

Perform exploratory data analysis (EDA) using Python and Excel

Identify seasonal and monthly pollution patterns

Analyze dominant pollutants impacting AQI

Classify air quality into standard AQI categories

Build an interactive Power BI dashboard for insight-driven decision-making

🧪 Dataset Description

Time Range: 2020 – 2023

Granularity: Hourly observations

Pollutants Analyzed:

PM10

PM2.5

SO₂

NO₂

O₃

NH₃

🔄 Data Processing Workflow

🐍 Python – Analysis & Feature Engineering

Data cleaning (missing values, type conversions)

Time-series feature engineering (Year, Month, Day, Day Name)

Exploratory Data Analysis (trend detection, statistical summaries)

Air quality category classification logic

Data validation prior to visualization

📊 Excel – Validation & Cross-Checks

Initial data inspection and sanity checks

Pivot tables for rapid aggregation

Cross-verification of pollutant averages and trends

Ensuring analytical consistency

📈 Power BI – Visualization & Storytelling

Data modeling and relationships

DAX measures for KPIs and aggregations

Interactive slicers and filters

Dashboard design focused on clarity and impact

📊 Dashboard Highlights

🔢 Key Air Quality Metrics

Average PM10: 300.09

Average PM2.5: 238.13

🚨 These values indicate severely elevated particulate matter levels, posing continuous public health risks.

📉 PM2.5 Temporal Trend Analysis

Tracks PM2.5 variations by Year, Quarter, Month, and Day

Reveals consistent winter pollution spikes

Shows relatively lower pollution during monsoon months

Insight: Delhi’s air pollution is seasonal, predictable, and persistent.

🧪 Pollutant Contribution Analysis

Comparative analysis of average pollutant concentrations

PM10 and PM2.5 dominate overall pollution

Gaseous pollutants show relatively lower impact

🎯 Air Quality Category Distribution

Hourly air quality classified into:

Good

Satisfactory

Moderate

Poor

Very Poor

Severe

⚠️ Observation: Most readings fall under Poor to Severe categories, highlighting chronic exposure.

🌱 Clean Air Days Indicator

Total Clean Days (2020–2023): 31

Only 31 clean air days across multiple years, emphasizing the severity of Delhi’s air quality challenge.

📆 Monthly Pollution Patterns

PM10 and PM2.5 peak sharply in December

Confirms winter as the highest-risk period for air quality

🎛 Interactivity

Day Name filter → weekday vs weekend analysis

Year–Month slicer → detailed time-based exploration

🛠 Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Microsoft Excel: Pivot Tables, Data Validation

Power BI: DAX, Power Query, Interactive Visuals

📌 Key Insights Summary

Delhi’s air pollution is chronic and seasonally driven

PM10 and PM2.5 are the primary contributors

Winter months pose the highest health risks

Clean air days are extremely limited

📁 Repository Structure

📂 Delhi-Air-Quality-Insights
 ├── data/
 │   └── delhi_aqi.csv
 ├── notebooks/
 │   └── Pollution.ipynb
 ├── dashboard/
 │   └── delhi pollution.pbix
 ├── images/
 │   └── dashboard_screenshots.png
 ├── reports/
 │   └── Delhi_Air_Crisis_Three_Year_Analysis.pdf
 └── README.md

👤 Author

Saket Kumar Jha
Data Analyst | Python | Excel | Power BI | SQL
📍 Patna, India
