# Sales Dashboard — Python Learning Project

A hands-on data analysis project using the Superstore dataset to practice core Python data skills: loading and cleaning data, exploratory analysis, and building visualizations.

## What I Learned

- Loading CSV data with pandas and handling encoding issues (`latin1`)
- Parsing and engineering date features (`Year`, `Month`) from datetime columns
- Creating derived metrics like `Profit Margin` to go beyond raw numbers
- Grouping and aggregating data to find patterns by region, category, and sub-category
- Building bar charts with matplotlib and formatting them properly
- Exporting a cleaned dataset for use in other tools (e.g. Power BI)

## Key Findings

- **Tables** is a loss-making sub-category — even at low discounts, profit goes negative due to high costs and shipping
- **Furniture** has strong sales volume but thin margins; discounting it heavily pushes orders into a loss
- **Fort Lauderdale** is a real-world example of high sales not equalling profit — bulk orders with heavy discounts
- The **West region** leads in total sales

## Tools Used

- Python 3
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Dataset

Superstore Sales dataset — a commonly used retail dataset covering orders, customers, products, and financials across US regions (2014–2017).

## How to Run

1. Clone the repo
2. Install dependencies:
   ```
   pip install pandas matplotlib seaborn
   ```
3. Open `sales_dashboard.ipynb` in Jupyter and run all cells
