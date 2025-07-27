# Blinkit Sales Analysis

This project analyzes Blinkit's sales data to identify key performance indicators and visualize sales trends.

## Table of Contents

- [Project Overview](#project-overview)
- [KPI Requirements](#kpi-requirements)
- [Data Source](#data-source)
- [Libraries Used](#libraries-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Charts and Visualizations](#charts-and-visualizations)
- [How to Run the Notebook](#how-to-run-the-notebook)

## Project Overview

The goal of this project is to analyze Blinkit's sales performance by examining various factors such as item type, fat content, outlet location, and establishment year. The analysis focuses on calculating key performance indicators and creating visualizations to provide insights into the sales data.

## KPI Requirements

The analysis addresses the following key performance indicators:

- **Total Sales**: The overall revenue generated from item sales.
- **Average Sales**: The average revenue per sale.
- **Number of Items**: The total count of different items sold.
- **Average Rating**: The average customer rating of items sold.

## Data Source

The data used in this analysis is stored in the `blinkit_data.csv` file.

## Libraries Used

The following Python libraries are used in this notebook:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib.pyplot`: For creating static, interactive, and animated visualizations.
- `seaborn`: For creating informative statistical graphics.

## Data Cleaning and Preparation

Before analysis, the data underwent cleaning, specifically addressing inconsistencies in the 'Item Fat Content' column by standardizing values like 'low fat', 'LF', and 'reg' to 'Low Fat' and 'Regular'.

## Key Performance Indicators (KPIs)

The calculated KPIs are:

- Total Sales
- Average Sales
- Number of Items Sold
- Average Rating

These are displayed in the notebook with appropriate formatting.

## Charts and Visualizations

The notebook includes the following visualizations to illustrate sales trends:

- **Total Sales by Item Fat Content**: A pie chart showing the distribution of sales based on the fat content of items.
- **Total Sales by Item Type**: A bar chart displaying the total sales for each item type, sorted in descending order.
- **Fat Content by Outlet for Total Sales**: A grouped bar chart showing the total sales for 'Regular' and 'Low Fat' items across different outlet location tiers.
- **Total Sales by Outlet Establishment**: A line plot illustrating the total sales over the years of outlet establishment.
- **Sales By Outlet Size**: A pie chart representing the distribution of sales by outlet size.
- **Sales by Outlet Location**: A bar plot showing the total sales for each outlet location type.

## How to Run the Notebook

1. Ensure you have the `blinkit_data.csv` file in the same directory as the notebook or provide the correct path to the file.
2. Install the required libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`. You can use pip for installation:
