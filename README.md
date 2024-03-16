# 24Seven Expansion Analytics Project

## Overview

This project supports the strategic expansion efforts of 24Seven, a leading Canadian convenience store chain planning to open its 11th location. We developed a custom Power BI dashboard to analyze business performance, client demographics, and forecast sales.

## Problem Statement

24Seven's expansion challenge is threefold:
1. **Performance Understanding**: Analyzing current store performance and customer demographics to predict new market success.
2. **Forecasting Data Interpretation**: Navigating extensive datasets to accurately forecast sales and demand in new locations.
3. **External Data Incorporation**: Enhancing analysis with external datasets, like StatsCan, for a comprehensive understanding of local demographics, competition, and economic indicators.

## Data Sources

The project utilizes both internal and external data sources:
- **Internal**: Customers, Historical Sales, Product Categories, and Sales data.
- **External**: StatsCan data, including age and gender distribution.

## Forecasting Methodology

Forecasting is based on Linear Regression for its clarity and explainability:
- **Data Preparation**: Merging customer, sales, and product category data, with sales information aggregated by postal code and product category.
- **Feature Engineering**: Developing gender indicators, extracting date components, and calculating average age.
- **Model Training**: Utilizing data from 10 cities over three years, focusing on year, month, average age, and gender as features.
- **Sales Forecasting**: Projecting upcoming year sales using new city age and gender data from StatsCan.

## Power BI Dashboard

Key components of the dashboard include:
- **Data Transformation**: Incorporating a calendar table for centralized date management, data refresh tracking, and a sorting table for ranking current state analyses.
- **KPIs**: Critical metrics include Total Revenue (YoY, MoM), Revenue Growth Rate (%), Total Customers (YoY, MoM), Average Revenue Per Customer, and Customer Penetration Rate (%).

## Data Schema

- **Linkages**: The schema connects various tables (Calendar, Stores, Product Category, Customers, Future Sales Predictions) through specific keys, facilitating a comprehensive analysis ecosystem.

## Power Query Steps

Initial data preprocessing involved:
- Header promotion for distinct column titles.
- Data type adjustments for accurate representation.
- Column name refinement for intuitive dataset navigation.
