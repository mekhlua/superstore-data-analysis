📊 Superstore Data Analysis (Pandas EDA)
📌 Overview

This project explores the Superstore dataset using Python and Pandas to perform exploratory data analysis (EDA). The objective is to extract meaningful business insights by analyzing sales, profit, customers, and regional performance. The analysis includes data cleaning, feature engineering, aggregation, pivot tables, and visualization.

📂 Dataset

The dataset used in this project is the Superstore dataset from Kaggle. It contains retail transaction data including customer information, product details, sales, and profit.

Source: Kaggle
Dataset: Superstore Dataset
File: Sample - Superstore.csv
🎯 Problem Statement

Retail businesses need data-driven insights to improve performance. This project aims to answer key business questions such as which categories are most profitable, which regions underperform, how sales evolve over time, and which customers contribute the most revenue.

🛠️ Tools Used

This analysis was performed using Python with the following libraries:

Pandas for data manipulation and analysis
Matplotlib for data visualization
🔄 Project Workflow
1. Data Loading & Inspection

The dataset was loaded using Pandas and inspected to understand its structure. This included reviewing column names, data types, and generating summary statistics to gain an initial understanding of the data.

2. Data Cleaning

The dataset was checked for missing values and confirmed to be complete. Date columns were converted into proper datetime format to enable time-based analysis. No imputation or removal of data was required.

3. Feature Engineering

New features were created to enhance analysis. Order Month and Order Year were extracted from the Order Date column to support time-based trends. Additionally, a Sales per Unit metric was created to analyze product-level efficiency.

4. Aggregation Analysis

GroupBy operations were used to analyze total sales by category, profit by region, and identify top-performing customers. Monthly sales trends were also examined to understand performance over time.

5. Pivot Tables

Pivot tables were created to compare sales across categories and regions, analyze segment performance over time, and evaluate profit distribution across sub-categories. These summaries helped structure the data for deeper insights.

6. Data Visualization

Several visualizations were created using Pandas plotting functions. These include a line chart for sales trends over time, bar charts for sales by category and profit by region, and a pie chart showing customer segment distribution.

📊 Key Insights

The analysis revealed that the Technology category is the most profitable, while the Central region shows the lowest profit performance. Sales and profit are positively related but influenced by discounts. Additionally, sales demonstrate seasonal patterns across different months.

💡 Business Recommendations

Based on the findings, improving profitability in underperforming regions is recommended. The business should also focus on high-margin product categories such as Technology and optimize discount strategies to maintain profit margins. Seasonal trends can be leveraged for better planning and marketing strategies.

🚀 How to Run This Project

To run this project locally, install the required libraries and open the Jupyter Notebook.

pip install pandas matplotlib

Then:

Open Jupyter Notebook
Load the dataset
Run the notebook cells sequentially
👤 Author
GitHub: https://github.com/mekhlua
Project Type: Exploratory Data Analysis (EDA) Practice
