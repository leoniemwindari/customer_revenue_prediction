# Customer Revenue Prediction : Project Overview
This project comes from Pareto Principle that states that 80% of your company sales comes from 20% of your customers. In this project, I will analyze data from Google Merchandise Store (also known as GStore, where Google swag is sold) to predict revenue from each customers. By doing this project, hopefuly it can helps small businesses on projecting their budget to get the most of it. Hopefuly we can also see how's the customer behavior on buying things and what variable affecting the company revenue the most.
   
## Code and Resources Used 
**Python Version:** 3.8 

**Packages:** 

## Dataset
This dataset is a data from Google Merchandise Store (also known as GStore, where Google swag is sold).
* Source : Kaggle - https://www.kaggle.com/c/ga-customer-revenue-prediction/data
* Note : Per row is one visit to the store, while the result will be the total revenue per user. There are multiple columns which contain JSON blobs of varying depth. In one of those JSON columns, totals, the sub-column transactionRevenue contains the revenue information we are trying to predict. This sub-column exists only for the training data.
* **Due to the formatting of fullVisitorId you must load the Id's as strings in order for all Id's to be properly unique!**


## Project Detail
The goals is to predict the natural log of the sum of all transactions per user for their transactions in the future time period of December 1st 2018 through January 31st 2019. **Note that the dataset does NOT contain data for December 1st 2018 to January 31st 2019. You must identify the unique fullVisitorIds in the provided test_v2.csv and make predictions for them for those unseen months.** Bellow is the target formula for this project:

![alt text](https://github.com/leoniemwindari/customer_revenue_prediction/blob/main/image.png)

**Machine Learning Models:**
For this project I will implement the data to these models and determine which one fits the best:
* Logistic Regression
* K-Nearest Neighbor
* Support Vector Machine
* Random Forest

**Model Parameter:**
To determine which machine learning model fits the dataset the best, I will use this parameter to decide:
* Precision-Recall
* F1-Score
* ROC-AUC


## Step-by-Step Project:
## Data Wrangling
1. Extracting values from some variables with JSON type and Nested Dictionary


## Data Analysis


## Model Building and Comparison
 

## Results



## Conclusion


## Contact
Leonie M. Windari - @leoniemw_ds - leoniemwindari98@gmail.com
Website - https://leoniemwindari.wordpress.com/
