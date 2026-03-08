# Sales-Data-Analysis-


## Project Overview
This project performs data analysis on sales data using Python. The goal is to analyze product sales, identify trends, and visualize the results using charts. The project demonstrates a complete data analysis workflow including data loading, cleaning, analysis, and visualization.

## Objectives
- Analyze sales performance by product and category
- Identify revenue trends over time
- Visualize the data using different chart types
- Generate insights from the analysis

## Tools and Technologies
- Python
- Pandas
- Matplotlib

Documentation  
Pandas: https://pandas.pydata.org/docs/  
Matplotlib: https://matplotlib.org/stable/tutorials/index.html

## Project Structure
sales_analysis_project  
│  
├── data  
│   └── sales_data.csv  
│  
├── visualizations  
│   ├── category_sales_bar_chart.png  
│   ├── product_sales_pie_chart.png  
│   └── monthly_sales_line_chart.png  
│  
├── report  
│   └── report.md  
│  
├── main.py  
├── requirements.txt  
└── README.md  

## Dataset
The dataset contains sales transaction information.

Columns used in the dataset:
- Date
- Product
- Category
- Revenue
- Quantity

## Installation
Install the required libraries before running the project.

pip install -r requirements.txt

## How to Run the Project
Run the Python script to perform the analysis and generate visualizations.

python main.py

## Output
The program will generate the following outputs:

Bar Chart: Sales by Category  
Pie Chart: Revenue Distribution by Product  
Line Chart: Monthly Sales Trend  

All visualizations will be saved in the visualizations folder.

## Data Analysis Process
1. Load the dataset using Pandas  
2. Clean missing or invalid data  
3. Perform basic statistical analysis  
4. Group and summarize sales data  
5. Create visualizations using Matplotlib  
6. Save charts and generate insights  

## Key Insights
- Electronics category generates the highest revenue  
- Some products contribute significantly more revenue than others  
- Monthly trends show changes in sales performance over time  

## Requirements
pandas  
matplotlib  

## Conclusion
This project demonstrates how Python can be used for basic data analysis and visualization. Using Pandas and Matplotlib makes it possible to analyze datasets efficiently and present insights through charts.

