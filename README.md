# Vanguard Threadworks: Regional Operations & Sales Analysis

## Executive Summary
This repository contains an Analysis-Driven Capstone project for **Vanguard Threadworks**, an e-commerce merchandise brand. The objective of this analysis is to evaluate operational performance, customer satisfaction, and revenue generation by comparing transaction data between two primary shipping hubs: **The East Coast (New Jersey)** and **The West Coast (Portland)**.

## Business Objectives
* **Operational Efficiency:** Analyze shipping charges, delivery workflows, and regional volume to identify cost-saving opportunities.
* **Customer Satisfaction:** Evaluate customer ratings and reviews across the East and West Coast fulfillment centers to isolate service bottlenecks.
* **Sales Performance:** Compare Total Sales, Quantity, and Sales per Unit segmented by product category and buyer demographics (Age, Gender).

## Repository Structure
The project is organized into the following directories:

* **`/data`**: Contains the datasets used for analysis.
  * `merch_sales_prepared.csv`: The initial scoped dataset.
  * `vanguard_cleaned_data.csv`: The final, processed dataset ready for EDA.
* **`/notebooks`**: 
  * `01_data_cleaning.ipynb`: Pipeline for handling missing values, standardizing formats, and ensuring data integrity.
  * `02_workflow_analysis.ipynb`: The core Exploratory Data Analysis (EDA) comparing the New Jersey and Portland hubs.
* **`/reports`**: Official project documentation and deliverables.
  * `Vanguard_proposal.pdf`: Initial project scope, problem statement, and methodology.
  * `Data_Processing_Report.pdf`: Detailed documentation of the data wrangling process.
  * `final_report.pdf`: Executive summary of insights and actionable business recommendations.
* **`/chart_images`**: Exported high-resolution visual assets generated during EDA (e.g., regional sales comparisons, shipping cost distributions).

## Key Insights & Visualizations
*The West Coast hub showed a 15% higher average shipping cost, while the East Coast maintained higher overall customer ratings.*

## Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

