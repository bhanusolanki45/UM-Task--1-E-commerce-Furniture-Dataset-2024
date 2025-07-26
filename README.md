# UM-Task--1-E-commerce-Furniture-Dataset-2024-
E-commerce Furniture Dataset 2024  (  ML _ FA _ DA projects )

# 📁 Dataset Overview

The dataset contains transactional-level data from an online furniture store, with features such as:

Order Date

Ship Date

Sales

Profit

Discount

Product Category

Region, Segment, and City

And other relevant business indicators



🧹 Data Preprocessing
Loaded the dataset using pandas

Identified and handled missing values

Converted data types where required (e.g., date parsing)

Cleaned column names and filtered relevant columns for analysis



📈 Exploratory Data Analysis (EDA)
Visualized sales, profit, and discount distributions using Seaborn and Matplotlib

Plotted correlation heatmaps to find relationships between numeric features

Used boxplots and pairplots to observe trends across product categories and segments

Identified top-performing categories, cities, and regions


🔍 Key Insights
High Discounts were often associated with low or negative profits

Office Supplies had more transactions but lower average sales compared to Furniture

Certain cities and regions consistently underperformed in profit margins

Found strong correlation between sales and profit, but this varied by category



🤖 Model Development
Applied Linear Regression to predict Profit based on variables such as Sales, Discount, and Category

Split the dataset into training and testing sets

Evaluated model performance using Mean Squared Error (MSE)



📌 Tools & Libraries
Python (Jupyter Notebook)

pandas, numpy

matplotlib, seaborn

scikit-learn
