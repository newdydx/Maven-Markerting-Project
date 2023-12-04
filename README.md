# Maven-Markerting-Project
A Data Analysis Project done with Excel

# Introduction
This is a Data analysis and visualization project of a marketing company named Maven Marketing. The project was done as part of an online assignment by Tina on Twitter(X). The project was done using Excel. 

# Dataset
The dataset contains marketing campaign data of 2,240 customers of Maven Marketing, including customer profiles, product preferences, campaign successes/failures, and channel performance.

![Dataset](https://github.com/newdydx/Maven-Markerting-Project/blob/main/Datasets.png)

Data Dictionary: The dataset contains 28 columns and 2240 rows.

# Business Questions

The following questions were presented to find insights from the campaign. My goal is to find answers to these questions, find insights, and provide recommendations to the team.

a. What factors are significantly related to the number of web purchases?

b. Which marketing campaign was the most successful?

c. Which products are performing best?

d. Which channels are underperforming?

# Skills

• Data Cleaning

• Excel Formula and function

• Pivot table

• Data Visualization and Dashboard

## DATA CLEANING

Several steps were taken to clean the data including:
1. Checking for duplicates
2. Replacing null values to prevent data loss
3. Changing necessary data formats
4. Correcting null values

# Formulas and Functions
1. I derived the age column from the year_birth column by using the formula (2023 - B2) and for the other column respectively
2. The marital_status column with 8 different values was transformed into Marital status column to have just two values by using the function VLOOKUP(E2,G$2246:H$2253,2) for better analysis
3. The null Values in the Income column was replaced by the average of all the income with the formula IF(G2241="",AVERAGE(G2241:G4480),G2241)
4. The customer income field was grouped into 3 level income with the formula IF(H2<50000,"Low Earner",IF(H2<101000,"Middle Earner","High Earner"))
