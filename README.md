🛒 Amazon Case Study Dashboard (Excel BI Project)

An Excel-based Business Intelligence project analyzing Amazon product data scraped from the web. This project uses pivot tables, calculated fields, and data visualizations to explore customer engagement, pricing strategies, product categories, and performance metrics.


---

📑 Table of Contents

1. Project Overview


2. Data Source


3. Tools and Technique


4. Data Processing and Cleaning


5. Exploratory Data Analysis


6. Results


7. Observations and Insights


8. Recommendations


9. Limitations




---

1. 📌 Project Overview

This project focuses on analyzing product-level data from Amazon using Excel to extract actionable insights. The objective is to evaluate pricing patterns, product ratings, customer engagement, discount strategies, and potential revenue opportunities.


---

2. 📁 Data Source

Source: Web-scraped Amazon product pages

Format: CSV file

Total Records: 1,465 products

Total Fields: 16 columns

Key Columns:

Product Name

Category

Actual Price

Discounted Price

Discount %

Rating

Number of Reviews

Rating Count

Price Range Bucket

Review Titles & Content (comma-separated)




---

3. 🛠 Tools and Technique

Microsoft Excel

Pivot Tables & Charts

Calculated Columns (Discount %, Revenue)

Slicers and Filters for Dashboard Interactivity


Visualization Techniques

Column Charts

Donut Charts

Line Graphs

Tree Maps


Data Modeling

Custom fields to categorize price and calculate revenue




---

4. 🧹 Data Processing and Cleaning

Removed null and duplicate records.

Converted string formats (e.g., "₹50,000", "50%") into numeric values.

Created calculated fields:

Discount % = (Actual Price - Discounted Price) / Actual Price

Potential Revenue = Actual Price * Rating Count


Grouped price ranges into logical buckets:

<₹200, ₹200–₹500, >₹500


Extracted numerical counts from comma-separated review values where applicable.



---

5. 📊 Exploratory Data Analysis

Key Questions Addressed:

1. What is the average discount percentage by product category?


2. How many products are listed under each category?


3. What is the total number of reviews per category?


4. Which products have the highest average ratings?


5. What is the average actual vs discounted price by category?


6. Which products have the highest number of reviews?


7. How many products have a discount ≥50%? → ✅ 751 products


8. What is the distribution of product ratings?


9. What is the potential revenue by category?


10. Product count by price bucket


11. Rating vs discount correlation


12. Products with <1,000 reviews


13. Categories with highest discounts


14. Top 5 products by rating + number of reviews




---

6. 📈 Results

Total Products Analyzed: 1,465

Total Potential Revenue: ₹121.33 billion

Top Categories by Product Count:

Electronics (526)

Computers (453)

Home Kit (448)


Highest Potential Revenue: Electronics – ₹98 billion

Highest Average Discount: Home Kit – 58%

Top Rated Categories:

Office Products – 4.31

Computers – 4.15


Products with ≥50% Discount: 751

Rating Distribution Peak: 4.0–4.3 (most products fall within this range)

Price Range Dominance: 98.57% of products priced under ₹50,000



---

7. 🔍 Observations and Insights

1. Customer Preference Trends:
Most products fall between 4.0 and 4.3 ratings, indicating general satisfaction. High ratings are consistent across categories, but the number of reviews helps gauge true popularity.


2. Dominance of Electronics:
Electronics not only has the highest number of products but also leads in potential revenue, making it the most commercially impactful category.


3. Aggressive Discounting in Home Kit & Computers:
Categories like Home Kit (58%) and Computers (54%) offer significant discounts, possibly to remain competitive. These may also represent seasonal or clearance sales strategies.


4. Majority Low-Priced Products:
Nearly 99% of all products are below ₹50,000, showing a strong leaning toward affordability. This affects both the discount strategy and revenue margins.


5. Office Products Lead in Rating:
Despite a smaller number of products, Office Products have the highest average rating (4.31), signaling high satisfaction among fewer items.


6. Low Engagement in Some Categories:
Categories like Toys & Games and Health have low review counts and little revenue contribution—suggesting either lower interest or marketing gaps.


7. Discount–Rating Paradox:
Products with the highest discounts don't always have the highest ratings, implying that deep discounts don’t guarantee quality perception.




---

8. ✅ Recommendations

Double Down on Electronics: Optimize listing quality, SEO, and promotions to capitalize on its high revenue potential.

Promote Office Products: With high user satisfaction, these can be pushed more via marketing and bundling strategies.

Audit Low-Engagement Categories: Reassess product mix in categories with zero revenue or low review counts.

Target Mid-Rated Products (4.0–4.3): They dominate the rating distribution and may benefit from minor product or presentation improvements.

Optimize Discount Strategy: Consider data-backed discounting to avoid unnecessary margin cuts where ratings are already high.



---

9. ⚠️ Limitations

Static Data: Snapshot from a specific time; no real-time or seasonal variation is captured.

Review Data: Stored as text in CSV, so deep sentiment analysis was not performed.

Currency Impact: All pricing is assumed consistent; international currency differences not accounted for.

Platform Bias: Only includes Amazon data; broader eCommerce insights would require multi-platform analysis.



---

Would you like a suggested folder structure and filenames to help you upload this to GitHub? I can provide that next.


