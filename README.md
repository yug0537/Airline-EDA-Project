# Airline-EDA-Project
This Project Involves Exploratory Data Analysis(EDA) On an Airline Datset

## Summary
This project involves Exploratory Data Analysis (EDA) on an airline dataset containing over 10,000 flight booking records. The goal is to derive actionable insights from customer, flight, and fare-related features that can inform business decisions and improve service offerings.

## Objectives
- Understand the structure and quality of the dataset.
- Identify missing values, anomalies, and inconsistencies.
- Analyze relationships between variables such as airline, source/destination, departure/arrival time, duration, and price.
- Visualize patterns to uncover trends in flight pricing and customer behavior.

## Tools & Libraries Used
- Python, Pandas, NumPy for data manipulation.
- Matplotlib, Seaborn for visualizations.
- Jupyter Notebook for interactive analysis.

## Dataset Used
- <a href="https://github.com/yug0537/Airline-EDA-Project/commit/090bfada5e5c7e55980f0f0f336778a578b9519d">Raw Data<a/>

## Process
- Data Loading & Initial Exploration
  - The dataset was loaded using Pandas.
  - Initial checks were done: .shape, .info(), column names, and unique values.
  - Found 10,683 rows and 11 columns.
- Data Cleaning
  - Identified and handled Missing values.
  - Datatypes (converted date and time columns to datetime format).
  - Text inconsistencies (e.g., multiple formats for airline and destination names like “Jet Airways Business” vs. “Jet Airways”).
- Feature Engineering
  - Extracted new features
  - Day, month, and year from Date_of_Journey.
  - Hour and minute from Dep_Time and Arrival_Time.
  - Converted Duration into total minutes for consistency.
  - Encoded categorical features.
- Data Preprocessing
  - Removed anomalies and Corrected inconsistent or duplicated values.
  - Ensured uniform formats for analysis.




