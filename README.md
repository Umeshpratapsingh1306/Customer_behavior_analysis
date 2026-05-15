## Customer Behavior Analysis Project
# Overview

This project focuses on analyzing customer purchasing behavior using Python, SQL, and Power BI. The workflow includes data loading, exploratory data analysis (EDA), data cleaning, SQL-based business analysis, and interactive dashboard creation. The objective of the project is to generate meaningful business insights from customer transaction data and present them through a professional dashboard and report.

# Dataset

The dataset contains customer-related information such as:

- Customer ID
- Age
- Gender
- Product Category
- Purchase Amount
- Payment Method
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Review Ratings
- Purchase Frequency
- Location and Season

The dataset was cleaned and transformed before analysis to ensure data quality and consistency.

Tools & Technologies Used
Tool	Purpose
Python	Data analysis and preprocessing
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical charts
MySQL	SQL querying and analysis
MySQL Workbench	Database management
Microsoft Power BI	Dashboard and reporting
Jupyter Notebook	Project development environment
# Project Workflow
1. Data Loading
Imported dataset into Python using Pandas
Connected Python with MySQL database using SQLAlchemy and PyMySQL
Uploaded cleaned dataset into MySQL Server
2. Exploratory Data Analysis (EDA)

Performed detailed EDA to understand:

Customer demographics
Purchase trends
Revenue distribution
Product category performance
Customer subscription behavior
Seasonal sales patterns

Created multiple visualizations to identify patterns and trends.

3. Data Cleaning

Data preprocessing steps included:

Handling missing values
Removing duplicates
Standardizing column names
Correcting data types
Feature engineering for customer segmentation
4. SQL Analysis

# Executed SQL queries in MySQL to generate business insights such as:

- Total revenue
- Average purchase amount
- =Discount usage rate
- Customer segmentation
- Category-wise sales
- Subscription analysis
- Purchase frequency analysis

# Used:

Aggregate functions
CASE statements
CTEs
GROUP BY
Power BI Dashboard

# Built an interactive Power BI dashboard to visualize key business metrics.

Dashboard Features
KPI Cards
Customer segmentation analysis
Revenue insights
Category performance
Subscription status distribution
Gender-based analysis
Interactive slicers and filters

# The dashboard enables quick business decision-making through dynamic visualizations.

# Key Insights
Identified top-performing product categories
Analyzed customer purchasing patterns
Evaluated discount effectiveness
Measured customer retention behavior
Observed seasonal trends in purchases
Project Structure
Customer-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard/
├── reports/
├── README.md
# How to Run the Project
1. Clone Repository
git clone <repository_link>
2. Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
3. Run Jupyter Notebook
jupyter notebook
4. Configure MySQL Connection

# Update database credentials in Python:

host = "localhost"
username = "root"
password = "your_password"
database = "customer_behavior"
5. Execute SQL Queries

Run SQL scripts using MySQL Workbench.

6. Open Power BI Dashboard

Open the .pbix file in Microsoft Power BI to explore the dashboard.

# Conclusion

This project demonstrates end-to-end data analytics workflow including:

Data preprocessing
SQL analysis
Business intelligence reporting
Dashboard development

# The project highlights practical skills in Python, SQL, and Power BI for solving real-world business problems and generating actionable insights.
