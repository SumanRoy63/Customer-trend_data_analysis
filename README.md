Customer Shopping Behavior Analysis:-

An end-to-end Customer Shopping Behavior Analysis project using Python, SQL, and Power BI to uncover customer spending patterns, product preferences, discount behavior, subscription trends, and customer segments.

Project Overview :-

A retail company wants to better understand its customers' shopping behavior to improve sales, customer engagement, satisfaction, and long-term loyalty.

This project analyzes 3,900 customer purchase records across 18 attributes and follows a complete analytics workflow:

Raw Data → Python Data Cleaning & Feature Engineering → SQL Business Analysis → Power BI Dashboard → Business Recommendations

Business Objectives :-

The analysis focuses on questions such as:

How does revenue differ across customer demographics?

Which customers use discounts but still spend above average?

Which products receive the highest average ratings?

Does shipping type relate to purchase value?

How do subscribers compare with non-subscribers?

Which products have the highest proportion of discounted purchases?

How can customers be segmented based on purchase history?

What are the most purchased products within each category?

Data Preparation — Python :-

The dataset was cleaned and transformed using Pandas.

Key steps

Loaded and explored the dataset using pandas.

Inspected data types, summary statistics, and missing values.

Imputed missing Review Rating values using the median rating within each product category.

Standardized column names to snake_case.

Created an age_group feature using quartile-based age segmentation.

Converted purchase-frequency categories into a numerical purchase_frequency_days feature.

Checked the relationship between discount_applied and promo_code_used.

Removed the redundant promo_code_used field after the consistency check.

Loaded the cleaned dataset into a relational database for SQL analysis.

SQL Analysis :-

The cleaned data was analyzed using SQL to answer 10 business questions involving:

Revenue by gender

High-spending customers using discounts

Top-rated products

Shipping type and average purchase amount

Subscriber vs. non-subscriber spending

Products with the highest discount rates

New, Returning, and Loyal customer segmentation

Top products within each category

Repeat buyers and subscription status

Revenue contribution by age group

Power BI Dashboard :-

An interactive Power BI dashboard was created to communicate the analysis to business stakeholders.

The dashboard focuses on:

Revenue and purchase KPIs

Customer demographics

Product performance

Customer segmentation

Subscription behavior

Discount usage

Shipping preferences

Purchase trends

Business recommendations

Are repeat buyers more likely to subscribe?

Which age groups contribute the most revenue?
