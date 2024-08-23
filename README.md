# Plant Company Quantity Performance Dashboard

## Overview

This repository contains the Power BI dashboard project designed to monitor and analyze the quantity performance of a plant company. The dashboard offers a range of visuals that provide insights into key performance indicators such as Gross Profit, Year-to-Date (YTD) sales, Prior Year-to-Date (PYTD) sales, and Gross Profit Percentage (GP%). It also includes detailed performance breakdowns by country, month, and product type.

## Files in this Repository

- **Perfomance Report Plant.pbix**: The Power BI report file containing all the visuals, measures, and data transformations.
- **Plant_DTS.xlsx**: The Excel data source used in the Power BI report, containing raw data on quantity, sales, and other relevant metrics.
- **PowerBiProj.png**: A screenshot of the Power BI dashboard, showcasing the final output.

## Dashboard Details

### Key Metrics
- **Gross Profit**: Total gross profit over the selected period.
- **Quantity**: Total units sold Year-to-Date.
- **Sales**: Total sales revenue Year-to-Date.
- **YTD vs PYTD**: A comparison between the current Year-to-Date sales and the previous year's sales.
- **GP%**: Gross Profit Percentage, indicating profitability.

### Visuals
1. **Tree Map**: Displays the bottom 10 countries based on YTD vs PYTD sales.
2. **Waterfall Chart**: Shows monthly changes in YTD vs PYTD by country and product.
3. **Bar and Line Chart**: Represents Quantity YTD & PYTD performance by month and product type.
4. **Scatter Plot**: Analyzes Account Profitability by Gross Profit Percentage (GP%) and Quantity.

### Filters
- **Year Filter**: Allows users to filter the dashboard metrics by a specific year.

## Skills and Tools Utilized
- **Data Modeling**: Designed data models to support dynamic and efficient data retrieval.
- **DAX (Data Analysis Expressions)**: Created measures and calculations to display KPIs and other metrics.
- **Power Query**: Used for data transformation and cleansing.
- **Visualization**: Developed interactive and visually appealing reports using various Power BI visualizations.
- **Excel**: Utilized as the data source for the dashboard.
- **Data Analysis**: Analyzed trends and patterns in sales and profitability.

## How to Use
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/hamig0har/PowerBi-Plant-Company-Dashboard
