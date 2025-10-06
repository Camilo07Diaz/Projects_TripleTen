# Project 8 - TripleTen

## Project description 
This project was part of my Data Analyst training at TripleTen. 
I worked as an analyst for Zuber, a new ride-sharing company launching in Chicago. The main goal was to identify patterns within the available data to better understand passenger preferences and evaluate the impact of external factors-such as weather-on ride frequency.
To achieve this, I analyzed competitor's data and tested a hypothesis on how weather conditions influenced trip duration between specific neighborhoods.

## Tasks completed 
### Exploratory data analysis (SQL)
- Calculated the number of taxi trips per company between **Nomvember 1516, 2017**, naming the resulting field trips_amount and sorting companies in descending order. 
- Counted the number of trips for each company whose name catained "Yello" or "Blue" during November 1-7, 2017, grouping results by company name. 
- Identified the most popular taxi companies in November 2017 - Falsh Cab and Taxi Afiliation Services - and grouped all other companies under "Other". Sorted the total trips in descending order by trips_amount. 

### Hypothesis Testing (SQL)
- Retrieved neighborhood identifiers for O'Hare and The Loop from the neighborhoods table. 
- Extracted hourly weather records from the weather_records table, classifying conditions as "Bad" if descriptions included "rain" or "storm", and "Good" otherwise. 
- Collected trip data from trips where rides started in The Loop (ID 50) and ended at O'Hare (ID 63) on Saturdays. 
- Combined this information with weather conditions and trip durations to evaluate wheter weather affected travel time. 
- Filtered out trips lacking corresponding weather data. 

### Exploratory data analysis (Python)
Using two CSV files provided (project_sql_result_01.csv and project_sql_result_04.csv), I: 

- Imported, inspected, and cleaned both datasets. 
- Verified data types and corrected inconsistencies. 
- Identified the top 10 neighborhoods by average trip completions in November 2017. 
- Created visualizations comparing: 
    - The number of trips by taxi company. 
    - The top 10 neighborhoods ranked by drop-off frequency. 
- Interpreted each chart and provided conclusions based on observed patterns. 

### Hypothesis testing (Python)
Using the file project_sql_result_07.csv, which contained trips from The Loop to O'hare International Airport, I tested the hypothesis: 
    "The average trip duration from The Loop to O'hare International Airport changed on rainy Saturdays." 

I:
- Defined the null and alternative hypotheses. 
- Selected an appropriate statistical test and significance level (alpha).
- Explained the reasoning behind my choice of test and evaluated wheter weather had statistically significant effect on trip duration. 

## Technologies Used 
- SQL (PostgreSQL). 
- Python (Pandas, NumPy, Matplotlib, Seaborn).
- Jupyter Notebook. 

## Contents
sprint_8.ipynb: Main notebook with data preparation, analysis, visualizations, and conclusions. 

## How to Use this repository 
1. Clone the repository. 
2. Open the file sprint_8.ipynb in Jupyter Notebook or VS Code. 

## Author 
Camilo Díaz
https://www.linkedin.com/in/camiloacdiaz