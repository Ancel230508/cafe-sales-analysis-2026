
# Cafe Sales Data Analysis & Power BI Dashboard

## Project Overview
This project analyzes cafe sales transactions to understand revenue performance, product sales, and monthly sales trends.

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab
- Microsoft Power BI
- DAX
- GitHub

## Project Workflow
1. Data cleaning and preprocessing using Python.
2. Handling missing values and invalid records.
3. Exploratory Data Analysis (EDA).
4. Payment method and location analysis.
5. Monthly sales trend analysis.
6. Interactive dashboard development using Power BI.

## Dashboard Visualizations
- Monthly Revenue Trend
- Revenue by Product

## Key Performance Indicators
- Total Revenue
- Total Transactions
- Total Quantity Sold
- Average Transaction Value

## Data Cleaning Notes
- The original dataset contained 10,000 records.
- Three transactions were excluded due to invalid or unknown quantity and price information.
- Final cleaned dataset contains 9,997 records.
- Missing quantities and unit prices were imputed as 1 where applicable.
- Missing transaction dates were replaced with 1 January 2023.

These imputations may affect the accuracy of some sales results, particularly January revenue.

## Project Files
- `data/` – Cleaned dataset
- `notebooks/` – Python analysis notebook
- `powerbi/` – Power BI dashboard
- `screenshots/` – Dashboard screenshots

## Author
Ancel Rodrigues
