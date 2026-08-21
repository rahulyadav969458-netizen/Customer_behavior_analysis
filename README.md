# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, from loading and cleaning raw data to generating insights and presenting them through an interactive Power BI dashboard.

The project includes:

* Data loading and exploration using Python
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* SQL analysis using PostgreSQL / MySQL / SQL Server
* Interactive Power BI dashboard
* Analytical report
* Project presentation created using Gamma

---

## Dataset

The project uses a structured dataset containing business-related records for analysis.

Typical steps performed on the dataset:

* Understanding columns and data types
* Checking missing values
* Removing duplicates
* Handling inconsistent data
* Detecting and treating outliers
* Creating useful derived columns
* Preparing clean data for SQL and Power BI

**Dataset File:** `dataset.csv`

---

## Tools & Technologies

| Tool                                | Purpose                      |
| ----------------------------------- | ---------------------------- |
| **Python**                          | Data loading, cleaning & EDA |
| **Pandas**                          | Data manipulation            |
| **NumPy**                           | Numerical operations         |
| **Matplotlib / Seaborn**            | Data visualization           |
| **PostgreSQL / MySQL / SQL Server** | SQL analysis                 |
| **Power BI**                        | Interactive dashboard        |
| **Gamma**                           | Project presentation         |
| **Excel / CSV**                     | Data storage & preparation   |

---

## Project Steps

### 1. Load Dataset

The dataset is loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

### 2. Exploratory Data Analysis

EDA is performed to understand the structure and patterns in the data.

Key activities:

* `head()` and `tail()`
* `info()`
* `describe()`
* Missing-value analysis
* Duplicate-value analysis
* Distribution analysis
* Correlation analysis
* Visualization of important variables

### 3. Data Cleaning

The raw data is cleaned before analysis.

Major cleaning activities include:

* Handling missing values
* Removing duplicates
* Correcting data types
* Standardizing categorical values
* Handling outliers
* Creating calculated columns

### 4. SQL Analysis

The cleaned dataset is imported into a relational database.

SQL queries are used to answer business questions such as:

* Total sales/revenue
* Average transaction value
* Top-performing categories
* Customer or product performance
* Monthly/yearly trends
* Highest and lowest performing segments
* Group-wise comparisons

SQL concepts used include:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `JOIN`
* Subqueries
* Aggregate functions
* Window functions

### 5. Power BI Dashboard

The cleaned data is connected to Power BI to create an interactive dashboard.

The dashboard includes:

* KPI cards
* Charts and graphs
* Category-wise analysis
* Trend analysis
* Filters and slicers
* Interactive visualizations
* Business performance indicators

---

## Dashboard

The Power BI dashboard provides a quick overview of the most important business KPIs and trends.

**Key dashboard areas:**

* Overall Performance
* Sales/Revenue Analysis
* Category Analysis
* Customer Analysis
* Time-Based Trends
* Top & Bottom Performers

> Add your Power BI dashboard screenshot here.

`![Power BI Dashboard](images/dashboard.png)`

---

## Results & Insights

The analysis helps identify important patterns and business insights from the dataset.

### Key Findings

* Identified major performance trends.
* Found the highest and lowest performing categories.
* Analyzed customer/product-level performance.
* Identified important trends over time.
* Used SQL to answer business-related questions.
* Created an interactive dashboard for easier decision-making.

The final dashboard converts raw data into **clear and actionable business insights**.

---

## Project Report

A detailed project report was created covering:

* Business problem
* Dataset description
* Data cleaning process
* EDA
* SQL analysis
* Power BI dashboard
* Key findings
* Business recommendations

---

## PPT Presentation

A project presentation was created using **Gamma** to present the complete analytics workflow and major findings in a professional format.

---

## Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   └── dataset.csv
│
├── python/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## How to Run

### Python

1. Clone or download the project.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the analysis notebook step by step.

### SQL

1. Create a database in PostgreSQL, MySQL, or SQL Server.
2. Import the cleaned dataset.
3. Open `analysis_queries.sql`.
4. Execute the SQL queries.

### Power BI

1. Open the `.pbix` file in Power BI Desktop.
2. If required, update the data source.
3. Refresh the dataset.
4. Explore the interactive dashboard.

---

## Key Skills Demonstrated

* Python for Data Analytics
* Pandas & NumPy
* Exploratory Data Analysis
* Data Cleaning
* SQL
* PostgreSQL / MySQL / SQL Server
* Data Visualization
* Power BI
* Business Intelligence
* Data Storytelling
* Report & Presentation Creation

---

## Conclusion

This project demonstrates a complete **end-to-end data analytics workflow**, transforming raw data into meaningful insights through **Python, SQL, Power BI, and business reporting**.

It showcases practical skills required for a **Data Analyst / Business Intelligence Analyst** role.

