# Business-Case-Target-SQL

## 📌 Context

Target is a globally renowned brand and a prominent retailer in the United States. Known for outstanding value, innovation, and an exceptional guest experience, Target has made itself a preferred shopping destination.

This business case focuses on Target’s operations in **Brazil**, providing insights into **100,000 orders** placed between **2016 and 2018**. The dataset enables a deep dive into several aspects of the e-commerce business — including order processing, pricing, payment, shipping performance, customer demographics, product attributes, and satisfaction levels.

---

## 📂 Dataset

The dataset comprises the following 8 CSV files:

- `customers.csv`  
- `sellers.csv`  
- `order_items.csv`  
- `geolocation.csv`  
- `payments.csv`  
- `reviews.csv`  
- `orders.csv`  
- `products.csv`

---

## 🧠 Problem Statement

As a **Data Analyst/Scientist** at Target, your task is to analyze the dataset to extract **valuable insights** and provide **actionable recommendations** that help improve operations and customer experience.

---

## ✅ What Does ‘Good’ Look Like?

### 1. 📊 Exploratory Data Analysis (EDA)
- Determine data types of all columns in the `customers` table.
- Get the time range between which orders were placed.
- Count the number of unique cities and states from which customers placed orders.

### 2. 📈 Trend & Seasonality
- Identify trends in the number of orders over the years.
- Check for monthly seasonality in order placement.
- Analyze the time of day when orders are mostly placed:
  - **Dawn (00:00 - 06:00)**  
  - **Morning (07:00 - 12:00)**  
  - **Afternoon (13:00 - 18:00)**  
  - **Night (19:00 - 23:00)**

### 3. 🌍 E-commerce Evolution in Brazil
- Monthly order volume per state.
- Customer distribution across states.

### 4. 💰 Economic Impact
- Analyze money flow using `payment_value` in the `payments` table.
- % increase in order cost from Jan–Aug 2017 to Jan–Aug 2018.
- Total & average order value per state.
- Total & average freight cost per state.

### 5. 🚚 Delivery & Freight Analysis
- Compute delivery time:
  ```sql
  time_to_deliver = order_delivered_customer_date - order_purchase_timestamp

### 6. 💳 Payment Analysis
- Monthly order count by payment type.
- Order count based on number of payment installments.

### 🛠️ Tech Stack
SQL for querying and analysis
CSV files as the data source

### 📈 Outcome
By executing the above analyses, the project aims to:

Understand customer behavior and logistics performance.

Reveal key patterns in order timing, pricing, and delivery.

Identify areas for operational improvement and customer satisfaction enhancement in Brazil’s market.
