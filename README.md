# 🛒 DMart Sales Dashboard | Microsoft Excel

## 🎯 Project Objective

The objective of this dashboard is to analyze DMart sales performance and provide interactive insights into sales trends, profitability, customer behavior, regional performance, product categories, and payment preferences to support data-driven business decisions.

---

## 📊 Dataset Description

The dataset contains retail sales transaction records from a DMart store. Each row represents a customer order and includes sales, profit, discount, customer details, product category, payment mode, region, city, and delivery information.

### Dataset Columns

| Column        | Description                             |
| ------------- | --------------------------------------- |
| Order ID      | Unique identifier for each order        |
| Sales         | Total sales amount before discount      |
| Order Date    | Date the order was placed               |
| Month         | Month extracted from Order Date         |
| Region        | Sales region (East, West, North, South) |
| Category      | Product category                        |
| Quantity      | Number of units sold                    |
| Delivery Date | Date the order was delivered            |
| Customer Type | Member, New, or Regular                 |
| Payment Mode  | UPI, Card, or Cash                      |
| Discount      | Discount amount applied                 |
| Net Revenue   | Revenue after deducting the discount    |
| Profit        | Profit earned from the order            |
| City          | City where the order was placed         |

---

## 🧮 Calculated Columns

* **Month** – Extracted from the Order Date.
* **Discount** – Calculated discount amount for each order.
* **Net Revenue** – Sales amount after deducting the discount.

---

## 📈 Dashboard Features

### KPI Cards

* Total Orders
* Total Sales
* Total Net Revenue
* Total Profit
* Total Quantity Sold
* Average Order Value
* Profit Margin (%)

### Charts

* 📈 Monthly Sales Trend
* 📊 Sales vs Profit by Month
* 📊 Profit by Category
* 🥧 Sales by Customer Type
* 🍩 Payment Mode Distribution
* 📊 Sales by Region
* 📍 Sales vs Profit by City

### Interactive Filters

* Year
* Order Month
* Region
* Category
* Customer Type
* Payment Mode

---
## 📊 Dashboard Preview

!DMART DASHBOARD.png

## 🔍 Key Insights

* **Total Sales:** ₹39.26M
* **Total Net Revenue:** ₹35.34M
* **Total Profit:** ₹6.87M
* **Total Orders:** 15,345
* **Total Quantity Sold:** 76.8K units
* **Average Order Value:** ₹2,559
* **Overall Profit Margin:** 17.5%

### Regional Performance

* **North** is the highest-performing region by sales, generating approximately **₹10.1M** in sales.
* **East** has the lowest sales among the four regions, at approximately **₹9.5M**.
* The difference between the regions is relatively small, indicating a fairly balanced regional sales distribution.

### Category Performance

* **Electronics** is the most profitable category, generating approximately **₹1.40M** in profit.
* **Grocery** generates approximately **₹1.35M** in profit.
* **Clothing** has the lowest profit among the categories, at approximately **₹1.34M**.
* Overall, profit is distributed fairly evenly across the product categories.

### Customer Type

* **New customers** contribute approximately **34%** of sales.
* **Member customers** contribute approximately **33%**.
* **Regular customers** contribute approximately **33%**.
* Customer contribution is therefore fairly balanced across all three customer types.

### Payment Mode

* **UPI** is the most-used payment mode at approximately **34%**.
* **Card** and **Cash** each contribute approximately **33%**.
* The distribution shows that customers use all three payment methods almost equally.

### Monthly Sales Trend

* Sales fluctuate throughout the year rather than following a continuous upward or downward trend.
* **January** records one of the highest monthly sales values at approximately **₹3.47M**.
* **April** records the lowest monthly sales at approximately **₹3.12M**.
* Sales recover after April, with strong performance again during **July, September, and October**.

### City Performance

* Sales are relatively close across the six cities.
* **Chennai and Delhi** are among the stronger-performing cities by sales.
* **Pune** records the lowest sales among the six cities shown in the dashboard.
* Profit follows a similar pattern to sales across the cities.

---

## ❓ Business Questions Answered

* What are the total sales and total profit?
* What is the total net revenue after discount?
* Which region generates the highest sales?
* Which category is the most profitable?
* Which customer type contributes the most sales?
* Which payment mode is used the most?
* Which cities generate the highest sales?
* How do sales change month by month?
* What is the average order value?
* What is the overall profit margin?
* How much discount has been provided?
* How do sales and profit vary across regions, categories, months, and cities?

---

## 📝 Conclusion

The DMart Sales Dashboard provides a consolidated view of overall sales performance, profitability, customer behavior, regional performance, and payment preferences.

The analysis shows that the business generated **₹39.26M in total sales**, **₹35.34M in net revenue**, and **₹6.87M in profit**, with an overall **17.5% profit margin**. Regional and city-level performance is relatively balanced, while Electronics is the strongest category in terms of profit.

Customer types and payment modes are also distributed fairly evenly, indicating that the business serves a diverse customer base with no single dominant payment method.

Overall, the dashboard helps identify **high-performing regions and categories, monthly sales patterns, customer behavior, and profitability trends**, making it easier to monitor performance and support data-driven business decisions.

---

## 🛠️ Tools & Technologies

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Slicers
* Excel Formulas
* Data Cleaning
* Dashboard Design
* Data Analysis
