# 🛒 Retail Superstore Sales Dashboard

A Data Analysis project built as part of my BSc Data Science and Artificial Intelligence coursework. This project combines Python for data cleaning with Power BI for building an interactive sales dashboard.

## 📥 View the Dashboard

Since Power BI's "Publish to Web" feature requires an organizational account, this dashboard cannot be embedded as a live public link. Instead, you can view it in two ways:

1. **PDF Preview:** [View Dashboard PDF](Retail_Sales_Dashboard.pdf) — a static preview of the dashboard, viewable directly on GitHub.
2. **Interactive File:** [Download the Power BI file (.pbix)](https://iitgoffice-my.sharepoint.com/:u:/g/personal/vinay_singh_op_iitg_ac_in/IQDZ-UYsSV4nQoqj8sULtwDwAeEh-sn5E421Jf_hznjUU-s?e=EyEhyX) — download this file, open it in **Power BI Desktop**, and log in with your own Microsoft account to explore the dashboard with full interactivity (filters, slicers, drill-downs, etc.).

## 📌 Project Overview

This project analyzes the **Superstore Sales Dataset** to uncover business insights such as:
- Which product categories and sub-categories generate the most sales
- Which regions and states are the most profitable
- How sales trend across different months
- Overall performance through key metrics like Total Sales, Profit, and Quantity Sold

## 🛠️ Tech Stack

- **Python (Pandas)** – data cleaning and preprocessing
- **Power BI** – interactive dashboard and data visualization

## 📂 Files in this Repository

| File | Description |
|---|---|
| `data_cleaning.ipynb` | Jupyter Notebook that cleans and prepares the raw sales data |
| `cleaned_superstore.csv` | Cleaned dataset (output of the Python cleaning step) |
| `Retail_Sales_Dashboard.pbix` | Power BI dashboard file |
| `Retail_Sales_Dashboard.pdf` | Static PDF export of the dashboard |
| Raw dataset file | Original Superstore dataset before cleaning |

## 🚀 How to Run This Project

1. Clone this repository
   ```
   git clone https://github.com/vinay-data-code/retail-sales-dashboard.git
   cd retail-sales-dashboard
   ```

2. To re-run the data cleaning step:
   - Install the required library: `pip install pandas`
   - Open `data_cleaning.ipynb` in VS Code or Jupyter and run all cells


## 🧹 Data Cleaning Steps (Python)

- Removed duplicate rows from the raw dataset
- Standardized column names by removing extra spaces
- Converted `Order_Date` and `Ship_Date` columns into proper datetime format
- Created new columns: `Order_Year`, `Order_Month`, `Shipping_Days`, and `Profit_Margin_%`
- Exported the cleaned dataset as a CSV file for use in Power BI

## 📊 Dashboard Features

- KPI cards showing Total Sales, Total Profit, and Total Quantity Sold
- Bar chart showing Sales by Category
- Pie chart showing Profit by Region
- Line chart showing Monthly Sales Trend
- Bar chart showing Top Sub-Categories by Sales
- Map visual showing State-wise Sales
- Interactive Region slicer to filter the entire dashboard

## 📁 Dataset Source

[Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Download link

   - Download `Retail_Sales_Dashboard.pbix` from this repository, or use the [SharePoint link](https://iitgoffice-my.sharepoint.com/:u:/g/personal/vinay_singh_op_iitg_ac_in/IQDZ-UYsSV4nQoqj8sULtwDwAeEh-sn5E421Jf_hznjUU-s?e=EyEhyX) above
   - Open it in Power BI Desktop (log in with your own Microsoft account if prompted)