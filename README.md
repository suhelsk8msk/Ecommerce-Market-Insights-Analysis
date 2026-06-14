# 📊 Detailed Analysis – Ecommerce Market Insights Analysis

## ▶️  Project Overview

* Conducted an end-to-end exploratory data analysis (EDA) on an e-commerce dataset containing approximately 1,000 records.
* Analyzed product-related, customer-related, shipping-related, and market-related variables.
* Applied data cleaning, preprocessing, statistical analysis, and visualization techniques using Python.
* Generated actionable business insights to support decision-making and improve business performance.

---

## ▶️ Data Understanding

### Dataset Characteristics

* Total Records: 999
* Total Features: 16
* Data Type: Structured Dataset
* Missing Values: None
* Duplicate Records: Checked and handled
* Categories Included:

  * Electronics
  * Books
  * Apparel
  * Footwear
  * Home Appliances

### 🔑 Key Variables

* Product Name
* Category
* Price
* Discount
* Tax Rate
* Stock Level
* Customer Age Group
* Customer Gender
* Customer Location
* Shipping Cost
* Shipping Method
* Return Rate
* Seasonality
* Popularity Index

---

## ▶️ Data Cleaning & Preparation

### Data Quality Checks

* Inspected dataset structure and data types.
* Verified dataset dimensions.
* Checked for missing values.
* Identified duplicate records.
* Validated numerical and categorical columns.

### Data Wrangling Operations

* Removed duplicate observations.
* Standardized column formats.
* Verified consistency of category names.
* Prepared data for statistical analysis and visualization.
---

This README is written as if a Data Analyst is presenting the project to recruiters and hiring managers.

# 📊 Ecommerce Market Insights Analysis

## Project Overview

This project focuses on analyzing an e-commerce dataset containing 999 product and customer records across multiple product categories. The objective of the analysis is to uncover meaningful insights related to product performance, customer demographics, pricing strategies, inventory management, shipping preferences, and market trends using Python-based data analysis techniques.

The project follows a complete Exploratory Data Analysis (EDA) workflow, including data cleaning, data exploration, statistical analysis, and data visualization using Pandas, NumPy, Matplotlib, and Seaborn.

---

## Dataset Information

### Total Records

* 999 Rows

### Total Features

* 16 Columns

### Features Included

* Product ID
* Product Name
* Category
* Price
* Discount
* Tax Rate
* Stock Level
* Supplier ID
* Customer Age Group
* Customer Location
* Customer Gender
* Shipping Cost
* Shipping Method
* Return Rate
* Seasonality
* Popularity Index

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook

This level of documentation makes the project look much more professional and recruiter-friendly than simply uploading charts and code.

---

## Exploratory Data Analysis (EDA)

### 1. Product Category Distribution

<img width="571" height="514" alt="1  Product Category Distribution" src="https://github.com/user-attachments/assets/f57d9b28-f506-4477-a211-b5af0c57acf1" />


The dataset contains products from five major categories:



## **Insight**

* **Books** represent the **largest product category **in the dataset.
* **Apparel** contains the **fewest products**.
* Product distribution is relatively balanced across all categories, indicating a diversified marketplace.

#### Business Value

A balanced product portfolio reduces dependency on a single category and supports broader customer reach.

---

### 2. Average Product Price Analysis
<img width="580" height="514" alt="2 Average Product Price by Category" src="https://github.com/user-attachments/assets/8879e19f-5eab-4631-acfd-7dd4e75caf1a" />

## **Insight**

* **Footwear** products have the** highest average selling price**.
* **Electronics** products have the **lowest average price** among all categories.
* Price differences between categories are relatively small, indicating consistent pricing strategies.

#### Business Value

Premium-priced categories such as Footwear and Home Appliances may contribute higher revenue opportunities.

---

### 3. Discount Analysis

## **Insight**

* **Apparel** receives the **highest average discount**.
* **Home Appliances** receive the **lowest average discount**.
* Discount levels remain fairly consistent across categories.

#### Business Value

Apparel may rely more heavily on promotional strategies to drive customer engagement and sales.

---

### 4. Customer Age Group Analysis
<img width="571" height="432" alt="3 Customer Age Group Analysis" src="https://github.com/user-attachments/assets/ad989bfc-1b37-4179-b094-d89e2ad13bd9" />

## **Insight**

* Customers **aged 55+** represent the **largest customer segment**.
* Younger **customers (18–24)** represent the **smallest segment**.
* **The customer base is dominated by middle-aged and senior consumers**.

#### Business Value

Marketing campaigns should prioritize mature customer segments while exploring strategies to attract younger customers.

---

### 5. Customer Gender Analysis
<img width="409" height="389" alt="4  Customer Gender Analysis" src="https://github.com/user-attachments/assets/e8094e38-3186-478e-a08a-08e0e858ec6e" />

