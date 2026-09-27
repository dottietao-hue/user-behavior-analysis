# E-commerce User Behavior Analysis

This project analyzes e-commerce user and order behavior using a dataset of 5,000 transactions. The goal is to uncover patterns in sales performance, customer purchasing behavior, product demand, regional differences, and satisfaction drivers.

## Project Overview

The analysis is organized into two main notebooks:

- `data-exploration.ipynb` — data quality checks, exploratory analysis, and descriptive statistics
- `business_analysis.ipynb` — business-focused analysis including product, customer, geographic, and time-based insights

The dataset used in the project is stored in:

- `raw_data/ecommerce_sales_analytics_5000.csv`

## Dataset Description

Each record represents an order with the following fields:

- `order_id`
- `order_date`
- `customer_id`
- `product_category`
- `region`
- `quantity`
- `unit_price`
- `discount`
- `payment_method`
- `delivery_days`
- `customer_rating`
- `revenue`

This dataset supports analysis of:

- sales and revenue trends
- customer repeat purchase behavior
- category-level performance
- regional performance comparison
- delivery and rating impacts
- discount and pricing patterns

## Business Questions Explored

The project investigates questions such as:

1. Which product categories generate the most revenue?
2. Which customers contribute the highest value?
3. Which regions perform best overall?
4. Are there seasonal or time-based sales trends?
5. Does a higher discount increase revenue?
6. How do customer ratings relate to delivery speed and purchase behavior?

## Key Analysis Areas

### 1. Product Analysis
- revenue by category
- sales volume by category
- average order value by category
- category performance comparison

### 2. Customer Analysis
- high-value customer identification
- repeat purchase patterns
- customer frequency and revenue segmentation
- RFM-style customer value analysis

### 3. Geographic Analysis
- revenue and order volume by region
- regional differences in delivery time
- customer satisfaction by region

### 4. Time-Series Analysis
- monthly and yearly revenue trends
- growth patterns over time
- seasonal buying behavior

### 5. Discount and Satisfaction Analysis
- impact of discount on revenue and conversion
- relationship between customer rating and delivery performance
- customer experience quality evaluation

## Repository Structure

```text
.
├── README.md
├── business_analysis.ipynb
├── data-exploration.ipynb
├── raw_data/
│   └── ecommerce_sales_analytics_5000.csv
└── .gitignore
```

## Tools and Libraries

The project uses Python with common data analysis libraries, including:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter notebook

## Getting Started

1. Open the notebooks in Jupyter or VS Code.
2. Ensure the required Python libraries are installed.
3. Run the dataset-loading cells to import the CSV file.
4. Follow the analysis steps in order from exploration to business analysis.

Example setup:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Notes

This project is intended for business intelligence and exploratory data analysis. The insights are useful for product strategy, customer retention planning, and regional marketing prioritization.

## Potential Business Insights

From the analysis, the project is designed to help answer which areas of the business are strongest and where improvements may be needed, including:

- top revenue-driving categories
- most valuable customer segments
- region-specific growth opportunities
- operational bottlenecks such as delivery speed
- pricing and discount optimization opportunities

