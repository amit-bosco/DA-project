# Amazon Sales Data Analysis

## Project Overview

This project focuses on analyzing Amazon sales data using Python and Power BI. The workflow involves cleaning raw data, performing aggregations, and building interactive dashboards to extract meaningful insights for category-level performance analysis.

---

## Project Workflow & Methodology

### 1. Data Collection

The analysis begins with the raw dataset **`amazon.csv`**, which contains product and sales-related information across multiple Amazon categories. This dataset serves as the primary data source for the project.

---

### 2. Data Cleaning & Preprocessing (Python)

Data cleaning and preprocessing were performed using **Python** in **Jupyter Notebook (`Untitled7.ipynb`)** with the **Pandas** library.

Key steps included:

* Handling missing and inconsistent values
* Standardizing column names and formats
* Removing duplicate and irrelevant records
* Converting data types for numerical analysis
* Filtering required attributes for analysis

The processed output was saved as **`amazon_cleaned.csv`**.

---

### 3. Data Aggregation & Feature Engineering

Using the cleaned dataset, category-level aggregations were created to optimize analysis and visualization.

Tasks performed:

* Grouping data by product category
* Calculating key metrics such as total sales, average ratings, and product counts
* Creating summarized tables for efficient dashboard performance

The aggregated dataset was exported as **`powerbi_category_summary.csv`**.

---

### 4. Data Modeling & Visualization (Power BI)

The cleaned and aggregated datasets were imported into **Power BI** (**`da.pbix`**).

Within Power BI:

* Data relationships were defined where required
* DAX measures were created for KPIs and performance metrics
* Interactive visuals such as cards, bar charts, tables, and slicers were designed
* Category-wise and comparative insights were visualized

---

### 5. Dashboard Insights

The final Power BI dashboard provides:

* Category-level sales performance analysis
* Key KPIs for business decision-making
* Interactive filtering for deeper exploration of data

---

## Files in the Repository

* `amazon.csv` – Raw dataset
* `amazon_cleaned.csv` – Cleaned and processed dataset
* `powerbi_category_summary.csv` – Aggregated data for Power BI
* `Untitled7.ipynb` – Python notebook for data cleaning and analysis
* `da.pbix` – Power BI dashboard file

---

## Tools & Technologies Used

* **Google colab**
* **Power BI** (DAX, Data Modeling, Visualization)
* **CSV datasets**
---
## Dashboard
Dashboard.png
---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from raw data preprocessing to interactive dashboard creation, enabling data-driven insights and informed decision-making.
