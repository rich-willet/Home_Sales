# Big Data with PySpark: Home Sales Analysis

This repository contains the code and instructions for analyzing home sales data using PySpark. The project focuses on querying and processing large datasets, demonstrating Spark's capabilities with filtering, grouping, and aggregations, as well as caching and partitioning data for optimized performance.

## Challenge Overview

The challenge includes the following tasks:

1. **Read Data from S3**  
   Load home sales data from an AWS S3 bucket into a PySpark DataFrame.

2. **Data Analysis Queries**  
   Perform various queries to analyze the dataset, including:
   - Average price of homes with specific attributes (e.g., bedrooms, bathrooms).
   - Average price of homes grouped by view ratings and build years.
   - Runtime comparison between cached and uncached queries.

3. **Optimization Techniques**  
   - Cache temporary tables for performance improvement.
   - Partition data by build year and save in Parquet format for optimized storage.

4. **Runtime Comparisons**  
   Compare runtimes for queries executed on cached data, raw Parquet data, and uncached data.

## Prerequisites

To run the code, ensure you have the following installed:
- Python 3.x
- PySpark
- An AWS S3 bucket (or equivalent public data link)
- Time tracking (`time` module for runtime comparisons)

