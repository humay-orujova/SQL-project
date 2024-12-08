# SQL-project

### Project Overview

This project involved analyzing customer data from an online marketing campaign to uncover insights into customer behavior, spending patterns, and the effectiveness of promotional campaigns. Using SQL, I performed data cleaning, transformed the data into smaller, more manageable tables, and executed exploratory analyses to answer key business questions.

### Data source

[Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis): This dataset contains details on customer demographics, spending behavior, and responses to marketing campaigns. The dataset is used to analyze customer behavior and segmentation in a marketing context.

### Tools

- **SQLite** - Data Cleaning, Transformation, and Analysis

### Data Cleaning/Preparation

Key data preparation steps included:
1. **Data Cleaning:** Removed NULL values from critical columns (e.g., customer ID, income, etc.), ensuring data integrity.
2. **Data Transformation:** Split the original dataset into smaller tables (e.g., People, Products, Promotion, Place) to streamline analysis and optimize query performance. Each table focused on specific aspects of customer data, such as product spending, promotional responses, and purchase behavior.

### Exploratory Data Analysis

The analysis aimed to answer the following key business questions:
- **Demographics:** What is the age distribution of customers?
- **Income Analysis:** What is the average income by education level and marital status?
- **Product Analysis:** Which product categories generate the highest total spending?
- **Channel Preferences:** Which purchase channel (web, store, catalog) is the most popular?
- **Income and Spending Patterns:** How does income level influence customer spending?
- **Promotional Effectiveness:** How do customers in different age groups respond to promotional campaigns?
- **Customer Engagement:** Are there patterns in customer recency and purchases?

### Results/Findings

Key findings from the analysis:
- Middle-aged customers (35–54) and older customers (55 and above) dominate the customer base, with younger customers representing a small minority.
- Higher education correlates with increased income, with PhD holders earning the highest average income, while basic education customers earn the least.
- Wines are the top revenue-generating product category, followed by meat and gold products.
- The store channel is the most popular for purchases, while catalog purchases have the lowest engagement.
- Middle-income customers exhibit the highest average spending across all product categories, significantly outspending low-income groups.
- Older customers tend to engage more consistently across campaigns, while younger customers demonstrate a preference for selective campaigns,
- Less recent customers (more than 60 days since last engagement) contribute the highest total spending, while recent customers (within 30 days) show strong purchasing activity.

### Recommendations

Based on these findings:

- Target less recent customers with re-engagement campaigns to leverage their higher total spending potential.
- Develop loyalty programs or exclusive offers to sustain recent customers' strong purchasing activity and foster long-term relationships.
- Focus inventory and marketing efforts on high-revenue categories such as wine, meat, and gold products.
- Ensure the store channel remains efficient while boosting web and catalog engagement through improved user experiences and targeted marketing.
- Design high-value promotions for middle-income customers, as they demonstrate the highest spending, while providing accessible offers for low-income groups.
