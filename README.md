# Amazon FBA P&L Financial Analysis

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Finance](https://img.shields.io/badge/Domain-Financial%20Analytics-0078D4?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-2ea44f?style=flat)

## Overview

A comprehensive Profit & Loss analysis built on **2,700+ real Amazon FBA transactions** spanning January 2025. This project models end-to-end financial performance for an Amazon seller — from raw order data through to net margin by SKU — across 8 structured analytical sheets.

This is not a textbook exercise. The dataset is drawn from live Amazon Seller Central settlement reports and models the actual financial mechanics of a multi-product FBA business.

---

## What's Inside

| Sheet | Description |
|-------|-------------|
| `Amazon` | Raw transaction ledger — 2,745 rows × 35 columns of order-level data |
| `ProductWise` | Revenue, COGS, refunds, gross profit, and net revenue broken down by product |
| `Logistics and Duty Charges` | FBA shipment tracking — units expected vs. located, fulfillment status |
| `Amazon Nov` | Month-specific order and settlement data |
| `P&L` | Consolidated profit & loss statement |
| `COGS` | Cost of goods sold modeling by product line |
| `Services` | Amazon service fees and platform cost breakdown |

---

## Key Analysis Performed

- **SKU-level profitability** — gross margin and net margin calculated per product across multiple categories (apparel, home goods)
- **Revenue vs. refund reconciliation** — tracking refund rate impact on net revenue
- **Logistics cost attribution** — FBA fulfillment fees, duty charges, and shipment discrepancy analysis
- **Service fee breakdown** — Amazon platform fees isolated from operational costs
- **Month-over-month settlement reconciliation** — matching settlement IDs to order-level transactions

---

## Skills Demonstrated

- Advanced Excel: PivotTables, VLOOKUP/XLOOKUP, dynamic cross-sheet formulas
- Financial modeling: P&L construction, COGS modeling, margin waterfall analysis
- Data cleaning: Reconciling raw settlement exports with structured financial outputs
- Business analytics: SKU-level attribution, refund impact analysis, fulfillment cost modeling

---

## Sample Insight

> Products in the apparel category (e.g., Brooklyntrend Men's Pearl Snap Shirts) showed high order volume but elevated refund rates — a margin compression pattern identifiable only through SKU-level P&L decomposition rather than aggregate revenue reporting.

---

## How to Use

1. Open `Amazon_Profit_and_Loss_Final_F.xlsx`
2. Start with the `P&L` sheet for the consolidated view
3. Drill into `ProductWise` for SKU-level margin detail
4. Cross-reference `Logistics and Duty Charges` to understand fulfillment cost drivers

---

## Tools Used

- Microsoft Excel (PivotTables, Solver, cross-sheet referencing)
- Amazon Seller Central (data source)
