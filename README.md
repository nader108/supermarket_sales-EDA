##Supermarket Sales Data Analysis#


Overview
This project focuses on Exploratory Data Analysis (EDA) of a supermarket sales dataset. The analysis aims to uncover insights about customer behavior, product sales, and supermarket performance. By visualizing and interpreting key features such as customer type, product line, sales by branch, and ratings, we gain valuable insights into how the supermarket operates and which factors influence sales performance.

Dataset
The dataset used in this project is a Supermarket Sales dataset, which contains 1,000 records with the following columns:

Invoice ID: Unique identifier for each transaction
Branch: Supermarket branch (A, B, C)
City: City where the branch is located
Customer type: Whether the customer is a 'Member' or 'Normal'
Gender: Gender of the customer
Product line: Category of product purchased
Unit price: Price of a single unit of the product
Quantity: Quantity of the product purchased
Tax 5%: Tax on the product sale
Total: Total amount spent by the customer
Date: Date of the transaction
Time: Time of the transaction
Payment: Method of payment used (e.g., Credit card, Ewallet, Cash)
Cogs: Cost of goods sold
Gross margin percentage: Gross margin percentage for the product
Gross income: Gross income generated from the sale
Rating: Customer satisfaction rating
Objectives
The primary objectives of this analysis are:

Exploratory Data Analysis (EDA): Clean and analyze the data to extract meaningful insights.
Data Visualization: Use charts and graphs to identify trends, patterns, and correlations.
Customer and Sales Analysis: Understand customer behavior based on gender, type, branch, and payment methods.
Sales and Product Insights: Investigate how different products and branches perform in terms of sales and ratings.
Key Findings
Customer Analysis: The data shows that female customers have a higher total spend across both Member and Normal customer types.
Branch Performance: Branch A outperforms the other branches in terms of total sales, followed by Branch C and Branch B.
Product Line Analysis: Categories like Health and beauty and Sports and travel contribute significantly to the supermarket's revenue.
Correlation Analysis: A heatmap of the correlation matrix reveals strong relationships between Unit price, Quantity, and Total sales.
Visualizations
The analysis includes the following visualizations:

Bar plots: To analyze total sales by Customer type and Gender.
Correlation heatmap: To uncover correlations between key variables such as Unit price, Quantity, and Total.
Pie charts: To visualize the distribution of sales across different Product lines and Payment methods.
Conclusion
The Supermarket Sales Data Analysis provides valuable insights into the sales patterns, customer preferences, and branch performance of the supermarket. The findings can help the supermarket make data-driven decisions on improving customer satisfaction, optimizing inventory, and targeting specific customer segments.

Requirements
pandas
numpy
seaborn
matplotlib
plotly
scikit-learn
