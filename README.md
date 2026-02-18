📊 COVID-19 Data Analysis Project
🚀 Project Overview

This project explores global COVID-19 data provided by Our World in Data.

The goal was to analyze cases, ICU patients, and hospitalizations across different countries and continents using real-world epidemiological data.

The analysis was performed using Python and Jupyter Notebook.

📂 Dataset

Source:
https://raw.githubusercontent.com/owid/covid-19-data/refs/heads/master/public/data/owid-covid-data.csv

The dataset includes:

location

continent

date

total_cases (cumulative)

new_cases

icu_patients

hosp_patients

vaccination metrics

Special attention was given to understanding:

The difference between cumulative and daily variables

Aggregated vs country-level data

Missing values handling

🔎 Key Analyses
1️⃣ Exploratory Data Analysis (EDA)

Dataset dimensions and structure

Missing values inspection

Data type validation

Metadata understanding

2️⃣ Total Cases by Continent

Computed total cumulative cases per continent

Calculated percentage share relative to global cases

Avoided double counting by excluding aggregated entries

3️⃣ Italy – 2022 Case Analysis

Filtered data for Italy in 2022

Removed days without weekly reporting

Visualized:

Total cases trend

New reported cases over time

4️⃣ ICU Patients Comparison

Countries analyzed:

Italy

Germany

France

Period: May 2022 – April 2023

A boxplot was used to compare ICU patient distributions.

5️⃣ Hospitalized Patients – 2021

Countries analyzed:

Italy

Germany

France

Spain

Calculated yearly sum of hospitalized patients

Identified and discussed missing values

Considered differences between stock and cumulative metrics

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📈 Skills Demonstrated

✔ Data cleaning
✔ Handling missing values
✔ Time-series filtering
✔ GroupBy & aggregation
✔ Data visualization
✔ Analytical reasoning
✔ Interpretation of real-world datasets

🎯 What This Project Shows

This project demonstrates my ability to:

Work with large real-world datasets

Understand epidemiological data structures

Apply data analysis techniques correctly

Communicate results clearly through visualization
