# E-commerce Sales and Customer Insights

## Project Overview

## Key Objectives
1. Perform data cleaning and preprocessing.
2. Conduct exploratory data analysis to uncover trends and patterns.
3. Create visually appealing and informative visualizations.

## Tools and Libraries
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Data visualization
- **Plotly**: Interactive visualizations

## Repository Structure
```
ecommerce-analysis/
├── data/
│   ├── raw_ecommerce_data.csv          # Raw dataset with inconsistencies
│   ├── cleaned_ecommerce_data.csv      # Cleaned and refined dataset
├── visualizations/
│   ├── top_categories.png              # Bar plot for top categories by revenue
│   ├── sales_trend.png                 # Line plot for sales trends
│   ├── payment_methods_pie.html        # Interactive pie chart for payment methods
├── scripts/
│   ├── ecommerce.py             # Script for data cleaning and analysis and generating visualizations
├── README.md                           # Project overview and instructions
```

## Steps in the Project

### 1. Data Cleaning
- **Handled Missing Values**:
  - Filled missing customer names with "Anonymous".
  - Replaced missing prices with the mean price.
- **Addressed Inconsistencies**:
  - Replaced "Unknown" categories with "Miscellaneous".
  - Ensured proper data types for all columns.

### 3. Exploratory Data Analysis (EDA)
- Analyzed revenue by product category.
- Examined sales trends over time.
- Investigated payment method preferences.

### 4. Data Visualization
- **Bar Plot**: Top categories by revenue.
- **Line Plot**: Sales trends over time.
- **Interactive Pie Chart**: Distribution of payment methods.
