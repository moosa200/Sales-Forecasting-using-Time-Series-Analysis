# Sales Prediction using Time Series Analysis

## Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** and building a model to **predict sales for the next 7 days** using a retail dataset from a global superstore. The dataset spans **4 years** and includes information on sales transactions. The objective is to forecast the sales for the upcoming week based on historical data.

## Problem Statement
The task is to analyze historical sales data and predict the sales for the next 7 days, starting from the last available date in the training dataset. The project involves **Time Series Analysis** which helps in forecasting future values based on previous observations.

## Dataset
The dataset used in this project is the **Superstore Sales Dataset** which contains sales transactions with the following features:
- **Order Date**: The date when the order was placed.
- **Sales**: The value of the sale.
- **Quantity**: The quantity of products sold.
- **Category**: The category of the product sold.
- **Region**: The region where the order was placed.
  
You can upload this dataset to your environment using the following code:
```python
df = pd.read_csv('superstore_sales.csv')
