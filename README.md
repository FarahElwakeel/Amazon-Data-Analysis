# Amazon Sales Data Analysis & Dashboard

## Project Overview

This project involves analyzing a significant dataset of Amazon sales transactions to extract actionable business insights. The goal was to transform raw sales data into an interactive, professional Excel dashboard that allows stakeholders to track key performance indicators (KPIs), analyze regional performance, and identify top-selling product categories.

This repository contains the raw data, the processed data, and the final interactive Excel dashboard built according to specific business requirements.

## Business Problem & Requirements

According to the project brief (available in the `Requirements/` folder), the Sales Manager needed a dynamic solution to track performance metrics. The specific requirements included:

* **KPI Tracking:** Instant visibility of Total Sales, Total Profit, Total Quantity ordered, and Profit Margin %.
* **Temporal Analysis:** Ability to view Sales and Profit trends over time (Yearly and Monthly).
* **Product Analysis:** Understanding which Categories and Sub-Categories are driving performance.
* **Geographical Analysis:** Analyzing sales performance by State.
* **Interactivity:** The dashboard must allow filtering by Year, Customer Segment, and Region.

## Key Features & Insights

The final dashboard meets all requirements and provides the following insights:

* **Interactive Slicers:** Users can dynamically filter the entire dashboard by Year (2015-2018), Region (Central, East, South, West), and Segment (Consumer, Corporate, Home Office).
* **Sales Trends:** A combination chart shows the relationship between Sales revenue and Profit over the years.
* **Category Performance:** A bar chart highlights that the 'Technology' category generates the highest sales.
* **Top Products:** An analysis of sub-categories shows that 'Phones' and 'Copiers' are among the highest revenue generators.
* **Regional Heatmap:** A map visualization indicates that California and New York are the dominant states for sales activities.

## Tools Used

* **Microsoft Excel:** The core tool used for the entire project lifecycle.
* **Data Cleaning:** Handling missing values, standardizing formats, and ensuring data quality.
* **Data Processing:** Utilizing Excel formulas and functionalities to prepare data for analysis.
* **Pivot Tables:** Used extensively to summarize complex data and create the underlying tables for visualizations.
* **Data Visualization:** Creating charts (Bar, Line, Map) and designing a clean, professional user interface.
* **Slicers:** Connecting multiple PivotCharts to provide interactive filtering capabilities.



## Project Structure

* `Amazon_Dataset_Task1.xlsx`: The final, interactive Excel dashboard file. **Download this file to interact with the slicers and view the underlying pivot tables.**
* `Data/raw_sales_data.xlsx`: The original, unprocessed dataset.
* `Data/cleaned_sales_data.xlsx`: The dataset after cleaning and preparation steps.
* `Requirements/Task6_Dashboard.pdf`: The original task document outlining the business needs.
