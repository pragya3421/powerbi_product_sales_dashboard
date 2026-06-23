# Product Sales Dashboard

# What I Built:
Sales analysis dashboard with customer and order data
KPI cards showing: Total Orders, Customer Count, Total Sales
Charts: Product sales bar chart, Category breakdown pie chart
Interactive filters by country, product category, and date range
Line chart showing sales trend over time

# Skills Applied:
Data connection (CSV files)
Table relationships
Basic visualizations
Slicer/filter creation

# Data Used: 
100 orders from 12 customers across multiple products

# DAX Functions
COALESCE() - Replace null values with alternatives
SUM() - Aggregate sales values
COUNT() - Count records
COUNT(DISTINCT) - Count unique values

# Data Relationships
1:* (One-to-Many) relationship between customers and orders
Establish relationships via drag-and-drop

# Visualizations
Bar charts - Compare values across categories
Line charts - Show trends over time
Cards - Display single KPI values
Slicers - Enable user interactivity
Pie/Donut charts - Show part-to-whole relationships

# Challenges Faced
Decimal Precision Issue
  Problem: 119.7 was rounding to 120
  Root Cause: Data type set to "Whole Number" instead of "Decimal Number"
  Solution: Changed Format from "General" to "Decimal Number" with proper decimal places

Null Values in Data
  Problem: Missing scores affected calculations
  Solution: Used COALESCE() function to replace nulls with 0

# Interactive Filters
Successfully created slicers for country, product category, and date ranges

# Lessons Learned
  Always backup your PBIX file - Don't work on the original
  Review data types carefully - Decimal vs Whole Number matters
  Use meaningful column names - Makes calculations easier
  Test before publishing - Preview in Service before sharing
  Keep dashboards simple - Too many visuals = confusing
  Use slicers wisely - Add interactivity but avoid clutter
