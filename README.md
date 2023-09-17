# Big-Mart-Sales-Prediction
# Sales Data Dataset README

## Overview

This dataset contains sales data for various products sold in multiple outlets. It includes information such as product weight, fat content, visibility, item type, maximum retail price (MRP), outlet details, and sales figures.

## Content

The dataset consists of the following columns:

- `Item_Identifier`: A unique identifier for each product.
- `Item_Weight`: The weight of the product.
- `Item_Fat_Content`: The fat content of the product (e.g., Low Fat, Regular).
- `Item_Visibility`: The visibility of the product in the store.
- `Item_Type`: The type of the product (e.g., Dairy, Soft Drinks).
- `Item_MRP`: The maximum retail price of the product.
- `Outlet_Identifier`: A unique identifier for each outlet.
- `Outlet_Establishment_Year`: The year when the outlet was established.
- `Outlet_Size`: The size of the outlet (e.g., Medium, NaN for missing values).
- `Outlet_Location_Type`: The location type of the outlet (e.g., Tier 1, Tier 3).
- `Outlet_Type`: The type of the outlet (e.g., Supermarket Type1, Grocery Store).
- `Item_Outlet_Sales`: The sales figure for the product in the outlet.

## Context

This dataset can be used for various data analysis and machine learning tasks, including:

- Predicting sales figures based on product attributes and outlet details.
- Understanding the impact of factors like visibility, fat content, and item type on sales.
- Exploring trends and patterns in sales data.

## Usage

Feel free to use this dataset for your data analysis or machine learning projects. You can load the data into your preferred data analysis tool or programming language (e.g., Python, R) and start exploring the insights it offers.

## Data Analysis with RandomForestRegressor

We applied a RandomForestRegressor model to this dataset to predict sales figures. Here are some key findings from the analysis:

Plot 1: You've created subplots to visualize the count distribution of categorical variables. Specifically, you've explored 'Outlet_Size,' 'Outlet_Location_Type,' and 'Item_Fat_Content' both individually and in relation to 'Outlet_Type' using count plots. This helps you understand the distribution of these categorical variables and how they relate to the outlet types.

Plot 2: In this step, you've created a subplot to visualize the kernel density estimate (KDE) plots for several numerical variables: 'Outlet_Establishment_Year,' 'Item_Outlet_Sales,' 'Item_Weight,' 'Item_Visibility,' and 'Item_MRP.' KDE plots provide insights into the distribution and density of these variables.

Plot 3: You've created a count plot to visualize the distribution of 'Outlet_Establishment_Year.' This plot helps you understand the distribution of outlets over the years.

Plot 4: You've created a count plot to visualize the distribution of 'Item_Type' across the dataset. This plot allows you to see the distribution of different types of items.

These steps and visualizations are essential for understanding the data distribution, identifying patterns, and gaining insights before building predictive models like RandomForestRegressor.
