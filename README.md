# Customer-Behaviour-Analysis Data Analytics Project

Overview

This project demonstrates an end-to-end data analytics workflow, starting from raw data and progressing through data cleaning, exploratory analysis, SQL analysis, and interactive dashboard development.

The project focuses on transforming raw data into meaningful insights that can support data-driven decision-making.

Dataset

The project uses a structured dataset containing relevant business/customer records.

The raw dataset is loaded into Python for initial inspection, cleaning, and exploratory data analysis before being used for further SQL analysis and visualization.

Tools & Technologies

* Python — Data loading, cleaning, EDA
* Pandas — Data manipulation and analysis
* NumPy — Numerical operations
* Matplotlib / Seaborn — Data visualization
* SQL — Data querying and analysis
* PostgreSQL / MySQL / SQL Server — Database analysis
* Power BI — Interactive dashboard and visualization
* Jupyter Notebook — Python-based analysis

Project Workflow

1. Data Loading

* Imported the dataset into Python using Pandas.
* Inspected the dataset structure, columns, data types, and dimensions.
* Identified missing values and potential data quality issues.

2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:

* Data distributions
* Trends and patterns
* Relationships between variables
* Outliers
* Missing values
* Key business metrics

Visualizations were created to communicate important findings.

3. Data Cleaning

The dataset was prepared for analysis by:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing categorical values
* Handling inconsistent or invalid data
* Treating relevant outliers

4. SQL Analysis

The cleaned data was loaded into a relational database and analyzed using SQL.

Queries covered concepts such as:

* SELECT, WHERE
* GROUP BY, HAVING
* ORDER BY
* Aggregate functions
* CASE WHEN
* Subqueries
* Joins
* Window functions
* CTEs

The analysis was used to identify meaningful trends and business insights.

5. Power BI Dashboard

The analyzed data was connected to Power BI to build an interactive dashboard.

The dashboard includes:

* KPI cards
* Interactive charts
* Tables
* Filters and slicers
* Trend analysis
* Category-wise analysis
* Key business insights

Dashboard

The Power BI dashboard provides an interactive view of the major findings from the analysis.

Dashboard Preview:

Add your Power BI dashboard screenshot here.

Example:

![Power BI Dashboard](images/dashboard.png)

Key Insights

The project identifies important patterns and trends within the dataset, helping answer questions such as:

* What are the major trends in the data?
* Which categories or segments perform better?
* What factors influence the key metrics?
* Which areas require attention?
* What actionable insights can be derived from the data?

Project Structure

Data-Analytics-Project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── analysis.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt

How to Run

1. Clone the Repository

git clone <repository-url>
cd Data-Analytics-Project

2. Install Python Dependencies

pip install -r requirements.txt

3. Run the Python Analysis

Open the Jupyter Notebook:

jupyter notebook

Run the cells in the notebooks/ directory to perform data loading, EDA, and data cleaning.

4. Run SQL Analysis

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the queries available in:

sql/analysis.sql

5. Open the Power BI Dashboard

Open:

powerbi/dashboard.pbix

in Microsoft Power BI Desktop.

Update the data source/credentials if required and refresh the dataset.

Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* SQL
* Database Management
* Data Visualization
* Power BI
* Dashboard Development
* Business Insight Generation

Conclusion

This project demonstrates an end-to-end approach to solving a data analytics problem — from raw data preparation to SQL analysis and interactive business intelligence dashboards.

The objective is not only to analyze data but also to transform the analysis into clear, actionable insights for decision-making.
