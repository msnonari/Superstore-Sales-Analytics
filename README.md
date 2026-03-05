# Superstore Sales Analytics

A comprehensive data analysis project examining global superstore sales data across multiple regions, customer segments, and product categories.

## Overview

This project leverages Python and Jupyter Notebook to perform in-depth analysis of a global superstore dataset containing over 51,000 orders. The analysis uncovers key business insights including sales trends, profitability patterns, regional performance, and customer behavior across different markets worldwide.

## Table of Contents

- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Analysis Highlights](#analysis-highlights)
- [Technologies](#technologies)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

✨ **Core Analytics:**

- **Sales Performance Analysis**: Track total sales, monthly trends, and year-over-year growth
- **Profitability Metrics**: Analyze profit margins, loss-making products, and discount impact
- **Customer Segmentation**: Understand behavior patterns across Consumer, Corporate, and Home Office segments
- **Regional Analysis**: Compare performance across Africa, APAC, EMEA, LATAM, and US regions
- **Product Insights**: Identify top-performing and underperforming products and categories
- **Shipping Analysis**: Evaluate shipping costs and delivery time patterns
- **Discount Impact Study**: Assess how discounts affect profitability

📊 **Visualizations:**

- Interactive charts and graphs
- Category-wise sales distribution
- Regional performance heatmaps
- Time-series trend analysis
- Statistical summaries

## Dataset

**Source**: SuperStoreOrders.csv

**Size**: 51,292 orders

**Time Period**: 2011-2014 (and beyond)

**Geographic Coverage**: Global - 100+ countries across all continents

**Key Fields**:
| Field | Description |
|-------|-------------|
| order_id | Unique order identifier |
| order_date | Date order was placed |
| ship_date | Date order was shipped |
| ship_mode | Shipping method (Standard, Second Class, First Class, Same Day) |
| customer_name | Customer name |
| segment | Customer segment (Consumer, Corporate, Home Office) |
| state | State/Province |
| country | Country |
| region | Geographic region |
| category | Product category (Office Supplies, Furniture, Technology) |
| sub_category | Product sub-category |
| product_name | Product name |
| sales | Revenue generated |
| quantity | Units ordered |
| discount | Discount percentage applied |
| profit | Net profit |
| shipping_cost | Shipping cost |
| order_priority | Priority level |

## Installation

### Prerequisites

- Python 3.7 or higher
- pip or conda package manager

### Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/msnonari/superstore-sales-analytics.git
   cd superstore-sales-analytics
   ```

2. **Create a virtual environment** (optional but recommended)

   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Jupyter Notebook setup**
   ```bash
   jupyter notebook
   ```

## Quick Start

1. Open `Superstore Solution.ipynb` in Jupyter Notebook
2. Ensure `SuperStoreOrders.csv` is in the same directory
3. Run all cells to generate analysis and visualizations
4. Explore the interactive outputs and insights

## Project Structure

```
superstore-sales-analytics/
├── README.md                          # This file
├── requirements.txt                   # Python dependencies
├── Superstore Solution.ipynb          # Main analysis notebook
└── SuperStoreOrders.csv               # Dataset (51,292 orders)
```

## Analysis Highlights

The notebook performs comprehensive analysis across multiple dimensions:

### 1. **Sales Overview**

- Total sales revenue
- Sales by category and sub-category
- Monthly and seasonal trends
- Year-wise comparison

### 2. **Profitability Analysis**

- Total and average profit
- Profit margins by category
- Loss-making products identification
- Discount impact on profit

### 3. **Customer Insights**

- Segment-wise performance
- Top customers by sales and profit
- Customer distribution by region
- Segment profitability comparison

### 4. **Regional Performance**

- Sales distribution by region
- Regional profitability patterns
- Market-wise comparison
- Geographic trends

### 5. **Product Analysis**

- Top 10 products by sales/profit
- Category performance matrix
- Sub-category deep dive
- Product profitability analysis

### 6. **Operational Metrics**

- Average shipping time
- Shipping cost analysis
- Order priority distribution
- Cost vs. revenue analysis

## Technologies

- **Python 3.7+**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive analysis environment

## Results

Key findings from the analysis include:

- **High-Impact Insights**:
  - Identification of profitable vs. loss-making product lines
  - Seasonal sales patterns and trends
  - Regional performance disparities
  - Impact of discounts on overall profitability

- **Actionable Recommendations**:
  - Categories and regions to focus on for growth
  - Products to discontinue or optimize
  - Discount strategy optimization
  - Regional market strategies

_Note: Specific metrics and detailed findings are available in the Jupyter Notebook output._

## Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes and add comments/documentation
4. Commit your changes (`git commit -m 'Add improvement'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

For major changes, please open an issue first to discuss proposed modifications.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or feedback about this analysis, please open an issue on GitHub.

---

**Last Updated**: March 2026

**Status**: Active Development

**Data Updated**: As of the latest order records in the dataset
