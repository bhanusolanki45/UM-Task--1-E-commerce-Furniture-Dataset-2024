# UM-Task--1-E-commerce-Furniture-Dataset-2024-
# 🛒 E-Commerce Furniture Sales Analysis (2024)
## This project presents a data analysis of a simulated e-commerce furniture dataset, focusing on sales performance, customer trends, and key business metrics. Using Python, we perform exploratory data analysis (EDA) to generate actionable insights and visualize customer behavior in the online furniture market.


# 📁 Dataset Overview
File: ecommerce_furniture_dataset_2024.csv

* Records: 2,000 rows

* Columns:

* Customer ID

* Product Name

* Category

* Sales

* Profit

# 🧹 Data Preprocessing
* Checked for null/missing values — dataset was clean.

* Verified data types and column distributions.

* Applied basic statistical summary to understand scale and distribution of Sales and Profit.

# 📊 Exploratory Data Analysis (EDA)
*  Top-Selling Products
Identified top 10 furniture items by sales volume.

Insight: Certain product types consistently outperform others across all customers.

*  Top Categories by Revenue
Analyzed total sales and profit by furniture category.

Insight: Some categories generate high sales but relatively lower profit, indicating potential pricing or cost issues.

*  Profit vs Sales Analysis
Scatter plots used to understand the correlation between sales and profit.

Insight: High sales do not always translate into high profit — some products may be sold at discount or low margin.

*  Customer-Wise Sales Performance
Identified most valuable customers based on total spending.

Insight: A small group of customers contributes a large share of revenue — useful for targeting in loyalty programs.

*  Profitability Heatmap
Used a heatmap to compare product-wise profitability.

Insight: Helped identify underperforming or loss-making SKUs.

# 📈 Visualizations Used
* Bar plots (Top Products & Categories)
  Insights:

Certain products like [e.g., Bookcase, Chairs] generate higher sales consistently.

Not all top-selling categories are highly profitable.

The Office Furniture category, while high in sales, has lower margins compared to Home Furniture.

Decision Use:
Focus marketing campaigns on high-profit and high-sales products. Re-evaluate low-profit high-sales items for pricing optimization.

* Pie chart (Category share)
  
Insights:

A few categories dominate the product mix, e.g., Chairs and Tables.

Some categories have a small share, indicating potential under-exploration or niche demand.

Decision Use:
Diversify offerings in underrepresented but potentially profitable categories. Also, identify if the dominant categories are oversaturated.

  

* Scatter plots (Sales vs Profit)

  Insights:

No perfect linear relationship between sales and profit.

Some products with very high sales have low or even negative profit.

Profitability varies drastically even at similar sales volumes.

Decision Use:
Identify and reduce dependency on low-margin, high-sales products. Consider adjusting pricing or reducing costs.

* Heatmaps (Profit distribution)

Insights:

Red zones indicate loss-making items.

Green or yellow zones highlight profitable products.

You can spot outliers that skew total profit.

Decision Use:
Eliminate or redesign products consistently in the red zone. Double down on products with steady profits across segments.



* Count plots (Product/Category frequency)

Insights:

High-frequency items may not always be the most profitable.

Shows popularity or customer preference, which may or may not align with profitability.

Decision Use:
Bundle popular items with low frequency but high profitability items to balance revenue and customer satisfaction.



# 🧠 Key Insights
* There is no direct correlation between high sales and high profit for all products.

* Product bundling and cost optimization are key areas for improving margins.

* Customer segmentation can help target high-value users with tailored promotions.

* The furniture category with the most items is not always the most profitable.

# 🛠️ Technologies Used
* Python

* Pandas

* NumPy

* Matplotlib

* Seaborn

* Google Colab

# ✅ Business Recommendations
* Focus marketing on top-performing and high-margin products.

* Review pricing strategy for low-profit high-selling items.

* Implement targeted loyalty campaigns for high-value customers.

* Consider cost-cutting strategies for underperforming products.


# ✅ Recommended Business Decisions Based on Analysis
1. Optimize Product Portfolio
Identify and discontinue products that generate high sales but result in low or negative profit (as seen in the scatter plots and heatmaps).

Focus on top-performing categories (high sales and high profit), such as [insert top profitable category from your analysis—e.g., Tables or Chairs].

2. Improve Pricing Strategy
Products with high sales but low profit indicate possible pricing issues or high costs.

Reassess pricing for such products, or negotiate with suppliers to reduce costs.

3. Promote High-Profit, Low-Sales Products
Use marketing to increase visibility of low-frequency but high-margin products.

Consider bundling these with popular items to boost exposure and sales.

4. Inventory & Demand Planning
Use count plots to align inventory management with product demand.

Avoid overstocking low-frequency items that don’t generate much revenue.

5. Category-Level Strategy
As shown in the pie chart, a few categories dominate sales.

Consider expanding into underrepresented categories that may have untapped market potential.

6. Remove Loss-Making Items
Heatmaps show clear patterns of loss in certain products/categories.

These should be phased out or re-engineered to improve profit margins.

7. Refine Marketing Campaigns
Bar plots reveal customer preferences—target advertising toward best-sellers and profitable products.

Also, focus on emerging or niche categories that show signs of growth.

8. Customer-Centric Insights
Use insights to create customer personas: e.g., users who frequently buy chairs might be office managers.

Tailor promotions or loyalty programs to their needs.

9. Regularly Monitor Profitability
Continuously use scatter plots and heatmaps to track changes in profitability over time.

Build a dashboard that alerts management when certain products fall below a profit threshold.

