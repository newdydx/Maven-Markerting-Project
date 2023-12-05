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

1. What factors are significantly related to the number of web purchases?

2. Which marketing campaign was the most successful?

3. Which products are performing best?

4. Which channels are underperforming?

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

# Data Analysis

> **1. What factors are significantly related to the number of web purchases?**

a. Education Level- Customers who are graduates purchased more items through the web than every other customer. They make up 51.81% of customers who purchased through the web.
   
![Education visuals](https://github.com/newdydx/Maven-Markerting-Project/blob/main/graduatepurchases.png)

b. Income- Customers who are middle earners with an income ranging from $51000-$100000 purchased more items through the web. Middle earners make up 68.35% of the customers who purchased through the web.

![Income](https://github.com/newdydx/Maven-Markerting-Project/blob/main/INCOME.png)

c. Country- Spain and Saudi Arabia were the highest country to purchase items through the web respectively.

![Country](https://github.com/newdydx/Maven-Markerting-Project/blob/main/COUNTRY.png)

> **2.  Which marketing campaign was the most successful?**

The 4th campaigh was the most successful when compared to the other campaigns with a 7.46% conversion rate.

![Campaign](https://github.com/newdydx/Maven-Markerting-Project/blob/main/campaign.png)

> **3. Which products are performing best?**

Wine and Meat are the top 2 best performing products with 50.17% and 27.56% of the total revenue respectively.

![Products](https://github.com/newdydx/Maven-Markerting-Project/blob/main/AMOUNT.png)

> **4. Which channels are underperforming?**

The catalog channel wasthe least channel used in purchasing products and most of the products were purchased through the store.

![channels](https://github.com/newdydx/Maven-Markerting-Project/blob/main/CHANNELS.png)


