# NYPD Budgeting Decisions and Resource Allocation Data Analysis Project

## Introduction
To start off, I was **curious** as to how the New York Police Department (NYPD) decided on their budgeting decisions. I decided to take this problem into my own hands and find key insights into how the NYPD should allocate their resources based on needs and crime trends. Understanding NYPD resource allocation based on crime trends is important because it directly impacts **public safety**, ensures the efficient use of resources, and fosters data-driven decision-making.

---

## Research Questions
The questions I wanted to answer were:
1. What is the frequency of arrests by week of the day?
2. Where are there potential crime hotspots in NYC?
3. What is the frequency of different crimes?
4. How are crimes split by Age Group?
5. What does the Year over Year number of crimes per year look like?
6. What is the number of crimes by Borough?

These questions help answer the question of budget allocation as they provide trends and insights for the NYPD to prioritize.

---

## Finding Data Sources
To find the appropriate datasets, I visited the official New York City website for their open public datasets.

- **Dataset 1**: [NYPD Arrests Data Historic (2006-2022)](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u/about_data)
- **Dataset 2**: [NYPD Arrest Data Year to Date (2023)](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc)

With these datasets, I had 19 columns and over 5.7 million records to analyze.

---

## Data Cleaning
To process this data, I used **Python** and the `pandas` library due to the large size of the datasets.

The data cleaning steps included:
1. Concatenating both datasets
2. Removing duplicates
3. Removing rows with blank values
4. Dropping unnecessary columns
5. Renaming column names
6. Renaming values
7. Cleaning data values for specific columns (e.g., AGE_GROUP)
8. Exporting the cleaned and combined dataset into a CSV file for analysis.

---

## Data Exploration / Visualization
I chose **Tableau** for data exploration, as the visualizations were instrumental in answering the research questions.

---

## Presentation
To present my findings effectively, I built a dashboard in Tableau, featuring graphs that could help the NYPD allocate resources using data-driven insights.
[NYPD Crime Statistics 2006-2023 Dashboard](https://public.tableau.com/app/profile/dorwin.liang/viz/NYPDCrimeStatistics2006-2023/Dashboard1)
