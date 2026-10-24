# Superstore Sales Analysis Using Python

## Project Overview

This project analyzes Superstore sales data to understand sales performance, profitability, customer segments, regional trends, and state-level business performance.

The analysis uses Python libraries to clean and explore the dataset, calculate key business metrics, and create visualizations that help identify important business insights.

## Objectives

- Clean and prepare the sales dataset for analysis.
- Calculate key sales and profitability metrics.
- Analyze sales by category, region, customer segment, and sub-category.
- Identify monthly sales trends.
- Compare sales and profit across sub-categories.
- Analyze state-level sales and profitability.
- Present findings through charts and an interactive US map.

## Tools and Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Dataset

The project uses the Sample Superstore dataset containing sales records and information about regions, states, product categories, customer segments, sales, profit, quantity, and order dates.

Dataset source: [Sample Superstore Dataset](https://www.mathewkanalytics.com/datasets/superstore-sales/)

The dataset used in this analysis contains 9,994 records before duplicate removal. After removing 2 duplicate records, 9,992 records remain.

## Project Workflow

### 1. Data Cleaning and Preparation
- Inspected the dataset structure and data types.
- Converted the Order Date column to datetime format.
- Checked for missing values and duplicate records.
- Removed duplicate records.
- Reviewed descriptive statistics.

### 2. Key Performance Indicators
Calculated total sales, total profit, total quantity sold, total order records, average sales per record, and average profit per record.

### 3. Exploratory Data Analysis
Analyzed:
- Sales and profit by category
- Sales and profit by region
- Sales by customer segment
- Monthly sales trends
- Sales and profit by sub-category
- State-level sales and profitability

### 4. Data Visualization
Created visualizations including:
- Bar charts
- Horizontal bar charts
- Donut chart
- Line chart
- Lollipop charts
- Scatter plot
- Interactive US sales map

## Key Findings

- **Total Sales:** 2,296,914.56
- **Total Profit:** 286,408.34
- **Total Quantity Sold:** 37,869
- **Records After Cleaning:** 9,992

### Sales and Profitability Insights

- Technology generated the highest sales and profit among the three product categories.
- Furniture generated substantial sales but comparatively low profit.
- The West region recorded the highest sales and profit.
- The Consumer segment contributed the largest share of sales.
- Copiers generated the highest profit among sub-categories.
- Tables recorded the largest sub-category loss.
- California recorded the highest state-level sales and profit.
- Texas recorded the largest state-level loss, followed by Ohio and Pennsylvania.

## Business Recommendations

- Investigate pricing, discounting, and costs for loss-making product sub-categories, especially Tables.
- Review the performance of states with negative profits.
- Study the strong profitability of Copiers and Accessories.
- Monitor monthly sales trends to support sales and inventory planning.
- Evaluate both sales and profit when assessing business performance.

These findings identify areas for further investigation; additional analysis is required to establish the causes of losses.

## Project Files

- `Superstore_Sales_Analysis.ipynb` — Jupyter Notebook containing the data cleaning, analysis, code, and visualizations.

## Conclusion

This project demonstrates practical Python data analysis skills, including data cleaning, exploratory data analysis, aggregation, visualization, and business insight generation.

It is a portfolio project developed to practice real-world-style data analysis workflows and communicate findings clearly.

## Author

**Pranali Pakere**

Aspiring Data Analyst | Python | SQL | Excel | Power BI
