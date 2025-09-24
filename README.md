# Web Scraping Dashboard – EDA & Interactive Visualization

This repository contains a complete workflow for scraping product data from the web, performing Exploratory Data Analysis (EDA), and building an interactive dashboard. Built with Python, Pandas, Streamlit, and Plotly.

## Features

### Data Collection & Cleaning
- Scrape product data from websites using Python (BeautifulSoup / Requests)
- Remove missing or invalid values
- Standardize numeric and currency columns

### Exploratory Data Analysis (EDA)
- Summary statistics using .describe()
- Quick insights and random samples
- Visualizations of product prices, stock levels, and categories

### Interactive Dashboard
- Built with Streamlit for interactive exploration
- Filters: Category, Price Range, Stock Availability
- KPIs: Total Products, Average Price, Stock Overview, Top Products
- Visualizations:
  - Price vs Stock Quantity (scatter chart)
  - Stock distribution by category (bar chart)
  - Product price distribution (histogram)
- Custom dark theme and responsive layout

## Installation

pip install streamlit pandas plotly beautifulsoup4 requests

## Run the Dashboard

streamlit run dashboard.py

Dataset

Original scraped dataset: products.csv

Cleaned dataset used in the dashboard: cleaned_products.csv

Screenshots
![Dashboard Screenshot](Webscrapping_Dashboard.png)
