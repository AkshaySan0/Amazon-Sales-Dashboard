# Amazon India Sales Dashboard

An interactive Excel dashboard analysing **10,000 e-commerce orders** across sales, profit, products, order status, payment methods, fulfilment types, and states in India.

## 🎯 Objective
Turn raw order data into a one-page view that helps answer:
- How much revenue and profit are we making, and where does it come from?
- Which categories, products, and states perform best?
- How much revenue is lost to returns and cancellations?
- Which payment methods and fulfilment types do customers use most?

## 📁 What's in the workbook

| Sheet | Contents |
|---|---|
| **Dashboard** | KPI cards and 6 charts: category and product performance, sales and profit trend, order status and revenue loss, payment performance, geographic performance, top products |
| **Analysis** | Summary tables that feed the dashboard charts |
| **Data** | 10,000 order records (order date, category, product, quantity, price, discount, sales, profit, payment method, fulfilment, status, ship state) |

**File:** `Amazon_India_Dashboard.xlsx` (download it and open it in Excel to see the charts and live formulas)

## 📊 Key findings

| Metric | Value |
|---|---|
| Total sales | ₹15.58 crore (₹155.8M) |
| Total profit | ₹3.32 crore, a **21.3%** margin |
| Total orders | 10,000 (24,926 units sold) |
| Average order value | ₹15,579 |
| Delivered orders | 81.5% |
| Returned / cancelled | 4.9% / 5.0% |

- **Electronics & Mobiles drives revenue:** about **79%** of total sales, far ahead of Home & Kitchen (₹1.80 crore).
- **Top states:** Maharashtra (₹2.96 crore), Karnataka (₹2.44 crore), and Delhi (₹2.24 crore) lead sales.
- **Top products by sales:** Laptop Backpack, Power Bank 20000mAh, and 5G Smartphone.
- **UPI is the most-used payment method**, at about 50% of sales, followed by Credit/Debit Card and Cash on Delivery.
- **Amazon FBA handles about 69% of sales**, ahead of Seller Flex and Merchant (FBM).
- **Revenue at risk:** returned and cancelled orders together account for about ₹1.56 crore, roughly **10% of total sales**.

## 🛠️ Tools & skills used
- Microsoft Excel: formulas (`SUM`, `COUNTA`, `COUNTIF`), summary tables, charts, and dashboard layout
- Data analysis: KPI design, category, geographic, and product analysis
- Data storytelling: presenting business metrics on a single page

## 📝 Notes
- Rates (delivered, returned, cancelled) use total orders as the denominator.
- Sales and profit are taken directly from the supplied data and include orders of all statuses.
- Dataset: practice dataset (edit this line to add the real source if you have one)

