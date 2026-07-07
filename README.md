# End-to-End E-commerce Analytics Platform

## Project Overview

This project demonstrates the complete development of an end-to-end e-commerce analytics platform using Python, SQLite, and Power BI. The objective is to transform raw sales data into meaningful business insights through data cleaning, database management, analytical processing, interactive dashboards, and automated reporting.

The project follows a complete analytics workflow beginning with data preprocessing in Python, storing the cleaned data in a SQLite database, performing business analysis using SQL queries, creating interactive Power BI dashboards, and generating automated analytical reports.

---

## Objectives

The project aims to:

- Clean and preprocess the raw e-commerce sales dataset.
- Store the processed data in a SQLite database.
- Perform SQL-based business analysis.
- Analyse sales, profit, discount, quantity, customer segments, products, and regional performance.
- Build interactive Power BI dashboards for business decision-making.
- Generate an automated analytical report using Python.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- SQLite
- SQL
- Power BI

---

## Project Workflow

The project consists of the following stages:

1. Data loading and exploration
2. Data cleaning and preprocessing
3. SQLite database creation
4. SQL business analysis
5. Exploratory data analysis using Python
6. Business KPI calculation
7. Segment performance analysis
8. Power BI dashboard development
9. Automated report generation

---

## Dataset

The project uses the Sample Superstore e-commerce sales dataset.

The cleaned dataset used for analysis is included in this repository.

---

## Repository Structure

```
End-to-End-E-commerce-Analytics-Platform
│
├── Cleaned_SampleSuperstore.xlsx
├── SampleSuperstore.xlsx
├── Ecommerce_Analytics.db
├── Sales Analysis.ipynb
├── Sales Analysis.pbix
└── README.md
```

---

## Project Components

### Python

The Python notebook performs:

- Data loading
- Data exploration
- Data cleaning
- Duplicate removal
- Data validation
- Exploratory data analysis
- SQLite database creation
- SQL query execution
- KPI calculation
- Business analysis
- Automated report generation

---

### SQLite Database

The SQLite database stores the cleaned dataset and supports SQL-based business analysis, including:

- Total sales
- Total profit
- Total quantity
- Average sales
- Average profit
- Average discount
- Sales by category
- Profit by category
- Sales by region
- Profit by region
- Sales by segment
- Top-performing states
- Top-performing cities

---

### Power BI Dashboard

The Power BI report contains multiple interactive dashboard pages for analysing:

- Executive business performance
- Product performance
- Regional sales performance
- Business insights

The dashboard includes KPI cards, bar charts, treemaps, maps, scatter charts, tables, matrices, gauges, and slicers for interactive filtering.

---

## How to Run the Project

### Python Notebook

1. Download or clone this repository.
2. Open the `Sales Analysis.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries if they are not already available.
4. Execute the notebook from the first cell to the last cell.
5. The notebook will clean the dataset, perform analysis, create the SQLite database, and generate the required outputs.

---

### SQLite Database

1. Open `Ecommerce_Analytics.db` using any SQLite client such as DB Browser for SQLite.
2. Explore the `sales_data` table.
3. Execute SQL queries for business analysis if required.

---

### Power BI Dashboard

1. Open `Sales Analysis.pbix` using Microsoft Power BI Desktop.
2. If prompted, reconnect the dataset to the local `Cleaned_SampleSuperstore.csv` file.
3. Refresh the data.
4. Explore the interactive dashboard pages using the available slicers and filters.

---

## Project Outcomes

The project demonstrates:

- End-to-end data analytics workflow
- Data preprocessing using Python
- SQL database development using SQLite
- Business analysis through SQL queries
- KPI calculation and performance evaluation
- Interactive dashboard development using Power BI
- Automated reporting using Python

---

## Author

Mohammed Mubashir
