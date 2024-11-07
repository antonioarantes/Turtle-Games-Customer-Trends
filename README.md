Turtle Games Customer Insights Project
This repository contains a data analysis project conducted for Turtle Games, a global game manufacturer and retailer. Turtle Games offers a diverse product range, including books, board games, video games, and toys, and collects extensive customer data to improve sales performance by analyzing trends in customer engagement.

Project Overview
This project aimed to address several key business objectives for Turtle Games:

Customer Engagement with Loyalty Points: Analyze how customers accumulate and interact with loyalty points.
Customer Segmentation: Identify data-driven customer segments to inform targeted marketing strategies.
Sentiment Analysis: Examine customer review sentiment to guide marketing approaches and business improvements.
The analysis was based on a single dataset (turtle_reviews), containing customer reviews, loyalty data, and demographic information, which I cleaned and transformed for accurate and relevant insights.

Analytical Approach
Data Cleaning and Transformation
Key data preparation steps included:

Dropping redundant columns and ensuring consistent formatting.
Creating unique client_id identifiers to avoid giving undue weight to repeat purchasers.
Grouping unique clients into a data frame with demographics, loyalty points, and purchase frequency for robust analysis.
Techniques and Models
To address each business question, I employed the following techniques:

Machine Learning Technique	Objective
Multiple Linear Regression (OLS)	Understanding customer engagement with loyalty points
Decision Tree Regressor	Analyzing loyalty drivers
K-Means Clustering	Customer segmentation
Sentiment Analysis (TextBlob & VADER)	Leveraging review sentiment for insights
Key Insights
1. Loyalty Points Analysis
Customer loyalty points were found to be heavily skewed, with most customers earning fewer than 1500 points. The primary drivers of loyalty points include remuneration, spending score, and age, with higher remuneration and spending scores strongly correlating with increased loyalty points.

2. Customer Segmentation
I identified five distinct customer segments:

Casual Shoppers: Low remuneration, low spending; respond well to frequent small rewards.
Passionate Gamers: Low remuneration but high engagement; benefit from targeted loyalty programs and exclusive offers.
Balanced Buyers: Medium remuneration and spending; reliable purchasers who respond to personalized offers.
High Income Minimalists: High remuneration, low spending; motivated by exclusive products and premium promotions.
Premium Enthusiasts: High remuneration and spending; ideal for VIP programs and personalized communications.
3. Sentiment Analysis
Review sentiment analysis revealed that 90% of comments were positive, with negative sentiments correlating with lower loyalty points and one-time purchases. Turtle Games could benefit from offering tailored incentives, such as discounts and personalized support, to transform negative experiences into loyalty-building opportunities.

Visualizations and Notebook Structure
The Jupyter notebook is organized for clarity, with branded color schemes in the visualizations reflecting Turtle Games’ identity. It includes:

Exploratory Data Analysis: Univariate and bivariate analyses to understand customer trends.
Model Implementation and Results: Detailed insights and recommendations for each business objective.
