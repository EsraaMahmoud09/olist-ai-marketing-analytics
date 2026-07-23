# olist-ai-marketing-analytics
An enterprise-level AI-Powered Business Intelligence &amp; Marketing Analytics solution built with Power BI, SQL, Python, and DAX, featuring executive dashboards, customer segmentation (STP), sales forecasting, delivery performance analysis, and AI-driven strategic recommendations to support data-driven business decisions.

# Brazilian E-Commerce Dataset (Olist)

## Overview

This repository contains the **Brazilian E-Commerce Public Dataset by Olist**, one of the most widely used public datasets for Data Analytics, Business Intelligence, Machine Learning, and Marketing Analytics projects.

The dataset includes approximately **100,000 real e-commerce orders** placed between **2016 and 2018** across multiple online marketplaces in Brazil. It provides a comprehensive view of the customer journey, including customers, products, sellers, payments, deliveries, reviews, and geographic information. The data has been anonymized to protect customer privacy.

---

# Dataset Information

| Attribute        | Description                                           |
| ---------------- | ----------------------------------------------------- |
| Dataset Name     | Brazilian E-Commerce Public Dataset by Olist          |
| Domain           | E-Commerce                                            |
| Country          | Brazil                                                |
| Time Period      | 2016 – 2018                                           |
| Number of Orders | ~100,000                                              |
| License          | CC BY-NC-SA 4.0                                       |
| Source           | Kaggle - Brazilian E-Commerce Public Dataset by Olist |

---

# Repository Structure

```text
dataset/
│
├── customers.csv
├── orders.csv
├── order_items.csv
├── order_payments.csv
├── order_reviews.csv
├── products.csv
├── sellers.csv
├── geolocation.csv
├── product_category_name_translation.csv
└── README.md
```

---

# Dataset Tables

## Customers

Contains customer demographic and geographic information.

**Key Columns**

* customer_id
* customer_unique_id
* customer_city
* customer_state
* customer_zip_code_prefix

---

## Orders

Stores the complete order lifecycle.

**Key Columns**

* order_id
* customer_id
* order_status
* order_purchase_timestamp
* order_approved_at
* order_delivered_customer_date
* order_estimated_delivery_date

---

## Order Items

Contains all purchased products within each order.

**Key Columns**

* order_id
* order_item_id
* product_id
* seller_id
* shipping_limit_date
* price
* freight_value

---

## Order Payments

Contains payment information.

**Key Columns**

* order_id
* payment_type
* payment_installments
* payment_value

---

## Order Reviews

Contains customer satisfaction ratings and reviews.

**Key Columns**

* review_score
* review_comment_title
* review_comment_message
* review_creation_date

---

## Products

Contains product metadata.

**Key Columns**

* product_id
* product_category_name
* product_weight_g
* product_length_cm
* product_height_cm
* product_width_cm

---

## Sellers

Information about marketplace sellers.

**Key Columns**

* seller_id
* seller_city
* seller_state

---

## Geolocation

Maps Brazilian ZIP code prefixes to geographic coordinates.

**Key Columns**

* geolocation_zip_code_prefix
* geolocation_city
* geolocation_state
* latitude
* longitude

---

# Entity Relationship

```
Customers
    │
    ▼
Orders
    │
    ├─────────────┐
    ▼             ▼
Order Items   Order Payments
    │
    ▼
Products
    │
    ▼
Sellers

Orders
    │
    ▼
Order Reviews

Customers
    │
    ▼
Geolocation
```

---

# Business Use Cases

This dataset can be used for:

* Sales Performance Analysis
* Customer Segmentation
* Marketing Campaign Analysis
* Recommendation Systems
* Delivery Performance Analysis
* Inventory Analysis
* Customer Satisfaction Analysis
* Business Intelligence Dashboards
* Machine Learning Projects
* Marketing Analytics
* AI Agents for Decision Support

---

# Example KPIs

* Total Revenue
* Total Orders
* Average Order Value (AOV)
* Average Delivery Time
* On-Time Delivery Rate
* Repeat Purchase Rate
* Customer Retention Rate
* Review Score
* Revenue by State
* Revenue by Category
* Revenue by Seller
* Monthly Revenue Growth

---

# Technologies

This dataset is suitable for:

* Power BI
* Python
* Excel
* Machine Learning
* Deep Learning
* AI Agents
* Marketing Analytics
* Business Intelligence

---

# Source

Original Dataset:

Brazilian E-Commerce Public Dataset by Olist (Kaggle).
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

# License

This dataset is distributed under the **MIT License** license. Please refer to the original Kaggle dataset page for complete licensing information.

---

## About the Author

**Esraa Shawky**  
AI Engineer | Data Analyst | Business Intelligence Developer

📧 **Email:** esraashawky09@gmail.com  
💼 **LinkedIn:** www.linkedin.com/in/esraa-mahmoud22 
💻 **GitHub:** https://github.com/your-username

---

> **Developed for educational and portfolio purposes as part of the Novartis AI Internship Challenge.**

This project demonstrates an **AI Marketing Analytics & Decision Support System** built using **Power BI, GitHub, Google Gemini, and n8n** to analyze marketing performance, generate strategic recommendations, and automate executive reporting.


