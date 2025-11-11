### Numeridex-Supermarket-Sales-Analysis-Report


## Introduction
This project analyzes a supermarket sales dataset containing detailed information on customer transactions across multiple branches. 
The aim is to identify sales trends, understand customer purchasing behavior, and evaluate overall business performance. Using Power BI, 
the data was cleaned, transformed, and visualized through interactive dashboards. These dashboards highlight sales trends across branches, 
top-performing product lines, customer preferences, and payment patterns. The insights gained from this analysis provide a clear understanding of what drives revenue and customer satisfaction, 
supporting data-driven decision-making for future growth.


## Objectives
The objectives of this project are:
* To analyze overall sales performance across different product categories, cities, and branches to identify key revenue drivers.
* To evaluate customer distribution and purchasing behavior based on customer type, gender, and payment method.
* To monitor monthly sales trends in order to identify peak and low-performing periods.
* To assess product category performance by comparing total sales and average unit prices across cities.
* To measure customer engagement and satisfaction levels through the average rating metric.
* To understand branch-level performance and how customer type influences sales within each branch.
* To identify actionable insights that can guide business strategies, improve sales efficiency, and enhance customer experience.

## Dataset Description
The dataset contains sales transaction records from a supermarket chain operating across three branches (A, B, and C) located in different cities (Yangon, Mandalay, and Naypyitaw) in Myanmar. 
It captures detailed transaction information from January through March 2019, with 100 records representing customer purchases across various product categories.

## Feature Description
The dataset includes the following attributes: 	
* Invoice ID: Unique identifier for each transaction (e.g., 750-67-8428)
* Branch: Branch where the sale occurred (A, B, or C)
* City: Geographic location of the branch (Yangon, Mandalay, or Naypyitaw)
* Customer Type: Customer classification (Member or Normal)
* Gender: Customer gender (Male or Female)
* Product Line: Category of products purchased (Health and beauty, Electronic accessories, Home and lifestyle, Sports and travel, Food and beverages, Fashion accessories) 
* Unit Price: Price per individual item in the transaction
* Quantity: Number of items purchased
* Tax 5%: Tax amount charged per transaction (5%)
* Total: Total price including tax
* Date: Transaction date (MM/DD/YYYY format)
* Payment: Payment method used (Cash, Credit card, or Ewallet)
* Rating: Customer satisfaction rating on a scale of 1–10

## Data Preparation
I began by cleaning our dataset in Excel where we 
* removed irrelevant columns
* checked for blank cells
* duplicated the file for backup
* verified numerical accuracy through calculations. 
* The cleaned data was then imported into Power BI for visualization.
Using Power BI, I created:
* Line Charts to show trends over time
* Bar Charts for category comparisons
* Pie Charts to illustrate proportions
* Doughnut Charts for a modern visual alternative
* Column Chart – to display vertical comparisons

## Analysis & Findings
Total Sales by Product Line
    Product Name	             Sales Value 	
* Health & Beauty	8.3K	  Generated the highest revenue
* Sports & Travels	7.4K	The second highest, had a good market performance
* Food & Beverages	6.9K	Had a reliable portion in overall sales
* Electronics Accessories	5.2K	Product with average sales performance
* Home & Lifestyle	4.8K	Product below average sales contribution
* Fashion Accessories	4.1K	Had the lowest sales contribution, promotion may be needed or product review
 
Findings: from the analysis above, the Health & Beauty products are the top performers, they contributed most to the total sales value.

## Distribution of Gender
* Male: 51%
* Female: 49%

Findings: There is almost an equal distribution among both genders, just a slight male dominance, Marketing campaigns can ensure that both genders are targeted effectively.

## Count of Customer Type by Branch:
Branch	Member	Normal	Remarks
A	17	18	Balanced
B	18	12	More Members
C	15	20	Had more Members overall

Findings: Branch A & C had the highest number of customers; however, Membership engagement is strong in Branch B, followed by Branch A, Branch C had the highest walk-in customers.

## Quantity Sold by City:
City Name	Quantity	  Share of Units Sold (%)
* Yangon	                 214	36.77%
* Naypyitaw	               211	36.25%
* Mandalay	               157	26.98%

Findings:
* Yangon leads slightly in quantity sold
* Mandalay had the lowest sales volume; there is need to improve sales performance.

## Total Sales by Month:
Month	Sales(K)	          Trend
January 	12K	        Second highest sales month
February	11.14K	    Month with the lowest sales
March	13.49K	        Month with the Highest Sales

Findings:
Sales declined in February, but improved in March which indicate seasonal or promotional effect.

## Average Unit Price by Products & City:
* Highest Average Unit Price: Food & Beverages in Naypyitaw (≈80).
* Lowest Average Unit Price: Electronic Accessories in Mandalay (≈46)

Findings:
* Naypyitaw displays a strong pricing pattern.
* Yangon is prone to have more competitive lower prices across all products.

## Insights and Interpretation
* Health & Beauty, Sports & Travel, and Food & Beverages are the top-performing product categories, driving the majority of sales revenue.
* Branch C (Naypyitaw) recorded the highest sales.
* E-wallet payments are the most preferred payment method.
* Normal customers generate more total revenue than Members.
* Sales performance peaked in March after a February dip
* The average customer rating of 6.89 indicates moderate satisfaction, highlighting opportunities for service quality improvements.
* Electronic Accessories and Fashion Accessories significantly underperformed.

## Recommendations
* Increase stock and promotional activities for Health & Beauty, Sports & Travel, and Food & Beverages to capitalize on high demand.
* Investigate and address underperformance in Electronic Accessories, Fashion Accessories, and Home & Lifestyle through pricing reviews or product repositioning.
* Study and replicate Branch C's successful strategies across Branch A and Branch B to improve overall sales performance.
* Strengthen membership programs with exclusive benefits and discounts to convert more normal customers into loyal members.
* Introduce E-wallet payment incentives such as cashback or loyalty points to encourage digital adoption and reduce transaction costs.
* Improve customer experience and service quality to raise the average rating above 6.89, particularly in lower-rated branches.
* Implement strategic bundling of underperforming products with top sellers to boost sales of weaker categories.

## Conclusion
This analysis has successfully identified the key drivers of sales performance across product categories, cities, and branches, 
while providing valuable insights into customer purchasing behavior and payment preferences. Monthly trend analysis revealed seasonal patterns in sales activity, 
and cross-city comparisons highlighted regional variations in product demand and pricing. Customer satisfaction ratings indicated areas requiring service improvement, 
while customer type emerged as a significant factor influencing branch performance. These findings provide management with a data-driven foundation to make informed strategic decisions, 
optimize operational efficiency, enhance customer loyalty, and improve overall business performance.







