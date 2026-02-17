E-Commerce Sales & Operations Dashboard

This project is an end-to-end Power BI dashboard built to analyze e-commerce performance across sales, operations, customers, products, sellers, payments, and reviews.

The goal was to create a centralized analytical view that helps answer business questions related to revenue trends, operational efficiency, customer behavior, and service quality.

Why I Built This

E-commerce businesses generate large volumes of data, but insights are often scattered across different reports. I wanted to design a structured, KPI-driven dashboard that integrates transactional and operational data into one clear reporting layer.

Instead of focusing only on visuals, I emphasized:

Clean data modeling (star schema)

Proper relationship design

Efficient DAX measures

Performance-friendly calculations

Clear business storytelling

Data Model Overview

The model follows a star schema structure.

Fact tables:

Orders

Order Items

Payments

Reviews

Dimension tables:

Date

Customers

Products

Sellers

Relationships are primarily one-to-many with single-direction filtering to avoid ambiguity and maintain predictable behavior across visuals.

Key Metrics Implemented (DAX)

Some of the core measures include:

Total Revenue

Total Orders

Average Order Value (AOV)

On-Time Delivery %

Revenue per Customer

Revenue per Seller

5-Star Review %

All measures were built to dynamically respond to slicers and filter context.

Dashboard Coverage

The dashboard includes:

Executive Overview

Sales Performance Analysis

Delivery & Operations Monitoring

Customer & Revenue Insights

Product & Category Performance

Seller & Payment Analysis

Reviews & Ratings Insights

Key Takeaways

Revenue growth is primarily driven by order volume rather than AOV fluctuations.

Delivery performance has a visible impact on customer ratings.

Revenue concentration exists among top customers and sellers.

Payment behavior is dominated by credit-based transactions.

Tools Used

Power BI

DAX

Data Modeling (Star Schema)
