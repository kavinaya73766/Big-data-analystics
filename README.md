# Superstore sales data analystics

# Project Overview
This project analyzes the SuperStore sales dataset using Python. The objective is to explore sales performance, customer behavior, product categories, and regional trends through data cleaning, exploratory data analysis (EDA), and data visualization.

# Objectives
Clean and preprocess the dataset.
Perform Exploratory Data Analysis (EDA).
Analyze sales, profit, and discount trends.
Identify top-performing categories and sub-categories.
Visualize business insights using charts.
Generate meaningful conclusions from the data.
# Dataset
Dataset: sample_-_superstore.csv

The dataset contains information about customer orders, including:

# Order ID
Order Date
Ship Date
Customer Name
Segment
Country
State
Region
Category
Sub-Category
Product Name
Sales
Quantity
Discount
Profit

# Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn

# Analysis Performed
Data Loading
Data Cleaning
Missing Value Analysis
Duplicate Removal
Data Type Conversion
Descriptive Statistics
Sales Analysis
Profit Analysis
Category-wise Analysis
Region-wise Analysis
Data Visualization

# Visualizations
The notebook includes the following visualizations:

Sales Distribution
Profit Distribution
Category-wise Sales
Region-wise Sales
Sub-Category Analysis
Correlation Heatmap
Bar Charts
Histograms
Box Plots

# Key Insights
Identified the highest-selling product categories.
Compared sales across different regions.
Analyzed the impact of discounts on profit.
Identified profitable and loss-making products.
Observed customer purchasing trends.

# Installation
Install the required libraries using:

pip install pandas numpy matplotlib seaborn jupyter

# How to Run
Clone the repository.
Place the dataset (sample_-_superstore.csv) in the project folder.
Open SuperStore.ipynb using Jupyter Notebook.
Run all cells to reproduce the analysis.

# Project Structure
SuperStore/
│── SuperStore.ipynb
│── sample_-_superstore.csv
└── README.md

# Future Enhancements
Build an interactive dashboard using Power BI or Tableau.
Develop a sales forecasting model.
Perform customer segmentation using machine learning.
Deploy the project as a web application.

## Task 2 – Big Data Analysis
## Project Overview
This project focuses on performing data analysis and exploratory data visualization using the Sample Superstore dataset.

The main objective is to understand sales, profit, discount, delivery time, category-wise performance, and relationships between numerical variables using Python and popular data analysis libraries.

## Objectives
Load and inspect the Superstore dataset.
Perform basic data preprocessing.
Convert date columns into proper datetime format.
Calculate delivery time in days.
Check for missing values.
Analyze sales and profit by category.
Study the distribution of sales and profit.
Analyze the relationship between discount and profit.
Generate a correlation matrix and heatmap.
Visualize important business insights using graphs.

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab
Jupyter Notebook

## Dataset
Dataset: Sample Superstore Dataset

The dataset contains business transaction information such as:

Order Date
Ship Date
Category
Sales
Profit
Discount
Other numerical and categorical attributes

## Data Preprocessing
The following preprocessing steps were performed:

Imported the required Python libraries.
Loaded the CSV dataset using Pandas.
Inspected the dataset using df.info() and df.describe().
Converted Order Date and Ship Date into datetime format.
Calculated Delivery Days using the difference between shipping and order dates.
Checked unique values in the Category column.
Checked for missing values.

## Exploratory Data Analysis
1. Sales by Category
Total sales were calculated by grouping the data based on Category.

A bar chart was used to visualize the total sales for each category.

2. Sales Distribution
A histogram was created to understand the distribution of sales values across the dataset.

3. Profit by Category
A bar plot was created to compare profit across different product categories.

4. Sales Distribution by Category
A category-wise bar plot was used to visualize sales across different categories.

5. Profit Distribution
A box plot was used to study the overall distribution and variation of profit.

6. Profit Variation Across Categories
A category-wise box plot was created to understand the variation of profit between categories.

7. Impact of Discount on Profit
A scatter plot was used to analyze the relationship between Discount and Profit.

8. Correlation Analysis
Numerical columns were selected and a correlation matrix was calculated.

A heatmap was then generated to visualize the correlations between numerical variables.


## Exploratory Data Analysis

### Importing Libraries
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns


This cell imports the required Python libraries for data analysis and visualization.
Pandas is used for data manipulation, NumPy is used for numerical operations,
Matplotlib is used for creating graphs, and Seaborn is used for statistical visualization.



## Visualizations
The project includes the following visualizations:

Sales by Category
Sales Distribution Histogram
Profit by Category
Sales Distribution by Category
Profit Distribution Box Plot
Profit Variation Across Categories
Discount vs Profit Scatter Plot
Correlation Heatmap


## Sales by Category
<img width="1011" height="708" alt="image" src="https://github.com/user-attachments/assets/5d9271e1-f1b5-48c5-9cbf-92ad10e3f4ad" />

## Sales Distribution Histogram
<img width="1027" height="606" alt="image" src="https://github.com/user-attachments/assets/754b3167-59f2-48cc-b59b-3791ca2565a7" />

## Profit by category
<img width="842" height="585" alt="image" src="https://github.com/user-attachments/assets/f5f09757-a149-4bd3-b1c4-23e0aa6f9823" />

## Sales Distribution by category
<img width="765" height="590" alt="image" src="https://github.com/user-attachments/assets/b68d1514-36f8-4edf-87a5-7a6196b22b8c" />

## Profit Distribution
<img width="887" height="533" alt="image" src="https://github.com/user-attachments/assets/49fe2813-4246-456a-870e-1db9fff91b4b" />

## Profit variation Across Categories
<img width="840" height="583" alt="image" src="https://github.com/user-attachments/assets/7b11af53-b512-4cb2-8257-c65fb35d7336" />

## Discount vs profit Scatter plot
<img width="813" height="580" alt="image" src="https://github.com/user-attachments/assets/7d4249c9-f8f3-411c-ad2c-8fb05841d554" />

## Correlation Heatmap
<img width="773" height="657" alt="image" src="https://github.com/user-attachments/assets/f9298e53-a4e3-4a82-bed0-e7b3e7419965" />


## Key Analysis Areas
The analysis focuses on:

Sales Analysis

Category-wise sales performance
Overall sales distribution
Profit Analysis

Category-wise profit
Profit variation and distribution
Discount Analysis

Relationship between discount and profit
Delivery Analysis

Number of days between order and shipping
Correlation Analysis

Relationships among numerical variables

## Project Structure
Task-2-BD/
│
├── Task_2_BD.ipynb
├── task_2_bd.py
└── README.md

## How to Run
Using Google Colab
Open Task_2_BD.ipynb.
Upload the Sample Superstore CSV dataset.
Update the dataset path if required.
Run all cells sequentially.
Using Jupyter Notebook
Install the required libraries:

pip install pandas numpy matplotlib seaborn
Then open:

Task_2_BD.ipynb
and execute the cells.

## Conclusion
This project demonstrates the use of Python-based data analysis and visualization techniques on the Sample Superstore dataset. The analysis helps understand sales, profit, discount, delivery time, category performance, and correlations between numerical variables.

The project provides a basic foundation for performing Exploratory Data Analysis (EDA) and extracting useful insights from business data.
