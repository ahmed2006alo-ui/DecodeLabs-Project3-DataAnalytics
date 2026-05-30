# Data Analytics — Project 3: SQL Data Analysis

**DecodeLabs Industrial Training | Batch 2026**

---

## Project Overview

This project is part of the DecodeLabs Data Analytics Industrial Training program.  
The goal is to use SQL queries to extract actionable business insights from an e-commerce orders dataset.

**Tool Used:** DB Browser for SQLite  
**Dataset:** E-Commerce Orders — 1,200 rows | 14 columns

---

## Dataset Columns

| Column | Type | Description |
|---|---|---|
| OrderID | Text | Unique order identifier |
| Date | Text | Order date |
| CustomerID | Text | Customer identifier |
| Product | Text | Product name |
| Quantity | Integer | Number of units ordered |
| UnitPrice | Float | Price per unit |
| ShippingAddress | Text | Delivery address |
| PaymentMethod | Text | Payment method used |
| OrderStatus | Text | Current order status |
| TrackingNumber | Text | Shipment tracking number |
| ItemsInCart | Integer | Number of items in cart |
| CouponCode | Text | Discount coupon applied |
| ReferralSource | Text | How the customer found the store |
| TotalPrice | Float | Total order value |

---

## SQL Queries Summary

| # | Query | Clauses Used |
|---|---|---|
| 1 | Preview Data | SELECT, LIMIT |
| 2 | Total Orders Count | SELECT, COUNT |
| 3 | Orders per Product | SELECT, COUNT, GROUP BY, ORDER BY |
| 4 | Total Revenue per Product | SELECT, SUM, GROUP BY, ORDER BY |
| 5 | Average Order Value per Product | SELECT, AVG, GROUP BY, ORDER BY |
| 6 | Orders by Status | SELECT, COUNT, GROUP BY, ORDER BY |
| 7 | Orders by Referral Source | SELECT, COUNT, GROUP BY, ORDER BY |
| 8 | Orders by Payment Method | SELECT, COUNT, GROUP BY, ORDER BY |
| 9 | Delivered Orders by Price | SELECT, WHERE, ORDER BY |
| 10 | High-Value Orders (Above 1000) | SELECT, WHERE, ORDER BY |

---

## Key Findings

- **Total Orders:** 1,200 orders analyzed
- **Top Product by Orders:** Printer (181 orders)
- **Top Product by Revenue:** Chair (195,620 EGP)
- **Highest Avg Order Value:** Laptop (1,110 EGP avg)
- **Most Used Payment Method:** Online (258 orders)
- **Top Referral Source:** Instagram (259 orders)
- **Most Common Order Status:** Cancelled (250) — high cancellation rate worth investigating
- **High-Value Orders (>1,000 EGP):** 512 orders = 42.6% of total

---

## Files

- `Project3_SQL_Analysis.docx` — Full report with all queries and screenshots
- `Dataset_Cleaned.xlsx` — Original cleaned dataset
- `data.csv` — CSV version used in DB Browser

---

*Completed by: Ahmad | Business Information Systems — Benha University*
