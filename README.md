# amazon-ecommerce-eda
Exploratory Data Analysis of Amazon E-commerce products to uncover trends, top-performing categories, and pricing insights using Python
# Amazon E-commerce EDA

![Python](https://img.shields.io/badge/python-3.10-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## Project Overview
Exploratory Data Analysis (EDA) on **1,465 Amazon products** to uncover trends in pricing, ratings, discounts, and customer reviews. The analysis provides actionable insights for product and category managers, helping to optimize sales, promotions, and customer satisfaction.

---

## Dataset
- Format: CSV (`amazon_eda_python.csv`)  
- Columns: Product info, category, prices, discounts, ratings, reviews, links, and images  
- Size: 1,465 rows × 16 columns  

---

## Key Features
- **Data Cleaning & Preprocessing:** Handled missing values, converted price, rating, and discount fields to numeric  
- **Feature Engineering:** Created `discount_amount`, `rating_level`, `price_bin_quantile`  
- **Descriptive & Category Analysis:** Top 10 categories by product count and average rating  
- **Statistical Testing:** Chi-square test to analyze the relationship between product price bins and rating levels  
- **Visualization:** Bar plots, histograms, boxplots, scatter plots to detect trends, outliers, and patterns  
- **Deliverables:** Cleaned dataset (`amazon_ecom_cleaned.csv`) + Markdown report (`amazon_eda_report.md`)  

---

## Technologies
- **Python** | **Pandas** | **NumPy** | **Matplotlib** | **Seaborn** | **Jupyter Notebook**

---

## Insights & Highlights
- **High-performing categories:** USB Cables, Smartwatches, Smartphones, Smart TVs, In-ear Headphones  
- **Top Products:** AmazonBasics HDMI Cables (>426k reviews, avg rating 4.4), boAt Headphones, Instant Pot Air Fryer  
- **Discount Analysis:** Smartwatches rely on deep discounts (~70%), while smartphones have modest markdowns  
- **Price vs Ratings:** Chi-square test significant (p = 0.0189), indicating higher-priced products more likely to have higher ratings  
- **Outliers:** Premium products with very high prices (>₹77,000) and extreme review counts (>400k)  

## Visualization Highlights

### 1. Top Categories by Product Count
![Top Categories](https://github.com/Shobnam/amazon-ecommerce-eda/blob/main/top_categories.png)

### 2. Rating Distribution
![Rating Distribution](https://github.com/Shobnam/amazon-ecommerce-eda/blob/main/rating_distribution.png)

### 3. Price vs Rating
![Price vs Rating](https://github.com/Shobnam/amazon-ecommerce-eda/blob/main/price_vs_rating.png)

### 4. Discount % vs Rating
![Discount vs Rating](https://github.com/Shobnam/amazon-ecommerce-eda/blob/main/discount_vs_rating.png)

### 5. Discount Percentage Distribution
![Discount Distribution](https://github.com/Shobnam/amazon-ecommerce-eda/blob/main/discount_distribution.png)




