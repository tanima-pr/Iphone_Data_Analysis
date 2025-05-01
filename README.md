# iPhone Sales Data Analysis

A comprehensive Jupyter notebook that performs exploratory data analysis (EDA), data cleaning, and basic modeling on an iPhone sales dataset. This project demonstrates how to inspect data quality issues, visualize key patterns, and prepare the data for downstream tasks such as machine learning.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Features & Notebook Structure](#features--notebook-structure)  
3. [Dataset Description](#dataset-description)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
5. [Usage](#usage)  
6. [Key Results](#key-results)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## Project Overview

This repository contains a single Jupyter notebook (`Iphone_analysis.ipynb`) that guides you through:

- Loading and inspecting the iPhone sales dataset  
- Identifying and quantifying missing or duplicated data  
- Exploratory visualizations (e.g., top product descriptions, cancelled transactions)  
- Basic classification experiments (e.g., decision tree tuning on a sample dataset)  
- Generating simple recommendations based on purchase recency and frequency  

By following this notebook, you will learn best practices for:
- Data cleaning and validation  
- Descriptive statistics and missing‐value analysis  
- Simple data visualizations with Matplotlib  
- Preparing data for basic machine learning pipelines  

---

## Features & Notebook Structure

1. **Data Loading & Inspection**  
   - Read CSV into a pandas DataFrame  
   - Display initial rows and summary statistics  

2. **Missing Data Analysis**  
   - Calculate per‐column missing‐value percentages  
   - Visualize missing data distribution  

3. **Duplicate Record Detection**  
   - Identify and sort fully duplicated rows  
   - Display sample duplicates  

4. **Transaction Status Flagging**  
   - Add `Transaction_Status` column (`Cancelled` vs. `Completed`)  
   - Compute and report the percentage of cancelled transactions  

5. **Product Description Frequency**  
   - Count occurrences of each unique product description  
   - Plot the top 30 most frequent descriptions  

6. **Basic Classification Example**  
   - Demonstrate tuning of a Decision Tree on the Iris dataset  
   - Report accuracy for different train/test splits and hyperparameters  

7. **Recommendation System Sketch**  
   - Outline logic for a simple recency–frequency recommendation approach  

---

## Dataset Description

The dataset includes the following fields (example columns):

| Column Name        | Description                                   |
| ------------------ | --------------------------------------------- |
| `InvoiceNo`        | Unique transaction identifier                 |
| `StockCode`        | Product/item code                             |
| `Description`      | Product description text                      |
| `Quantity`         | Number of units per transaction               |
| `InvoiceDate`      | Date and time of purchase                     |
| `UnitPrice`        | Price per unit                                |
| `CustomerID`       | Unique customer identifier                    |
| `Country`          | Country of customer                           |

> **Note:** Some datasets may already include iPhone-specific fields; adjust the description accordingly.

---
