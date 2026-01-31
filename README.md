#Food Delivery Data Analysis Hackathon
--------------------------------------
#Project Overview
------------------
This project involves integrating and analyzing data from three different sources to derive business insights for a food delivery platform. The goal was to combine transactional, user, and restaurant data to understand order trends, membership impacts, and regional performance.

#Datasets Used
----------------
orders.csv: Transactional data containing order IDs, dates, and amounts.

users.json: User master data including locations and membership status (Gold/Regular).

restaurants.sql: Restaurant master data containing cuisine types and ratings.

#Skills Demonstrated
----------------------
Data Integration: Merging multiple file formats (CSV, JSON, SQL) using Python and Pandas.

Data Cleaning: Parsing SQL insert statements and handling date formatting.

Exploratory Data Analysis (EDA): Calculating revenue distribution, average order values, and city-wise performance.

#Key Insights Derived
-----------------------
Membership Impact: Identified that Gold members account for approximately 50% of total orders.

Regional Performance: Chennai emerged as the top revenue-generating city for Gold members.

Cuisine Trends: Mexican cuisine holds the highest average order value, while Chinese cuisine has the highest revenue-to-restaurant density.

Rating Correlation: Higher-rated restaurants (4.6–5.0) significantly drive the majority of platform revenue.

#How to Run
-----------------------
Clone this repository.

Ensure you have pandas installed.

Run the Jupyter Notebook analysis.ipynb to see the step-by-step merging and analysis logic.
