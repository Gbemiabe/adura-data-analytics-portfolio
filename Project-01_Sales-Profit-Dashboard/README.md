# Project 01 — Sales & Profit Dashboard (USD)

## Business Problem
Management wants a clear view of **sales performance and profitability**:
- Which months, regions, channels, and categories drive the most revenue?
- Which areas drive the most **profit** (not just revenue)?
- Where is profit leaking through **discounts, returns, fees, and fulfillment costs**?

## Data
**Grain:** 1 row = 1 order line  
**Period:** 2025 (Jan–Dec)  
**Currency:** USD (standardized for readability)

Key fields:
- Revenue: `gross_revenue_usd`, `discount_amount_usd`, `net_revenue_usd`
- Costs: `cogs_usd`, `shipping_fulfillment_usd`, `payment_fee_usd`, `return_amount_usd`
- Profit: `gross_profit_usd`, `net_profit_usd`
- Segments: `region`, `channel`, `category`, `product`, `customer_segment`

## KPIs
- Net Revenue, COGS, Gross Profit, Net Profit
- Gross Margin %, Net Margin %
- Orders, Average Order Value (AOV)
- Return Rate %
- Discount Spend, Fulfillment Spend

## Deliverables
- Executive Report (PDF): `outputs/adura_datahub_project1_report.pdf`
- Dashboard Workbook: `adura_datahub_project1_sales_profit_dashboard.xlsx`
- Dataset: `data/sales_profit_dataset_2025_usd.csv`
- Visuals: `outputs/*.png`

## Recommendations
1) Control discounts: prioritize high-margin, low-return products for promos.  
2) Reduce returns: review top-return SKUs and improve QA + product descriptions.  
3) Optimize fulfillment: monitor cost per order weekly and set thresholds.
