# Retail Sales Analysis using Python

## Project Overview
This project explores retail sales data using Python to identify sales trends, product category performance, and customer purchasing patterns. The goal is to extract meaningful business insights through Exploratory Data Analysis (EDA).

## Objectives
- Understand and clean the retail sales dataset.
- Calculate key sales metrics.
- Analyze revenue by product category and gender.
- Explore monthly sales trends.
- Visualize findings and identify business insights.

## Tools & Technologies
- **Python**
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization

## Dataset
The dataset contains 1,000 retail transactions with information about transaction dates, customer demographics, product categories, quantities, unit prices, and total amounts.

Dataset: [Retail Sales Dataset — Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

## Project Workflow
1. **Data Loading and Exploration:** Inspected the dataset's structure, columns, data types, and descriptive statistics.
2. **Data Cleaning:** Checked for missing values and duplicate records, and converted the date column to datetime format.
3. **Sales Analysis:** Calculated total revenue, transaction count, units sold, average transaction value, and transaction amount range.
4. **Category and Customer Analysis:** Compared category performance and sales by gender.
5. **Trend Analysis and Visualization:** Examined monthly revenue and created charts to communicate findings.
6. **Insights:** Identified key patterns in sales performance.

## Key Findings
- **Total revenue:** 456,000
- **Total transactions:** 1,000
- **Total units sold:** 2,514
- **Average transaction value:** 456
- **Top revenue-generating category:** Electronics, with 156,905 in revenue.
- **Monthly sales trend:** May recorded the highest revenue (53,150), while September recorded the lowest (23,620).
- **Gender comparison:** Female customers accounted for 232,840 in revenue, compared with 223,160 for male customers.

*Note: Monetary values are reported in the units used by the original dataset.*

## Visualizations
The notebook includes:
- Revenue by product category
- Monthly revenue trends
- Sales comparison by gender
- Age-wise transaction exploration

## How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Place `retail_sales_dataset.csv` in the project directory.
4. Open `retail_sales_analysis.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells in order.

## Conclusion
This project demonstrates the use of Python for data cleaning, exploratory analysis, aggregation, and visualization. It provides a foundation for understanding retail sales performance and communicating data-driven findings.

## Author
Aditya Mungekar

---

*This project was completed as a beginner-level Data Analytics portfolio project.*
