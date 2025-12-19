📊 Delhi Air Quality Insights (2020–2023)

📌 Project Overview![Uploading Screenshot 2025-12-19 123035.png…]()


This project presents a comprehensive air quality analysis of Delhi (2020–2023) using Python, Excel, and Power BI.
Hourly pollutant-level data is cleaned, explored, and visualized to uncover seasonal trends, pollutant dominance, air quality distribution, and clean air frequency.

The project demonstrates an end-to-end data analytics workflow — from raw data preprocessing to interactive dashboard reporting.

🎯 Objectives

[Delhi_Air_Crisis_Three_Year_Analysis.pdf](https://github.com/user-attachments/files/24254512/Delhi_Air_Crisis_Three_Year_Analysis.pdf)

Clean and preprocess large hourly air quality datasets

Perform exploratory data analysis (EDA) using Python and Excel

Identify seasonal and monthly pollution patterns

Analyze dominant pollutants affecting AQI

Classify air quality into standard AQI categories

Build an interactive Power BI dashboard for insights delivery

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

🐍 Python

Data cleaning (handling missing values, type conversions)

Time-series feature engineering (Year, Month, Day, Day Name)

Exploratory Data Analysis (trend detection, summary statistics)

Pollution category classification logic

Data validation before visualization

📊 Excel

Initial data inspection and sanity checks

Pivot tables for quick aggregation

Cross-verification of averages and trends

Basic exploratory summaries for consistency

📈 Power BI

Data modeling and relationships

DAX measures for KPIs and aggregations

Interactive visualizations and slicers

Dashboard design and storytelling

📈 Dashboard Components

1. Key Metrics (KPIs)

Average PM10: 300.09

Average PM2.5: 238.13

These KPIs indicate severely elevated particulate matter levels, posing continuous public health risks.

2. PM2.5 Temporal Trend Analysis

Visualizes PM2.5 variation by Year, Quarter, Month, and Day

Highlights recurring winter pollution spikes

Shows reduced levels during monsoon months

Insight: Air pollution in Delhi is seasonal, predictable, and persistent.

3. Pollutant Contribution Analysis

Comparative analysis of average pollutant concentrations

PM10 and PM2.5 dominate overall pollution

Gaseous pollutants have comparatively lower impact

4. Air Quality Category Distribution

Hourly air quality categorized into:

Good

Satisfactory

Moderate

Poor

Very Poor

Severe

Observation: Most observations fall under Poor to Severe categories, indicating chronic exposure.

5. Clean Air Days Indicator

Total Clean Days (2020–2023): 31

This reflects the rarity of acceptable air quality over multiple years.

6. Monthly Pollution Patterns

PM10 and PM2.5 peak sharply in December

Confirms winter as the highest-risk pollution period

7. Interactivity

Day Name filter for weekday vs weekend analysis

Year–Month slicer for granular time-based exploration

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib/Seaborn)

Microsoft Excel (Pivot Tables, Data Validation)

Power BI (DAX, Power Query, Interactive Visuals)

📌 Key Insights Summary

Delhi’s air pollution is chronic and seasonal

Particulate matter (PM10 & PM2.5) is the primary contributor

Winter months pose the highest health risk

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
 └── README.md


👤 Author

Saket Kumar Jha
Data Analyst | Python | Excel | Power BI | SQL
📍 Patna, India
