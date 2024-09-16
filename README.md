# Restaurant-Ratings-in-Mexico

### Project Overview

The data is Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences which display total customer, total restaurant and in which state to show how customers rate their food and services based on gender and age.


![image](https://github.com/user-attachments/assets/9e92436f-ea9e-44d7-9682-e5b9e59736b5)



### Data Sources

Primary dataset used for this analysis is the combination of "consumer_preferences.csv", "consumers.csv", "rating.csv", "restaurant_cuisines.csv", "restaurants.csv". file from Quantum Analytics NG contained detailed information about customer rating of Mexicans foods and services in some selected restaurant i in city.

### Tools 

- Power Query - Data Cleaning
- Power Query - Data Merging / Modeling
- Power BI- Data Analysis
- Power BI - Create Report

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following task:

1. Loading data on Power query
2. Inspection and aligning 
3. Data cleaning and formatting
4. Loading data for Analyzing
5. Merging and modeling of Data
6. Create new measures 

### Exploratory Data Analysis

EDA involved exploring the Restaurant ratings in Mexico by real consumers from 2012 as:
- What is the overall customer rating by foods 
- What is the overall customer rating by service
- What is the overall customer rating by city
- What is the overall customer rating by age grade
- What is the overall customer rating by gender
- What is the overall customer rating 


### Data Analysis

Include some interesting formula worked with

```
 POWER BI
- count customer = COUNT(consumers[Consumer_ID])
- count no of male = COUNT(consumers[Marital_Status])
- No of Cuisine = DISTINCTCOUNT(restaurant_cuisines[Cuisine])
- Restaurant City = DISTINCTCOUNT(restaurants[Restaurant City])


```

### Results/Findings

The analysis results are summarized as follow:
1. The result shows that between the age of 20-25 visited restaurant more than any other age group  
2. City of San Luis Potosi has the highest restaurant visit than any other cities
3. Singles individual visited restaurant more that married even the gaps is beyond 90%
4. Preference on satisfaction is different based on the food and services 
 

### Recommendation

Based on the analysis, we recommend the following actions:
- Based on the result, those restaurants in the city of San Luis Potosi should expect more of singles patronage and I recommend that they should be preparing their foods to satisfying those that are single for them to increase sales
- Also I recommend more elderly advertisement focused, to encourage Adult and married to be visiting restaurant to have more Adult visitation
- City with low visitation should prepared their food to satisfied more of Singles to increase sales and make their advertisement single focused

