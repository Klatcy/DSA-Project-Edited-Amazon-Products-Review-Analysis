---
# DSA-Project  
## Project Title: Amazon Products Review Analysis

---

## 📌 Table of Contents

---

## ✅ Introduction


---

In the ever-evolving world of e-commerce, data-driven insights are critical to maintaining a competitive edge. This case study focuses on the analysis of product and customer review data sourced from Amazon, one of the largest global online marketplaces. Conducted under the guidance of RetailTech Insights, a firm that specializes in providing analytics solutions to online sellers, this analysis aims to uncover meaningful trends and patterns that can drive product enhancement, targeted marketing strategies, and improved customer engagement.

---

## 📊 Project Overview

This project focuses on analyzing Amazon product review data to extract meaningful business insights. The analysis is centered on understanding customer behavior, product performance, and discount strategies across various categories.

**Key objectives include:**
- Categorizing products based on ratings, reviews, and discounts  
- Identifying high-performing products  
- Estimating potential revenue  
- Discovering trends between discounts and ratings  
- Highlighting low-visibility products for improvement  

---

## 🔍 Data Sources

The dataset was **web-scraped from Amazon** and includes **1,465 rows** and **16 columns**. Each row represents a unique product.

**The dataset includes:**
- Product Attributes: name, category, original/discounted price, average rating  
- Customer Engagement: review counts and snippets  
- Derived Metrics: discount %, revenue estimates  

---

## 📄 About the Dataset

The dataset includes product details such as name, category, price, discount, and ratings. It also includes customer review metrics. It was transformed and cleaned to support analysis by creating fields like:

- 'price range bucket'
- `potential_revenue`
- 'weighted score' 

Each row is a product record, with review data summarized for analysis.

---

## 🛠️ Tools Used

- **Microsoft Excel** – Data cleaning, pivot tables, dashboards  

- **GitHub** – Hosting project files  
  [GitHub Repo](https://github.com/Klatcy/DSA-Project-.-Amazon-Product-Review-Analysis-/)

---

## 🧹 Data Cleaning and Preparations

Before diving into the analysis, the dataset was cleaned and preprocessed to ensure consistency and accuracy. The key steps in this process included:

- Removing null or missing values in critical columns like product name, category, price, and rating.  
- Converting data types: Prices and discounts were converted from strings to numerical formats for computation.  
- Splitting Category column 
- Filtering invalid entries: Removed products with price or rating equal to 0.   
- Creating new columns:   
  - `potential_revenue = actual_price × number_of_reviews`
  - 'Weighted Score =rating * rating count'
  - 'Price range bucket = , If actual_price< 200,"₹200", If actual_price < 500, "₹200–₹500", > "₹500"))

This preparation step ensured that the dataset was ready for meaningful and accurate analysis.

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution, spread, and key patterns in the dataset. Some of the initial observations included:

- Category Distribution: Count of products per category to identify popular segments.  
- Ratings Distribution: Spread of product ratings, identifying products with high or low performance.  
- Price Range: How product prices are distributed across the dataset.  
- Discount Trends: Identifying whether certain categories offer larger discounts.  
- Review Counts: Detecting the most and least reviewed products.  

This stage helped in forming hypotheses and framing the questions for deeper analysis.

---

## 📈 Data Analysis

Based on the project goals, the following key analyses were performed:

- 📦 Total Number of Products by Category  
- 📝 Total Reviews per Category  
- 💸 Average Discount % by Category  
- ⭐ Product with the Highest Average Rating  
- 💰 Total Potential Revenue Estimation  
- 📊 Distribution of Ratings  
- 🥇 Top Products by Review Count & Ratings  
- 📉 Products with Less than 1000 Reviews  
- 🎯 Product Category with the Highest Discount  
- 🛍️ Products Offering ≥50% Discount  
- 📈 Correlation Between Rating and Discount  
- 📊 Average Actual Price vs Discounted Price by Category  
- 🔢 Number of Unique Products per Price Range Bucket (e.g., < ₹200, ₹200–₹500, > ₹500)  
- 🔎 Categories with the Highest Discounts  
- 🏆 Top 5 Products Based on Combined Ratings and Review Counts  

---

## 📊 Data Visualization

Dashboards and pivot tables were used in Excel to visualize:
- Category performance  
- Price vs rating trends  
- Discounts across products  
- Review and rating distributions  

**Dashboard snapshots:**  





1. ![Pivot 1234  Amazon](https://github.com/user-attachments/assets/3af842ca-f62d-472c-b6a0-10ef11352956)




The pivot table above provides a comprehensive report, showcasing:

- Average Discount Percentage by Product Category
- Total Number of Products in each Category
- Total Number of Reviews by Category
- Products with the Highest Average Rating in each Category





2. ![Pivot 5 6 7 Amazon](https://github.com/user-attachments/assets/f8c7f66c-5bd1-42f1-a1e1-2a87f092e4d9)




The pivot table above provides a comprehensive report, showcasing:

- Average Actual Price Vs Discounted Price by Category.
- Products With Highest Number of Review.
- Products With 50% Discount and more.
  




3. ![Pivot 8, 9, 10, 11  Amazon](https://github.com/user-attachments/assets/3d049639-d0ed-4ff9-9d22-97c533af2309)

The pivot table above provides a comprehensive report, showcasing:

- Distribution of Product Rating
- Total Potential Revenue by Category
- Unique Products Per Price Range 
- Rating Relating to Level of Discount


  

4. ![Pivot 12, 13, 14   Amazon](https://github.com/user-attachments/assets/d30cafc6-44c9-4075-81b2-ca5653fb8565)



The pivot table above provides a comprehensive report, showcasing:

- Products lesser than 1000
- Product Category With Highest Discount
- Top 5 Products in Terms of Rating and Review 



5. ![Amazon Dashboard](https://github.com/user-attachments/assets/410a110d-0f8f-4268-8757-0732785ad89a)




In analyzing Amazon product reviews, various visualization tools were employed, including column charts, bar charts, pie charts, and line charts, providing a comprehensive understanding of the review data.



---

## ✅ Conclusion

The analysis of Amazon product data provided insightful findings across multiple categories:

- **Electronics** and **Home & Kitchen** had the highest number of products and reviews, indicating strong demand and engagement.  
- **Toys & Games** and **Office Products** had fewer reviews despite a moderate number of listings, showing opportunity for better visibility or engagement.  
- **Musical Instruments** and **Health & Personal Care** received some of the highest average ratings, suggesting strong customer satisfaction.  
- The **₹200 – ₹500** price range had the most unique products, making it the most competitive segment.  
- A large number of products had discounts of **50% or more**, but these did not always align with high ratings.
- Products with high review counts tended to dominate potential revenue, emphasizing the importance of customer feedback over pricing alone.

---

## ✅ Recommendations

### 1. 🎯 Focus on Popular Categories  
Invest more in categories like **Electronics** and **Home & Kitchen** with high reviews and product counts.

### 2. 🌟 Promote High-Rated but Less Engaged Categories  
Highlight **Musical Instruments** and **Health & Personal Care** to increase visibility and customer awareness.

### 3. 📢 Target Low-Review Products  
Improve marketing and presentation for products with fewer than 1,000 reviews, especially in **Toys & Games** and **Office Products**.

### 4. 💸 Optimize Discount Strategy  
Rather than focusing only on heavy discounts, apply moderate price cuts to quality products to build long-term value.

### 5. 💵 Focus on Competitive Price Ranges  
Target the **₹200 – ₹500** range where most sales and product listings occur.

.

