# Sales Performance Analysis of Walmart Stores

## Overview
This repository contains a comprehensive presentation and accompanying SQL queries used to analyze the sales performance of Walmart stores. The project leverages advanced SQL techniques to extract key insights related to sales totals, growth rates, profitability, customer segmentation, and more.

## Repository Contents
- **Sales_Performance_Analysis_of_Walmart_Stores_Presentation.pptx**  
  *Presentation detailing the analysis, including SQL queries, results, and key findings.*

## Analysis Tasks and SQL Queries

### Task 1: Total Sales for Each Branch
- **Query:**
  ```sql
  SELECT Branch, SUM(Total) AS total_sales  
  FROM walmartsales_dataset  
  GROUP BY Branch  
  ORDER BY total_sales DESC;
