Sales Data Analysis & Linear Regression Project

 Project Overview
This project demonstrates an end-to-end data analysis workflow using a sales dataset.  
It focuses on cleaning raw data, engineering useful features, exploring trends,
and building a simple regression model to understand relationships within the data.

The goal of this project is not just model accuracy, but to show good data practices,
clear thinking, and reproducible analysis, 
making it suitable for learning and presentation.

 Objectives
- Clean and preprocess raw sales data
- Engineer meaningful features for analysis
- Analyze sales trends by time, city, and product
- Build and evaluate a linear regression model
- Practice real-world data analysis workflows


 Dataset Description
Each row in the dataset represents a product purchased in a customer order.

 Key Columns
- order_id – Unique order identifier  
- product – Product name  
- quantity_ordered – Number of units purchased  
- price_each – Price per unit  
- order_date – Date and time of purchase  
- purchase_address – Customer address  


Data Cleaning

 Handling Missing Values
Rows where all values were missing were removed to ensure data integrity.

python
df = df.dropna(how="all")
