# Sales-data-analysis
Sales data analysis project using Python, SQL and visualization

## Overview
This project performs an in-depth analysis of retail sales data from the Superstore dataset. It explores sales trends, customer behavior, product performance, and regional insights using Python, pandas, SQL, and data visualization techniques. The analysis aims to uncover actionable business insights for optimizing sales strategies, customer targeting, and profitability.

## Dataset
- **Source**: Sample Superstore dataset (commonly used for Tableau training)
- **Description**: Contains transactional data for a fictional superstore, including orders, customers, products, and sales metrics.
- **Key Columns**:
  - Order details: Order ID, Order Date, Ship Date, Ship Mode
  - Customer info: Customer ID, Customer Name, Segment
  - Product info: Product ID, Category, Sub-Category, Product Name
  - Sales metrics: Sales, Quantity, Discount, Profit
  - Geographic: Country, City, State, Postal Code, Region
- **Time Period**: 2014-2017
- **Size**: ~10,000 rows of data

## Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **SQLite**: Database for SQL queries
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive development environment

## Installation and Setup
1. **Prerequisites**:
   - Python 3.7+
   - Jupyter Notebook
   - Required libraries: pandas, matplotlib, sqlite3 (built-in)

2. **Clone/Download the Repository**:
   - Ensure you have the `sales_analysis.ipynb` notebook and `Sample - Superstore.csv` file in the same directory.

3. **Install Dependencies**:
   ```bash
   pip install pandas matplotlib notebook
   ```

4. **Run the Analysis**:
   - Open the Jupyter notebook: `jupyter notebook sales_analysis.ipynb`
   - Execute cells sequentially to reproduce the analysis.

## Project Structure
```
sales-data-analysis/
├── sales_analysis.ipynb          # Main analysis notebook
├── Sample - Superstore.csv       # Raw dataset
├── sales.db                      # SQLite database (generated)
└── README.md                     # This file
```

## Key Analyses and Insights

### 1. Exploratory Data Analysis (EDA)
- Data loading and initial inspection
- Handling missing values and duplicates
- Date parsing and feature engineering (Year, Month)

### 2. Sales Performance Analysis
- **Total Revenue**: Calculated overall sales figures
- **Category Performance**: Technology leads in revenue, followed by Furniture and Office Supplies
- **Regional Analysis**: West region shows highest sales, followed by East and Central
- **Sub-Category Insights**: Top performers include Phones, Chairs, and Storage items

### 3. Customer Behavior Analysis
- **Top Customers**: Identified high-value customers by total spending
- **Repeat Purchase Analysis**: Analyzed customer loyalty and retention patterns
- **Segment Preferences**: Consumer segment prefers Office Supplies, Corporate focuses on Technology
- **Lifetime Value**: Calculated average customer value by region

### 4. Profitability Analysis
- **Unprofitable Customers**: Identified accounts with negative profit margins
- **Discount Impact**: Analyzed how discounting affects sales and profitability
- **Category Profitability**: Technology shows highest profit margins

### 5. Time Series Analysis
- **Monthly Trends**: Sales peak during holiday months (November-December)
- **Year-over-Year Growth**: Identified seasonal patterns

## Visualizations
- Bar charts for category and regional sales
- Pie charts for regional distribution
- Line plots for monthly sales trends
- Scatter plots for discount vs. profit analysis

## Key Business Insights
- **Technology Dominance**: Focus marketing efforts on tech products for maximum revenue and profit
- **Regional Strategy**: Prioritize West region for expansion and inventory allocation
- **Customer Segmentation**: Target high-value customers in Consumer and Corporate segments
- **Discount Optimization**: Review discounting policies as heavy discounts often lead to losses
- **Seasonal Planning**: Prepare for Q4 spikes with increased inventory and staffing

## SQL Queries Used
The project includes several SQL queries for advanced analysis:
- Customer lifetime value calculation
- Segment-wise product preferences
- Profit margin analysis by customer
- Repeat purchase identification

## Contributing
This is a portfolio project. Suggestions for improvements are welcome!

## License
This project uses sample data and is for educational purposes only.
