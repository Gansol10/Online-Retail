Overview

This project aims to analyze customer purchasing behavior using the Online Retail dataset from the UCI Machine Learning Repository. 

Objectives
- Identifying the most purchased items.
- Determining which countries contribute the most to sales.
- Analyzing whether lower-priced products are more popular.
- Analyzing sales trends over time to identify seasonal patterns and fluctuations.
- Providing insights for market segmentation and business strategy.

Tools & Libraries Used
Pandas: Data manipulation and analysis.
NumPy: Numerical computations.
SciPy (stats, norm): Statistical analysis.
Matplotlib & Seaborn: Data visualization.
Feature-engine (Winsorizer): Outlier handling.

Workflow
Data Preprocessing:
- Loaded the dataset (data_set.csv).
- Renamed columns for better readability.
- Identified and handled missing values.
- Checked for duplicate entries.

Exploratory Data Analysis (EDA):
- Determined the most frequently purchased item using mode().
- Listed the top 5 most bought products.
- Analyzed sales distribution across different countries.

Sales Trend Analysis:
- Aggregated sales data over time to identify patterns.
- Visualized sales trends using line charts.
- Examined monthly and seasonal variations in sales.

Statistical Analysis & Insights:
- Used statistical methods to understand pricing trends.
- Applied outlier handling techniques to clean the dataset.

Results & Insights
- Top-Selling Products: The most frequently bought items were decorative and home-related products.
- Sales by Country: UK had the highest number of purchases, followed by other European countries.
- Price Preference: Customers tend to buy low-to-mid price range products rather than premium-priced ones.

Sales Trend Analysis:
- Sales peaked in November, likely due to major shopping events such as Black Friday and Cyber Monday, which encouraged heavy discounting and bulk purchases.
- Sales declined in December after the peak, as many customers had already completed their holiday shopping in November. However, there was still demand in early December due to Christmas preparation.
- This seasonal trend highlights the importance of inventory stocking and strategic promotions to maximize revenue.

Business Implications
- Retailers should prepare inventory and marketing campaigns for November sales events to capitalize on peak demand.
- December sales strategies should focus on last-minute shoppers and post-holiday clearance promotions to maintain momentum.
- Understanding regional demand differences can help tailor product distribution strategies.
