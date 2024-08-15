# Pizza Sales Analysis Project

## Table of Contents
1. [Overview](#overview)
2. [Business Problem](#business-problem)
3. [Work Environment](#work-environment)
4. [Steps Taken](#steps-taken)
5. [Challenges Faced](#challenges-faced)
6. [Key Findings](#key-findings)
7. [Impact](#impact)
8. [Usage](#usage)
9. [Summary](#summary)
10. [Repository Structure](#repository-structure)
11. [Contributing](#contributing)
12. [License](#license)

## Overview
This project involves a comprehensive analysis of pizza sales data using MySQL. The goal was to uncover key insights into sales patterns, customer preferences, and revenue distribution to support data-driven decision-making.

## Business Problem
The business needed to understand and optimize its operations based on sales data. This analysis aimed to identify key sales patterns, top-selling products, peak order times, and revenue contributions to enhance inventory management, improve marketing strategies, and boost overall business performance.

## Work Environment
The analysis was conducted entirely within a MySQL environment. MySQL was used for data extraction, manipulation, and analysis, utilizing complex SQL queries to derive actionable insights from the pizza sales data.

## Steps Taken

### 1. Data Retrieval:
- Extracted data from multiple tables to create a comprehensive dataset for analysis.

### 2. Basic Analysis:
- Calculated the total number of orders (21,350).
- Determined total revenue generated ($817,860.53).
- Identified the highest-priced pizza (Deluxe Supreme).
- Found the most common pizza size ordered (Medium).
- Listed the top 5 most ordered pizza types.

### 3. Intermediate Analysis:
- Joined tables to find the total quantity of each pizza category ordered.
- Analyzed the distribution of orders by hour of the day.
- Grouped orders by date to calculate the average number of pizzas ordered per day.
- Determined the top 3 most ordered pizza types based on revenue.

### 4. Advanced Analysis:
- Calculated the percentage contribution of each pizza type to total revenue.
- Analyzed cumulative revenue generated over time.
- Identified the top 3 most ordered pizza types by revenue within each category.

## Challenges Faced
- **Complex SQL Queries:** Crafting and optimizing SQL queries to join multiple tables and extract meaningful insights was challenging.
- **Data Quality Issues:** Addressing inconsistencies and missing data required careful cleaning and validation.
- **Time Management:** Balancing thorough analysis with time constraints posed a challenge, particularly with large datasets.

## Key Findings
- **Total Orders:** 21,350
- **Total Revenue:** $817,860.53
- **Highest-Priced Pizza:** Deluxe Supreme
- **Most Common Pizza Size:** Medium
- **Top 5 Pizza Types:** Margherita, Pepperoni, Veggie, BBQ Chicken, Hawaiian

## Impact
The analysis provided valuable insights into customer preferences and sales trends, enabling better inventory management and targeted marketing strategies. The findings helped optimize business performance and enhance customer satisfaction.

## Usage
To replicate the analysis:
1. Clone the repository.
   ```bash
   git clone https://github.com/ayushGupta1405/Pizza-Shop-Sales-Analysis-.git
   ```
2. Import the provided SQL scripts into your MySQL database.
3. Run the queries in the `queries.sql` file to generate the analysis results.

## Summary
The Pizza Sales Analysis project successfully leveraged MySQL to analyze over 21,350 pizza orders, delivering critical insights into sales patterns, customer preferences, and revenue distribution. Despite challenges such as complex queries and data quality issues, the project provided actionable business recommendations that enhanced overall performance.


