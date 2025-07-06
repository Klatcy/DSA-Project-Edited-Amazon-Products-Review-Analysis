---
# DSA-Project  
## Project Title: Amazon Products Review Analysis

---

## 📌 Table of Contents
- [Introduction](#introduction)  
- [Project Overview](#project-overview)  
- [Data Sources](#data-sources)  
- [About the Dataset](#about-the-dataset)  
- [Tools Used](#tools-used)  
- [Data Cleaning and Preparations](#data-cleaning-and-preparations)  
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
- [Data Analysis](#data-analysis)  
- [Data Visualization](#data-visualization)  
- [Conclusion](#conclusion)  
- [Recommendations](#recommendations)  

---

## ✅ Introduction

In today's data-centric business landscape, informed decision-making is crucial. This project involves analyzing Amazon product reviews to uncover key trends and generate actionable insights that can inform product development, marketing strategies, and consumer engagement. The goal is to provide a roadmap for product improvements and drive sustainable growth.

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

- `discounted_price`  
- `potential_revenue`  

Each row is a product record, with review data summarized for analysis.

---

## 🛠️ Tools Used

- **Microsoft Excel** – Data cleaning, pivot tables, dashboards  
- **SQL** – Querying and slicing data  
- **GitHub** – Hosting project files  
  [GitHub Repo](https://github.com/Klatcy/DSA-Project-.-Amazon-Product-Review-Analysis-/)

---

## 🧹 Data Cleaning and Preparations

Before diving into the analysis, the dataset was cleaned and preprocessed to ensure consistency and accuracy. The key steps in this process included:

- Removing null or missing values in critical columns like product name, category, price, and rating.  
- Converting data types: Prices and discounts were converted from strings to numerical formats for computation.  
- Standardizing text in columns like product name and category (e.g., lowercasing, trimming spaces).  
- Filtering invalid entries: Removed products with price or rating equal to 0.  
- Extracting numerical values from strings (e.g., "50% off" → 50).  
- Creating new columns:  
  - `discounted_price = price - (price × discount%)`  
  - `potential_revenue = discounted_price × number_of_reviews`

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
- 🔢 Number of Unique Products per Price Range Bucket (e.g., )  
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

---

## ✅ Conclusion

The analysis of Amazon product data provided insightful findings across multiple categories:

- **Electronics** and **Home & Kitchen** had the highest number of products and reviews, indicating strong demand and engagement.  
- **Toys & Games** and **Office Products** had fewer reviews despite a moderate number of listings, showing opportunity for better visibility or engagement.  
- **Musical Instruments** and **Health & Personal Care** received some of the highest average ratings, suggesting strong customer satisfaction.  
- The **₦10,000 – ₦50,000** price range had the most unique products, making it the most competitive segment.  
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
Target the **₦10k – ₦50k** range where most sales and product listings occur.

