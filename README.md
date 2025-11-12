🧩 Customer Shopping Behavior Analysis — Data Analytics Project
📘 Overview

This project explores customer shopping patterns using transactional data to identify key trends that influence purchasing behavior, customer loyalty, and revenue growth.
The analysis integrates Python, MySQL, and Power BI to deliver actionable insights through data-driven storytelling and visualization.
The project concludes with a PDF report and Gamma presentation summarizing key findings and recommendations.

📊 Dataset

Records: 3,900

Features: 18

Key Columns:

Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Product, Category, Purchase Amount, Season, Size, Color

Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency, Rating, Shipping Type

Missing Data: 37 missing values in Review Rating column (handled during cleaning)

🧰 Tools & Technologies
Tool	Purpose
Python (pandas, numpy, matplotlib)	Data loading, cleaning, and EDA
MySQL 	Running SQL queries and business analysis
Power BI	Dashboard visualization and storytelling
Gamma App	Final presentation design
GitHub	Version control and documentation
🔍 Project Steps
1. Data Loading & Preparation (Python)

Imported the dataset using pandas

Inspected structure with .info() and .describe()

Handled missing values using median imputation per product category

Standardized column names and created derived features (e.g., age_group, purchase_frequency_days)

2. Exploratory Data Analysis (EDA)

Visualized spending trends, product preferences, and demographic patterns

Identified correlations between discounts, reviews, and repeat purchases

3. Data Storage & SQL Analysis

Loaded cleaned data into MySQL

Executed SQL queries to answer key business questions:

Revenue by gender, age group, and category

High-spending customers using discounts

Subscriber vs. non-subscriber performance

Shipping method comparison

Product rankings by ratings and purchase count

4. Visualization (Power BI)

Built an interactive dashboard featuring:

Sales overview by demographics

Customer segmentation (New, Returning, Loyal)

Top products and categories

Discount and subscription insights

Key performance metrics (Revenue, Avg. Spend, Rating)

5. Reporting & Presentation

Summarized key findings and recommendations in a professional report (PDF)

Created a Gamma presentation to visually communicate business insights to stakeholders

📈 Results & Insights

Identified high-value customer segments driving the majority of sales

Found that discount strategies significantly influenced repeat purchases

Subscribers spent more per transaction compared to non-subscribers

Express shipping correlated with higher spending behavior

Recommendations focused on improving loyalty programs, targeted marketing, and product positioning
