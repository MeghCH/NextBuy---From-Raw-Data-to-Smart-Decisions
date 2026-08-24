# NextBuy - From Raw Data to Smart Decisions

## Overview

This project is a comprehensive data analysis of an online grocery shopping platform. It explores customer purchasing behavior, product performance, and temporal patterns to derive actionable business insights.

## Project Structure

```
nextbuy-project/
├── datasets-project/
│   └── datasets/
│       ├── orders.csv
│       ├── products.csv
│       ├── aisles.csv
│       ├── departments.csv
│       └── order_products.csv
├── notebook.ipynb
├── requirements.txt
└── README.md
```

## Data Structure

The dataset consists of five CSV files:

- **orders.csv**: Contains order information (order_id, user_id, order_dow, order_hour_of_day, days_since_prior_order)
- **products.csv**: Contains product information (product_id, product_name, aisle_id, department_id)
- **aisles.csv**: Contains aisle information (aisle_id, aisle)
- **departments.csv**: Contains department information (department_id, department)
- **order_products.csv**: Contains product-order relationships (order_id, product_id, add_to_cart_order, reordered)

## Analysis Objectives

The analysis is structured into six main blocks:

1. **Assortment and Performance**: Identify top-selling products and aisle penetration rates
2. **Temporal Behavior**: Analyze ordering patterns by day of week and hour of day
3. **Basket Psychology**: Study basket size, product sequencing, and co-purchase patterns
4. **Loyalty and Repurchase**: Examine repurchase rates and customer loyalty metrics
5. **Machine Learning**: Build predictive models for repurchase behavior
6. **Typical Buyer Profile**: Identify recurring customer and product patterns

## Key Findings

- The top 10 products account for 7.2% of total sales volume, with bananas being the most ordered product
- Fresh fruits and vegetables have the highest penetration rates (55.76% and 44.45% respectively)
- Organic products represent 31.6% of total sales, with significant variation by department
- Customer ordering patterns show distinct temporal behaviors throughout the week

## Requirements

The project requires the following Python packages:

- pandas>=2.0.0
- numpy>=1.24.0
- matplotlib>=3.7.0
- seaborn>=0.12.0
- scikit-learn>=1.3.0
- plotly>=5.15.0
- jupyter>=1.0.0
- ipykernel>=6.0.0

## Usage

1. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open and run the `notebook.ipynb` file to execute the complete analysis

## Business Recommendations

Based on the analysis, key recommendations include:

- Prioritize stocking and visibility of top-selling products
- Highlight fresh produce sections in the user interface
- Optimize inventory management for high-penetration aisles
- Implement targeted marketing strategies for organic products in relevant departments
- Adjust logistics planning based on temporal ordering patterns

## License

This project is for educational purposes as part of the Epitech data analysis curriculum.
