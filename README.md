# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow using Python, SQL, Tableau, and reporting tools. The goal of the project is to analyze a dataset, clean and transform the data, generate insights using exploratory data analysis and SQL queries, and present the findings through an interactive Tableau dashboard, a written report, and a presentation created using Gamma.

This project is designed to showcase practical data analytics skills, including data cleaning, data visualization, SQL analysis, dashboard building, and business reporting.

## Dataset

The project uses a structured dataset containing business-related records such as sales, customers, products, orders, revenue, or other key performance indicators.

The dataset is loaded and analyzed using Python. Initial checks are performed to understand the data structure, identify missing values, detect duplicates, and review data types.

Key dataset tasks include:

* Loading the dataset into Python
* Reviewing rows, columns, and data types
* Checking for missing and duplicate values
* Preparing the dataset for analysis
* Exporting cleaned data for SQL and dashboard use

## Tools Used

* **Python**: Data loading, cleaning, and exploratory data analysis
* **Pandas**: Data manipulation and transformation
* **MySQL**: SQL querying and business analysis
* **Tableau**: Interactive dashboard creation
* **Gamma**: Presentation deck creation
* **Excel / CSV**: Dataset storage and export
* **Jupyter Notebook**: Python analysis workflow

## Project Steps

### 1. Data Loading

The dataset was imported into Python using Pandas. Basic checks were performed to understand the structure of the data.

Tasks performed:

* Imported required Python libraries
* Loaded the dataset into a DataFrame
* Displayed sample records
* Checked dataset shape, columns, and data types

### 2. Exploratory Data Analysis

EDA was performed to understand patterns, trends, and relationships in the data.

Tasks performed:

* Summary statistics
* Missing value analysis
* Duplicate value checks
* Distribution analysis
* Category-wise comparisons
* Trend analysis
* Initial visualizations

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Tasks performed:

* Removed duplicate records
* Handled missing values
* Corrected data types
* Standardized column names
* Created calculated fields where required
* Exported the cleaned dataset

### 4. SQL Analysis Using MySQL

The cleaned dataset was imported into MySQL for structured querying and deeper analysis.

Tasks performed:

* Created database and tables
* Imported cleaned data into MySQL
* Wrote SQL queries to answer business questions
* Used filtering, grouping, sorting, joins, and aggregate functions
* Extracted key metrics and insights

Example SQL analysis areas:

* Total revenue or sales
* Top-performing products or categories
* Customer segmentation
* Monthly or yearly trends
* Region-wise performance
* Profitability or growth analysis

### 5. Tableau Dashboard

An interactive Tableau dashboard was created to present the key findings visually.

The dashboard includes:

* KPI cards
* Trend charts
* Category-wise analysis
* Regional or segment-level breakdowns
* Filters for interactive exploration
* Clear visual storytelling for business users

## Dashboard

The Tableau dashboard summarizes the most important insights from the analysis. It allows users to explore the data interactively and understand performance across different dimensions.

Dashboard features:

* Clean and professional layout
* Interactive filters
* Business-focused KPIs
* Easy-to-read charts
* Insight-driven design

## Results

The analysis helped identify important trends, performance drivers, and areas for improvement.

Key outcomes include:

* Identified top-performing categories, products, or segments
* Analyzed sales, revenue, or performance trends
* Found patterns in customer or regional behavior
* Highlighted opportunities for business improvement
* Created a dashboard and report for decision-making

## Report

A final report was created to summarize the analysis, methodology, insights, and recommendations.

The report includes:

* Project objective
* Dataset summary
* Cleaning process
* EDA findings
* SQL insights
* Dashboard explanation
* Final recommendations

## Presentation

A professional presentation was created using Gamma to communicate the project clearly and visually.

The presentation includes:

* Project overview
* Tools and workflow
* Key analysis steps
* Dashboard screenshots
* Main insights
* Business recommendations

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/data-analytics-project.git
cd data-analytics-project
```

### 2. Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn mysql-connector-python
```

### 3. Run the Python Notebook

Open the Jupyter Notebook and run the analysis step by step.

```bash
jupyter notebook
```

### 4. Import Data into MySQL

Create a MySQL database and import the cleaned dataset.

Example:

```sql
CREATE DATABASE analytics_project;
USE analytics_project;
```

Then import the cleaned CSV file into MySQL and run the SQL queries provided in the project files.

### 5. Open Tableau Dashboard

Open the Tableau workbook file and connect it to the cleaned dataset or MySQL database.

### 6. Review Report and Presentation

Review the final report and Gamma presentation for the project summary, insights, and recommendations.

## Project Files

```text
data-analytics-project/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── tableau_dashboard.twbx
│
├── report/
│   └── final_report.pdf
│
├── presentation/
│   └── gamma_presentation_link.txt
│
└── README.md
```

## Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory data analysis
* SQL querying using MySQL
* Dashboard development in Tableau
* Business insight generation
* Data storytelling
* Report writing and presentation design

## Conclusion

This project presents a complete data analytics workflow from raw data to final business insights. It demonstrates the ability to work with data using Python, analyze it with SQL, visualize it with Tableau, and communicate results through a report and presentation.
