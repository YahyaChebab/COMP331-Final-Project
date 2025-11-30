# Online Retail Data Quality & Customer Segmentation

## COMP/STAT 331 - Data Quality Final Project
### University of the Fraser Valley
#### Student: Yahya Chebab
#### Date: November 28, 2025

## Project Overview

This project analyzes online retail data to show how data quality problems affect customer segmentation. Using real transaction data, I identify data quality issues and fix them before grouping customers into segments.

## Files in This Repository

- COMP331_Final_Project_data_analysis.ipynb - Complete Jupyter notebook with all analysis
- data.csv - Online retail dataset (541,909 transactions)

## How to Run

1. Download the files from this repository
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn ydata-profiling
3. Open the notebook:
   jupyter notebook COMP331_Final_Project_data_analysis.ipynb
4. Run all cells to see the full analysis

## What the Analysis Shows

### Data Quality Problems Found
- Missing Data: 25.1% of records missing CustomerID
- Invalid Data: Negative prices and quantities
- Inconsistent Data: Duplicate records and calculation errors

### Customer Segments Created
- Low-value customers: 4,279 customers (98.6%) - $1,374 average spending
- Mid-value customers: 50 customers (1.2%) - $31,026 average spending  
- High-value customers: 9 customers (0.2%) - $161,868 average spending

## Course Concepts Used

- Data Quality Dimensions: Completeness, validity, consistency
- Week 10: Data warehousing and ETL concepts
- Week 11: Data mining and clustering algorithms
- ETL-Quality Pipeline Framework from our course

## Author

Yahya Chebab
COMP/STAT 331 - Data Quality
University of the Fraser Valley