# Data Analysis using Python 

## Table of contents
- [Project-overview](#project-overview)
- [Data-Sources](#data-sources)
- [Tools-Used](#tools-used)
- [Project-overview](#project-overview)
- [Data-Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory-Data Analysis](#exploratory-data-analysis)
- [Data-Analysis](#data-analysis)
- [Results](#results)




## Project Overview
This data analysis aims to provide deep insights into a football dataset particularly in relation to their age, payment rate, youngest and oldest players, country with the highest number of players, top players with great shot power, 
players with best long passes and so on. 

## Data Sources 
The data used for this data analysis was culled from fifa19.csv which was downloaded from Kaggle. 

## Tools used 
- Python

## Data Cleaning/Preparation 
- At the intial phase, null values were identified and removed
- Also, a column was dropped
- Non-numeroc values were also removed from the numeric columns to be able to use aggregaate functions on them.
## Exploratory Data Analysis (EDA)
The EDA involved exploring the data to answer the following key questions;
1. Who is the youngest player?
2. Who are the 5 oldest players
3. Who are the top 5 players with long passes
4. Who are the top five players with great shot power?

## Data Analysis
```
Python
fifa[['Name', 'Value']].sort_values(by='Value', ascending=False)
```
## Results
- One of the results showed that Christiano Ronaldo is the oldest payer 

