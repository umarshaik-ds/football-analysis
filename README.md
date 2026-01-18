# FIFA 2022 World Cup Data Analysis
## Project Description
This repository contains a Power BI project focused on the FIFA 2022 World Cup. The project demonstrates a full data analysis workflow: from connecting to raw data and performing complex ETL (Extract, Transform, Load) tasks to designing an interactive dashboard that provides insights into team statistics and match outcomes.


![](https://github.com/umarshaik-ds/football-analysis/blob/main/fifa-world-cup-2022-logo-png_seeklogo-389149.webp)


## Dataset Information
The dataset includes comprehensive statistics from the FIFA 2022 tournament, covering: 

Match Details: Scores, dates, and venues.

Team Stats: Possession, shots on target, and passing accuracy.

Player Discipline: Yellow cards, red cards, and fouls committed.

## Data Cleaning & Transformation (Power Query)
Before building the visuals, I performed extensive data cleaning to ensure accuracy:

## Data Standardization:
Fixed naming inconsistencies for teams and stadiums.

## Data Type Optimization:
Converted statistical columns into numerical formats for calculation.

## Handling Missing Values: 
Replaced nulls in performance metrics with zeros to avoid calculation errors.

## Feature Engineering:
Created custom columns such as [Goal Difference] and [Match Outcome] using Power Query M-formulae.

## Data Modeling
## Schema:
I utilized a Star Schema to organize the data, ensuring efficient filtering and high performance.

## DAX Measures:
I developed custom DAX measures for key performance indicators (KPIs) like Total Goals, Average Possession, and Win Percentage.

## Dashboard Visualizations
The report focuses on three high-impact visuals to tell the story of the tournament:

![](https://github.com/umarshaik-ds/football-analysis/blob/main/fb.png)

### 1. Team Scoring Efficiency (Bar Chart)
A comparison of goals scored versus total shots. This visual highlights which teams were the most clinical in front of the goal.

### 2. Possession vs. Winning Correlation (Scatter Plot)
A deep dive into whether controlling the ball led to victory. This visual plots ball possession percentage against matches won to identify tactical trends.

### 3. Disciplinary Record Overview (Heatmap/Table)
A breakdown of team conduct, tracking yellow and red cards. It identifies the most aggressive teams and those who maintained the highest level of fair play.

## Tools Used
## Power BI Desktop: 
For data modeling and visualization.

# Power Query:
For data cleaning and transformation.

# DAX:
For advanced data calculations.
