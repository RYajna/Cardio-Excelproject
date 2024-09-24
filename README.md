# Cardio & Fitness Analysis

## Project Overview
The Cardio & Fitness Dataset provides insights into consumer behavior and purchasing patterns, including age, gender, and product preference. Analyzing this data can help the business in optimizing product offerings and tailor marketing strategies. It serves as a valuable resource in understanding the customer demographics.


### Data Source
Cardio & Fitness data: The dataset used for this analysis is the "Cardio&Fitness.xlsx" file, This dataset contains customer treadmill purchasing information. The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/vsridevi/cardio-good-fitness).

### Tool used
Excel

### Data Cleaning/Preparation
This data has already been cleaned.
I have only created the following columns to facilitate data visualisation:
 - Age range, using the below formula:
``` =IF(B2<=25, "18-25", IF(B2<=35, "26-35", IF(B2<=45, "36-45", "46+")))```
 - Income Range
   ``` =IF(A2<=50000, "25K-50K",IF(A2<=75000,"50K-75K",IF(A2<=100000,"75K-100K","+100K")))```

### Exploratory Data Analysis
EDA involved exploring the data to answer questions such as:
 - Is there a relationship between age and how often customers want to use the treadmill?
 - What proportion of the customers were male vs female and what % difference is there between partnered & single customers? 
 - Is there a relationship between the income range of customers and how much they want to use the treadmill in a week?
 - Is there a relation between how fit a customer rates himself and their weekly expected usage?
 - Is there a product preferance for each age range?


### Findings
 - Average usage across all age seems to be 3 times per week
 - Customers between the ages of 36 to 45 are slightly more inclined to want use the treadmill more
 - More male customers than female customers irrespective of marital status
 - Approximately 10% more of the customers are partnered as opposed to single
 - 46% of Customers make between 25k - 50k while 42% make between 50k - 75k
 - Higher earning customers want to use the treadmill more
 - Customers who rate themselves fitter expect to run more
 - The TM195 seems to be most popular across all ages followed by the TM498 except for customers above 46

### Recommendations
1. Marketing can target more female & single customers in order to increase sale
2. Increase exposure of the TM798; put discounts for the product in order to boost sales

### Limitations
1. The data does not contain any information on the purchase date which could have helped further in analysing this data. 
2. The data is not really consistent or realistic. For example if I select a female clothing item from the ratings table, the % for Male is greater than that for Female.

   
