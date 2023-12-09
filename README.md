# Olist Power BI Sales Dashboard

![banner](/assets/Beige%20Black%20Modern%20Photo%20Collage%20Summer%20New%20Collection%20Banner.png)


## Authors

- [@adel3li](https://www.github.com/semasuka)

## Table of Contents

  - [Overview](#overview)
  - [Data source](#data-source)
  - [Methods](#methods)
  - [Tech Stack](#tech-stack)
  <!-- - [Quick glance at the results](#quick-glance-at-the-results)
  - [Lessons learned and recommendation](#lessons-learned-and-recommendation)
  - [Limitation and what can be improved](#limitation-and-what-can-be-improved)
  - [Run Locally](#run-locally)
  - [Explore the notebook](#explore-the-notebook)
  - [Deployment on streamlit](#deployment-on-streamlit) -->
  <!-- - [App deployed on Streamlit](#app-deployed-on-streamlit) -->
  <!-- - [Repository structure](#repository-structure) -->
  <!-- - [Contribution](#contribution) -->
   - [Dashboard](#dashboard)
  - [License](#license)


## Overview
This Power BI dashboard project provides a comprehensive sales analysis for an e-commerce platform in Brazil named Olist. The dashboard covers key metrics, monthly sales details, order status insights, and category-specific information. The project utilizes data from various datasets related to Olist's customers, orders, payments, geolocation, products, sellers, and reviews.


## Project Files

- **olist.pbix**: Power BI file containing the dashboard design and visualizations.
- **olist_customers_dataset.csv**: Dataset containing information about Olist customers.
- **olist_geolocation_dataset.csv**: Dataset with geolocation information.
- **olist_order_items_dataset.csv**: Dataset providing details about order items.
- **olist_order_payments_dataset.csv**: Dataset containing information about order payments.
- **olist_order_reviews_dataset.csv**: Dataset with order reviews data.
- **olist_orders_dataset.csv**: Dataset with overall order details.
- **olist_products_dataset.csv**: Dataset containing information about products.
- **olist_sellers_dataset.csv**: Dataset with details about Olist sellers.
- **product_category_name_translation.csv**: Dataset with translations for product category names.


## Dashboard

### 1. Total Sales Overview

<p align="center">
  <img src="/assets/shot1.gif" alt="shot1" width="800">
</p>
<p align="center">
  <img src="/assets/shot2.gif" alt="shot2" width="800">
</p>

- Total Sales
- Total Payments
- Monthly Sales
- Quarterly Sales
- Top 5 States

### 2. Monthly Sales Details

<p align="center">
  <img src="/assets/shot3.gif" alt="shot3" width="800">
</p>

- Top 3 Months
- Lowest 3 Months
- Top 10 Categories

### 3. Order Status Insights

<p align="center">
  <img src="/assets/shot4.gif" alt="shot4" width="800">
</p>

- Lowest 10 Status
- Top 5 Cities
- Top 5 Status

### 4. Categories and Top 10 Products

<p align="center">
  <img src="/assets/shot5.gif" alt="shot5" width="800">
</p>

- Top 10 Products
- Category-wise Analysis

## How to Use

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/adel3li/Olist-Dashboard.git


## MIT License

### Copyright (c) [2023] [Adel Ali]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.