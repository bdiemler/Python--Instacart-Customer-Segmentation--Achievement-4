# Python--Instacart-Customer-Segmentation--Achievement-4
Python-based exploratory data analysis of Instacart sales and customer behavior to inform targeted marketing strategies and customer segmentation.

This repository contains the full data analysis and reporting for the Instacart project, demonstrating core Python and Pandas skills to derive actionable business insights and define a targeted marketing strategy.

## Project Objective
The primary objective was to perform an initial Exploratory Data Analysis (EDA) on Instacart's customer and order data to uncover sales patterns, purchasing behaviors, and customer segmentation opportunities. The analysis directly supports the Vice President of Marketing and Senior Vice President of Sales in creating targeted advertising campaigns and boosting sales in underdeveloped sectors.

## Technical Methodology
The analysis was executed end-to-end using the following technical workflow and tools:

Programming Language: Python 3

Environment: Jupyter Notebook / Anaconda

Core Libraries: pandas, NumPy, matplotlib, seaborn, os

Data Handling: Merging multiple Instacart datasets, robust data consistency checks, handling mixed-type columns, identifying and addressing missing/duplicate data, and deriving key variables (e.g., price ranges, loyalty status).

Analysis: Extensive use of groupby() and aggregation for calculating metrics like busiest days/hours, average spending, and product frequency.

Visualization: Generated multiple data visualizations (e.g., bar charts, histograms, heatmaps) to clearly communicate purchasing habits across various customer segments.

## Key Business Questions Answered
The analysis provided data-driven answers to the stakeholders' critical questions:

Optimal Ad Scheduling: Identified the busiest days of the week and hours of the day to inform ad scheduling for maximum impact.

Spending Habits: Determined specific times of the day when customers spend the most money, guiding the advertisement of higher-priced products.

Product Popularity: Analyzed the highest frequency of orders by department to identify popular categories and inform market share strategies.

Customer Segmentation: Developed detailed customer profiles by analyzing:

Distribution of brand loyalty status.

Differences in ordering habits based on loyalty status and customer region.

Connection between age, income, and family status in purchasing behavior.

## Repository Structure
Instacart-Customer-Segmentation-EDA/
|-- 01_Initial_Wrangling/
|   |-- data_cleaning_and_merge.ipynb  # Initial Python script for data preparation
|-- 02_Exploratory_Analysis/
|   |-- sales_and_behavior_analysis.ipynb # Main EDA script answering key questions
|-- data/
|   |-- original_data/                    # Raw Instacart data sets
|   |-- prepared_data/                    # Cleaned and merged data sets (.pkl or .csv)
|-- visuals/
|   |-- [All charts and graphs exported from notebook]
|-- final_report.docx/pdf                 # Final report and strategic recommendations
|-- README.md                             # This file

## Data Citation
The Instacart Online Grocery Shopping Dataset 2017, Accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle on October 2025.
