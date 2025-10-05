# Project 6 - TripleTen

This projectwas part of my Data Analyst trainiing at TripleTen. 
I worked for the online store **Ice**, which sold video games worldwide. User and expert reviews, genres, platforms (such as Xbox or PlayStation), and historical sales data were available from open sources. The main goal was to identify patterns that determined whether a game would be successful, helping to detect promising projects and plan effective marketing camppaigns. 

The data set contained information up to 2016. The analysis simulated a real-life scneario in which it was December 2016,, and I was planning a campaign for 2017. Additionally, the dataset included a **ESRB rating** column, which classified games according to their content and suitable audience. 

## Project Tasks

### Data preparation 
- Renamed the column titles to lowercase and converted data types as required. 
- Described all data type and explained the reasons behind them. 
- Handled missing values, providing justifications for eithher imputing or keeping them. 
- Addressed "TBD" (to be determined) values with and appropiate strategy. 
- Calculated total sales (the sum of sales across all regions) for each game and stored them in a new column. 

### Data analysis 
- Analyzed the number of games released per year and evaluated the representativeness of the data over time. 
- Examined sales trends by platform, identifying those with the highest total sales and tracking how their popularity changed over the years. 
- Determined which years were relevant for building a model to predict sales for 2017. 
- Identified leading, growing, and declining platforms to find potentially profitable ones. 
- Created box plots to compare global games sales byb platform and analyzed significant differences in average sales. 
- Explored how user and critic reviews affected sales on a popular platform using scatter plots and correlation analysis. 
- Compared the sales of the same games across multiple platfforms. 
- Investigated the distribution of games by genre and idenfied the most profitable ones. 

### Regional user profiling 
- Performed statistical hypothesis testing to validate assuptions: 
1. The average user ratings for Xbox One and PC were the same. 
2. The average user ratings for the Action and Sports genres were different. 

Defined the null and alternative hypotheses, selected an appropriate significance level (alpha), and justified the choice of statistical tests used for the analysis. 

## Technologies used
- Python (NumPy, Pandas, Matplotlib, Seaborn) 
- Jupyter Notebook

## Contents 
sprint_8.ipynb: Main notebook with data preparation, analysis, visualizations, and conclusions. 

## How to use this repositoy
1. Clone the repository. 
2. Open the file sprint_8.ipynb in Jupyter Notebook or VS Code. 

## Author 
Camilo Diaz 
https://www.linkedin.com/in/camiloacdiaz
