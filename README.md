# -Retail-Sales-Insights-Dashboard

# Retail Sales Insights Dashboard

This repository contains resources and tools for analyzing retail sales data, including a Power BI dashboard, data files, and a Jupyter Notebook for sales forecasting and market basket analysis.

## Repository Contents

- **Retail Sales Insights Dashboard.pbit**: A Power BI template file for visualizing retail sales data.
- **online_retail_II.csv**: Raw dataset containing transactional data for retail sales.
- **cleaned_online_retail_data.csv**: Processed version of the raw dataset, cleaned and prepared for analysis.
- **Sales_Forecasting_&_Market_Basket_Analysis.ipynb**: Jupyter Notebook performing sales forecasting and market basket analysis on the retail data.

## Getting Started

To utilize the resources in this repository:

1. **Power BI Dashboard**:
   - Open `Retail Sales Insights Dashboard.pbit` in Power BI Desktop.
   - When prompted, load the `cleaned_online_retail_data.csv` file to visualize the data.
     ![Screenshot 2025-04-04 201537](https://github.com/user-attachments/assets/c7e633db-d6d0-4654-a48d-23b11cf794df)


2. **Jupyter Notebook**:
   - Ensure you have Python and Jupyter Notebook installed.
   - Open `Sales_Forecasting_&_Market_Basket_Analysis.ipynb` to explore the analyses.
   - The notebook utilizes the `cleaned_online_retail_data.csv` dataset.

## Data Overview

The datasets provided (`online_retail_II.csv` and `cleaned_online_retail_data.csv`) contain transactional records of a retail store, including fields such as:

- **InvoiceNo**: Unique invoice number.
- **StockCode**: Product code.
- **Description**: Product description.
- **Quantity**: Number of units sold.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit.
- **CustomerID**: Unique customer identifier.
- **Country**: Country of the customer.

## Analyses Performed

- **Sales Forecasting**: Predicting future sales trends based on historical data.
- **Market Basket Analysis**: Identifying product purchase patterns and associations.

## Prerequisites

- **Power BI Desktop**: For viewing and interacting with the `.pbit` dashboard.
- **Python Libraries**: Required for the Jupyter Notebook analyses:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## How to Use

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ysaikumar21/-Retail-Sales-Insights-Dashboard.git
Data Preparation:

Use the online_retail_II.csv as the raw data source.

The cleaned_online_retail_data.csv is provided for immediate analysis.

Running Analyses:

Open the Jupyter Notebook to perform forecasting and market basket analysis.

Utilize the Power BI template to visualize sales insights.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

