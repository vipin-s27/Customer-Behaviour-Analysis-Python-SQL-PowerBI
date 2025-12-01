# 📊 Customer Shopping Behavior Analysis

This project analyzes 3,900 customer transactions to understand how users shop, what influences their purchases, and which customer groups drive the most revenue.
It includes data preparation in Python, SQL-based analysis, and a Power BI dashboard supported by a final business report and presentation.

# 🧾 Overview

The goal of this project is to uncover insights from customer transaction data and provide meaningful recommendations for business growth.
The workflow includes:

Loading and exploring the dataset in Python

Cleaning and preparing the data

Conducting in-depth SQL analysis

Building an interactive Power BI dashboard

Creating a business-focused report using Gamma AI

# 🗂️ Dataset Summary

Rows: 3,900

Columns: 18

Missing Values: 37 missing review ratings (handled during cleaning)

### Key Data Features:

Customer details: Age, Gender, Location, Subscription Status

Purchase information: Item Purchased, Category, Amount, Season, Size, Color

Shopping behavior: Discounts, Promo Codes, Review Rating, Shipping Type

Behavioral patterns: Previous Purchases, Purchase Frequency

**Dataset Used:** - <a href="https://github.com/vipin-s27/Customer-Behaviour-Analysis-Python-SQL-PowerBI/blob/main/Customer_Shopping_Behavior_Raw_Data.csv">Dataset</a>

# Dashboard
**Dashboard File** - <a href="https://github.com/vipin-s27/Customer-Behaviour-Analysis-Python-SQL-PowerBI/blob/main/Customer_Behaviour_Dashboard.pbix">View Dashboard File</a>

<img width="1285" height="724" alt="Screenshot 2025-12-01 111031" src="https://github.com/user-attachments/assets/a595947c-6ef9-4c19-96f8-27178fe65b5b" />

# 🛠️ Tools & Technologies

Python: Pandas, NumPy, Matplotlib/Seaborn

MySQL Server: SQL queries for deeper behavioral and segmentation insights

Power BI: Dashboard creation and KPI visualizations

Gamma AI: Final report and presentation

Jupyter Notebook / VS Code: Development environment

# 🔧 Project Workflow
### 1. Data Loading & Exploration

- Imported dataset with Pandas

- Reviewed structure using df.info(), summary statistics, and value distributions

### 2. Data Cleaning

- Imputed 37 missing review ratings using median per product category

- Removed duplicates and fixed inconsistent values

- Standardized categorical fields

### 3. Feature Engineering

- Created new columns for improved insights:

- age_group (18–25, 26–35, 36–50, 50+)

- purchase_frequency_days

- Customer segments: New, Returning, Loyal

### 4. SQL Analysis (MySQL)

- Performed deeper analysis including:

- Gender-wise revenue

- Subscriber vs non-subscriber purchases

- Top products

- Discount dependency analysis

- Customer segment insights

- Age-group revenue comparison

### 5. Power BI Dashboard

- Developed an interactive dashboard featuring:

- Key KPIs and real-time metrics

- Revenue breakdowns

- Product performance

- Subscription insights

- Filters for category, season, segments, shipping type

### 6. Final Presentation (Gamma AI)

- Created a structured business report summarizing:

- Key findings

- Customer segmentation

- Discount impact

- High-performing products

- Actionable recommendations

# 📈 Key Insights from the Report
### 1. Balanced Revenue by Gender

- Male and female customers contribute almost equally to revenue.

### 2. Subscribers Drive More Total Revenue

- Similar average spend (~$60)

- But subscribers contribute 60% more total revenue

- Subscription benefits strongly influence engagement

### 3. Age Group 26–35 Generates Highest Revenue

- This is the primary target segment for marketing and promotions.

### 4. Top-Rated Products

- Backpack – 4.8★

- Sneakers – 4.7★

- Jacket – 4.6★

### 5. Discount-Dependent Products

- Some items rely heavily on discounts (e.g., Handbag 68%, Sweater 65%).

# 🎯 Recommendations

- Boost Subscriptions: Highlight exclusive perks to convert more users

- Loyalty Programs: Reward repeat customers to grow the “Loyal” segment

- Smart Discounting: Offer discounts strategically to protect margins

- Targeted Marketing: Focus on ages 26–35 and express-shipping users

- Product Positioning: Promote top-rated and best-selling items

# 📬 Contact
Name: Vipin Suryavanshi

**Email:**  <a href="mailto:vipinsuryavanshi.vs@gmail.com">vipinsuryavanshi.vs@gmail.com</a>  

LinkedIn:  <a href="https://linkedin.com/in/vipin-suryavanshi">Vipin Suryavanshi </a>

GitHub:  <a href="https://github.com/vipin-s27">Vipin-s27 </a>