## **Insight**

* Customer distribution is remarkably balanced across genders.
* **Female customers hold a slight lead over other groups**.

#### Business Value

The business appeals to a diverse customer base, supporting inclusive marketing strategies.

---

### 6. Customer Location Analysis
<img width="713" height="432" alt="5  Customer Location Analysis" src="https://github.com/user-attachments/assets/7f058bf4-d8df-4665-9412-8a7013ea8992" />

Top customer locations include:

* Cape Town, South Africa
* Singapore
* London, UK
* Phoenix, USA
* Houston, USA
* Paris, France
* Toronto, Canada
* Tokyo, Japan

## **Insight**

* Customer activity is distributed globally.
* **Cape Town** generates the **highest customer count**.
* Strong customer presence exists across North America, Europe, Asia, and Africa.

#### Business Value

The marketplace demonstrates international reach and growth potential in multiple geographic regions.

---

### 7. Shipping Method Analysis

## **Insight**

* **Standard Shipping** is the **most preferred delivery method**.
* Demand remains relatively balanced across all shipping options.
* Customers value both cost-effective and faster delivery services.

#### Business Value

Businesses should continue optimizing standard shipping while maintaining premium delivery options.

---

### 8. Return Rate Analysis

## **Insight**

* **Home Appliances** experience the **highest return rate**.
* **Books** have the **lowest return rate**.
* Return rates are relatively similar across categories.

#### Business Value

Reducing return rates in Home Appliances could improve customer satisfaction and reduce operational costs.

---

### 9. Seasonality Analysis

## **Insight**

* Seasonal products achieve slightly higher popularity scores.
* Seasonal demand appears to positively influence customer interest.

#### Business Value

Seasonal inventory planning and promotional campaigns can help maximize sales opportunities.

---

### 10. Product Popularity Analysis
<img width="543" height="513" alt="6 Top 10 most popular products" src="https://github.com/user-attachments/assets/f0b7f045-519b-4d32-a403-c2f4879fb186" />

Top Popular Products:

1. Smartphone
2. Hiking Shoes
3. Flats
4. Speaker
5. Microwave
6. Cookbooks
7. Monitor
8. Comics
9. Headphones
10. Fiction

## **Insight**

* **Smartphones** are the most popular products in the dataset.
* Both technology and lifestyle products appear among the top-performing products.
* Product popularity is distributed across multiple categories.

#### Business Value

High-performing products should receive priority in inventory management, promotions, and marketing campaigns.

---

### 11. Stock Level Analysis

## **Insight**

* **Electronics** maintain the **highest inventory levels**.
* **Footwear** maintains the **lowest stock levels**.
* Inventory allocation appears aligned with anticipated customer demand.

#### Business Value

Maintaining adequate inventory for popular categories reduces stockout risks and supports customer satisfaction.

---
### 11. Correlation Analysis
<img width="613" height="517" alt="7 Correlation Analysis" src="https://github.com/user-attachments/assets/9e4bb3b7-6726-4375-9544-852b9b3ec7d3" />


----
## 🔑 Key Business Findings

* Books represent the largest product category in the marketplace.
* Footwear products command the highest average prices.
* Apparel products receive the largest discounts.
* Customers aged 55+ form the largest customer segment.
* Customer distribution is highly balanced across genders.
* Cape Town, Singapore, and London are among the strongest customer markets.
* Standard shipping is the preferred delivery method.
* Home Appliances experience the highest return rates.
* Seasonal products achieve higher popularity scores than non-seasonal products.
* Smartphones are the most popular products in the dataset.
* Electronics maintain the highest average stock levels.

---

## Business Recommendations

### Product Strategy

* Prioritize inventory for highly popular products such as Smartphones and Hiking Shoes.
* Expand successful product categories with strong customer demand.

### Marketing Strategy

* Develop targeted campaigns for customers aged 35+ and 55+.
* Create region-specific marketing initiatives for top-performing locations.

### Pricing Strategy

* Evaluate the effectiveness of discount-heavy categories such as Apparel.
* Explore premium pricing opportunities in Footwear and Home Appliances.

### Inventory Management

* Monitor Electronics inventory levels to prevent overstocking.
* Increase stock allocation for products with consistently high popularity.

### Customer Experience

* Investigate the causes of high return rates in Home Appliances.
* Optimize delivery performance while maintaining affordable Standard Shipping options.

---

## Conclusion

This project demonstrates how exploratory data analysis can transform raw e-commerce data into actionable business insights. By analyzing customer demographics, product categories, pricing patterns, inventory levels, shipping preferences, and product popularity, the project highlights opportunities to improve operational efficiency, customer satisfaction, and overall business performance through data-driven decision-making.



