# Space-Missions-Analysis

![](introduction-photo.jpg)

## Introduction
This project analyzes and creates visualizations of a space missions database with the objective of elucidating the differences and characteristics of how companies and countries are involved in the "Space Race."

The development of this project was part of a python course I completed. The database utilized was scraped from nextflight.com. To see the complete code and other visualizations of the project, you can access the notebook in this link https://drive.google.com/file/d/14tMzDUFyKophH2bI1xGGMKRyF5ak7MGT/view?usp=sharing


## Problem Statment
1. What was the structure of the database?
2. What were the differences between organisations in terms of launches and money spent?
3. What was the distribution of the prices?
4. What where the differences between countries in terms of launches?
5. How did lauches changed over the months and years present in the database?

## Skills / concepts demostrated
-Implementation of libraries such as Pandas, Plotly Express, iso3166, and Seaborn.
-Grouping data into different categories and preparing it for visualization.
-Data transformation:
  -Extracting data from within strings.
  -Conversion into different data types (e.g., from string to integer, float, etc.).
  -Generating general descriptive statistics of variables.
  -Utilizing dictionaries to map country names.
  -Employing country names to obtain corresponding ISO codes.
  -Converting time units to facilitate plotting various data over time.
  -Applying rolling mean for data smoothing.

## Visualization
1. What was the structure of the database?
  1.  the shape of the dataframe is (4324, 9)
  2.the columns names are:
     Unnamed: 0.1
     Unnamed: 0
     Organisation
     Location
     Date
     Detail
     Rocket_Status
     Price
     Mission_Status
2. What were the differences between organisations in terms of launches and money spent?
  ![](launchesxorganisation.png)
  ![](money-launch-org.png)
3. What was the distribution of the prices?
  ![](how-expensive-are-the-launches.png)
  ![](prices-box-plot.png)
4. What where the differences between countries in terms of launches?
  ![](launchesxcountry.png)
  ![](failuresxcountry.png)
  ![](pie-mission-status.png)
5. How did lauches changed over the months and years present in the database?
   ![](launchesxyear.png)
   ![](month-launcher-roll.png)
   ![](year-launches-country.png)
   ![](year-launches-organization.png)
