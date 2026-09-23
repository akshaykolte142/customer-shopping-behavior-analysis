# Customer Behavior Analysis

This project analyzes customer shopping data to understand purchasing patterns, customer characteristics, product categories, and sales performance.

I used **Python, SQL, PostgreSQL, and Power BI** to clean the data, perform analysis, and create an interactive dashboard.

## Project Objective

The main objective of this project is to understand customer shopping behavior and answer business-related questions such as:

* Which customer groups make more purchases?
* Which product categories perform better?
* How does customer behavior differ by age and gender?
* What is the relationship between discounts and purchases?
* How do subscribed and non-subscribed customers differ?
* Which shopping channels are used more frequently?

## Tools Used

* **Python** – Data cleaning and exploratory data analysis
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **PostgreSQL** – Data storage and SQL analysis
* **SQL** – Business queries and analysis
* **Power BI** – Dashboard and visualization
* **Jupyter Notebook** – Python analysis
* **GitHub** – Project management and version control

## Project Steps

### 1. Data Cleaning

* Loaded the customer shopping dataset into Python.
* Checked the dataset structure and data types.
* Checked for missing and duplicate values.
* Cleaned and prepared the data for analysis.

### 2. Exploratory Data Analysis

Analyzed customer data based on:

* Age
* Gender
* Location
* Product category
* Purchase amount
* Purchase frequency
* Discounts
* Subscription status
* Shopping channel
* Review ratings
* Previous purchases

Created charts using Matplotlib and Seaborn to understand the data.

### 3. SQL Analysis

Used PostgreSQL and SQL to answer business questions related to:

* Customer purchases
* Revenue
* Product categories
* Customer segments
* Subscription status
* Discounts
* Customer demographics
* Shopping behavior

### 4. Power BI Dashboard

Created an interactive Power BI dashboard to present the analysis.

The dashboard includes:

* Total customers
* Purchase and sales metrics
* Category analysis
* Customer demographics
* Subscription analysis
* Shopping channel analysis
* Customer behavior
* Interactive filters and slicers

## Dashboard Preview

![Customer Behavior Dashboard](customer%20behavior%20analysis%20dashboard.jpg)

## Project Files

```text
Customer Behavior Analysis/
│
├── Customer_Shoping_Behavior_Analysis.ipynb
│   └── Python data cleaning and analysis
│
├── Customer behavior business Analysis.sql
│   └── SQL queries
│
├── customer_shopping_behavior.csv
│   └── Dataset
│
├── customer behavior dashboard.pbix
│   └── Power BI dashboard
│
├── customer behavior dashboard.pdf
│   └── Dashboard PDF
│
├── customer behavior analysis dashboard.jpg
│   └── Dashboard image
│
├── Customer Behavior Analysis Report.pdf
│   └── Project report
│
├── Customer_Behavior_Analysis.pptx
│   └── Project presentation
│
├── Business Problem Document.pdf
│   └── Business problem
│
└── .gitignore
    └── Excludes sensitive files
```

## Skills Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQL
* PostgreSQL
* Power BI
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Business Analysis

## Key Learning

Through this project, I practiced working with a dataset from start to finish, including data cleaning, exploratory analysis, SQL querying, and dashboard creation.

It helped me understand how Python, SQL, and Power BI can be used together for data analysis.

## Security

Database credentials are stored locally using environment variables.

The `.env` file is excluded from GitHub using `.gitignore`.

```text
.env
```

No database passwords or other sensitive credentials are included in this repository.

## Disclaimer

This is a portfolio project created for learning and demonstrating data analytics skills.
