# SalesStore_Project_Oluwatosin

## Introduction
This project involves the analysis of products sold and their corresponding shipping data.
The dataset contains details about:
* Customer orders,
* Including product categories,
* Sales amount,
* Quantity sold,
* Shipping methods,
* Regions, and
* Profit generated.    

The goal of the analysis is to uncover patterns in :
* Sales performance,
* Shipping efficiency and
* Product profitability across different categories and regions.

## Problem Statement
The company wants to gain a deeper understanding of its product sales and shipping performance. Specifically, the goal is to: 
* Indentify top_performing and underperforming product categories.
* Analyze how different shipping modes impact profit and delivery times.
* Discover regional trends in sales and profit generation.
* Uncover patterns in customer demand over times tos upport inventory and marketing decisions.

## Data Sourcing 
The dataset used in this project was provided by Datafied academy.
At this stage, the dataset has been uploaded to this Github repository to serve as the foundation for subsequent transformation, cleaning, and analysis steps using Power BI. 


## Data Transformation 
Before analysis, the dataset requires certain structural adjustments to make it suitable for modelling and reporting.  Transformation includes: 
* Converting 'Order date' and 'Ship date' coulmns to proper date formats.
* Creating new columns, including ( Order month, Order year, etc).
* Standardize column names.
* Ensure that categorical fields are properly formatted for grouping.
These transformations would be applied in Power BI's Power Query.

## Data Cleaning 
* Check for missng or blank values.
* Remove duplicates.
* Verify that numerical fields (e.g., 'Sales', 'Profit', 'Quantity' are in the correct data type.
* Ensure date values are valid.

## Data Modelling 
At this stage of the project, the dataset consists of a single flat table containig all neccessary information for analysis. 
Since no additional tables are currently available, a schema is not required. However, during the Power BI phase, logical grouping and relationships will be stimulated through calaculated columns and measures where appropriate. 
  
