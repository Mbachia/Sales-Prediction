# Sales-Prediction
![Company Logo](https://github.com/Mbachia/Sales-Prediction/blob/main/Company%20Logo/bigmart%20logo.jpg)

# Overview
Bigmart, a supermarket chain has collected 2013 sales data for products across multiple stores in different cities. The management has set out a challenge to data scientists to help the in creating a model that can predict sales per product for each store. 

# Objectives

## Main Objective

- To build a predictive model and predict the sales of each product at a particular outlet.

## Other Objectives

- To clean the data and fill in missing values
- To create a Graphical User Interface to predict sales
- To derive insights from the data

## Data Understanding

The data was obtained from [Kaggle](https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets). It contains 8523 rows and 12 columns. 
The columns include:
- Item_Identifier ---- Unique product ID
- Item_Weight ---- Weight of product
- Item_Fat_Content ---- Whether the product is low fat or not
- Item_Visibility ---- The % of the total display area of all products in a store allocated to the particular product
- Item_Type ---- The category to which the product belongs
- Item_MRP ---- Maximum Retail Price (list price) of the product
- Outlet_Identifier ---- Unique store ID
- Outlet_Establishment_Year ---- The year in which the store was established
- Outlet_Size ---- The size of the store in terms of ground area covered
- Outlet_Location_Type ---- The type of city in which the store is located
- Outlet_Type ---- Whether the outlet is just a grocery store or some sort of supermarket
- Item_Outlet_Sales ---- sales of the product in t particular store. This is the outcome variable to be predicted.