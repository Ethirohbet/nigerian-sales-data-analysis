# Nigerian Sales Data Analysis

Exploratory data analysis of Nigerian sales data using Python, Pandas, Seaborn, and Matplotlib.

## Project Overview

This project analyzes customer demographics, purchasing patterns, regional performance, occupations, and product categories. It demonstrates a practical data-analysis workflow from data cleaning through visualization and interpretation.

## Tools

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

## Analysis Areas

- Gender analysis
- Age-group analysis
- State-level order and sales analysis
- Marital-status and gender analysis
- Occupation analysis
- Product-category analysis
- Product-level order analysis

## Data Cleaning

The original dataset contained 11,251 rows and 15 columns. The analysis:

- Removed two completely empty columns (`Status` and `unnamed1`)
- Removed 12 rows with missing `Amount`
- Converted `Amount` from float to integer

The cleaned working dataset contains **11,239 rows and 13 columns**.

## Key Findings

- Female customers generated the larger share of total sales.
- Customers aged **26–35** generated the highest total sales amount.
- **Kano** recorded the highest order volume and total sales amount among the states analyzed.
- Technology, Healthcare, Aviation, and Banking were among the leading occupation groups by sales.
- **Food** was the leading product category by total sales amount.
- Clothing & Apparel, Electronics & Gadgets, and Footwear & Shoes were also major contributors.

## Repository Structure

```text
nigerian-sales-data-analysis/
├── Nigerian_Sales_Data_Analysis_GitHub.ipynb
├── NigerianSalesData.csv
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook
   ```
4. Make sure `NigerianSalesData.csv` is in the same directory as the notebook.
5. Run the notebook from top to bottom.


## Limitations

The dataset does not contain profit, cost, or transaction-date fields in the analyzed columns. Therefore, the project focuses on sales amount and order patterns rather than profitability or time-series trends.

## Future Improvements

- Profit and margin analysis
- Average order value
- Customer segmentation
- Time-series analysis if dates are available
- Interactive Tableau or Power BI dashboard
- Statistical testing

## Author

**Ethi Robert**

Data Analyst | Python | SQL | Excel | Tableau | Data Visualization
