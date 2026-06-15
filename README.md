# Customer Support Ticket Analysis Dashboard

# Overview

This project focuses on analyzing customer support ticket data using Python, SQL, and Power BI to identify customer issue trends, support performance, ticket resolution efficiency, and SLA-related insights.

The project follows an end-to-end analytics workflow including:

* Data Cleaning
* Data Preprocessing
* Feature Engineering
* SQL Analysis
* Dashboard Development
* Business Insight Generation

# Python Data Cleaning & Preprocessing

The dataset was cleaned and transformed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Steps Performed

* Standardized column names
* Converted date columns into datetime format
* Standardized categorical values
* Removed formatting inconsistencies
* Handled missing values
* Replaced inconsistent ticket status values
* Removed invalid negative resolution delays

## Feature Engineering

Created new analytical columns such as:

* product_category
* resolution_delay_hours
* response_hour
* response_day

## Exploratory Data Analysis

Performed initial visual analysis using:

* Bar plots
* Count plots
* Resolution delay analysis
* Customer satisfaction analysis

## Database Integration

The cleaned dataset was loaded into MySQL using SQLAlchemy and PyMySQL.

# SQL Analysis

SQL queries were written to analyze:

* Ticket status distribution
* Product categories with highest issues
* Most common ticket priorities
* Support channel performance
* Resolution delay analysis
* SLA compliance
* Customer satisfaction trends
* Ticket trends over time
* Product performance analysis

The SQL analysis helped identify operational bottlenecks and customer issue patterns.

# Power BI Dashboard

An interactive dashboard was created in Power BI to visualize operational KPIs and support analytics.

## KPI Cards

* Total Tickets
* Closed Ticket Percentage
* Avg Resolution Delay (hrs)
* Average Customer Rating
* Active Tickets

## Dashboard Visuals

* Tickets by Product Category
* Tickets by Issue Type
* Tickets by Priority Level
* Ticket Status Distribution
* Resolution Time Distribution
* Tickets Resolved by Hour

## Interactive Filters

* Ticket Status
* Ticket Priority
* Ticket Type
* Ticket Channel
* Product Category

# Key Insights

1. Gaming and Camera products generated the highest number of support tickets, likely because hardware products are more prone to physical damage, compatibility issues, and technical failures.

2. Most customer issues were related to:

* Refund requests
* Technical issues

3. Medium-priority tickets were the most common because most customer issues were related to refund requests and common technical problems rather than critical system failures.

4. Only around 32.7% of tickets were fully resolved, indicating a large number of active and pending tickets.

5. Average resolution delay was approximately 8 hours, showing that most customer issues were resolved within 24 hours and support operations generally remained within SLA limits.

6. Most ticket resolutions occurred during evening hours, especially around 7 PM.


# Conclusion

This project demonstrates a complete end-to-end data analytics workflow using Python, SQL, and Power BI.

The analysis helped identify:

* customer issue patterns
* operational inefficiencies
* support performance trends
* ticket resolution behavior
* SLA-related insights
