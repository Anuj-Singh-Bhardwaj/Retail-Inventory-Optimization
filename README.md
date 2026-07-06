# Retail Inventory Optimization: From $22.6M Waste to Supplier Contract Renegotiation

## 📌 Project Overview

This project analyzes 10,000+ inventory records from a multi-chain supermarket to identify systemic inventory overstock and spoilage. The analysis uncovered **$22.6M in inventory waste**, with **5 suppliers driving 60% of spoilage** (Meat & Dairy categories highest).

**Business Impact:** A 30% order reduction for high-risk categories and supplier contract renegotiation could unlock **$3.4M in annual savings**.

## 🎯 Business Problem

A mid-sized supermarket chain was losing money from perishable goods expiring on shelves. The initial assumption was a balance between spoilage and stockouts, but analysis revealed **zero stockouts** across all stores—the real problem was systemic over-ordering.

## 🔍 Key Questions Answered

- Which products, categories, and stores are driving the most waste?
- Which suppliers are consistently underperforming?
- What specific actions can store managers take TODAY to stop the bleeding?

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning & feature engineering |
| Python (Matplotlib, Seaborn) | Exploratory Data Analysis |
| Power BI (DAX) | Interactive dashboard & KPI tracking |
| Excel | Data validation & quick analysis |

## 📊 Key Metrics Engineered

| Metric | Definition | Formula |
|--------|------------|---------|
| Days_Unsold | How long a product has been sitting without sale | Today - LastSoldDate |
| Spoilage_Threshold | Category-specific shelf life (5 days for Dairy, 365 for Cleaning) | Category-based mapping |
| Spoilage_Cost | Financial loss from expired products | Spoilage_Units × Cost_Price |
| Opportunity Cost | True financial impact (waste + lost profits from stockouts) | Spoilage_Cost + Stockout_Cost |

## 💡 Key Insights

1. **60% of all SKUs** are already past their shelf life
2. **5 suppliers** are responsible for 60% of total spoilage
3. **Meat & Dairy** are the highest-risk categories
4. **Stockouts are zero**—the chain is massively over-ordering

## 📋 Recommendations

1. **Reduce orders** for Meat & Dairy by 30% across all stores
2. **Renegotiate contracts** with top 5 suppliers to include penalty clauses for early expiry
3. **Implement weekly review** using the Power BI dashboard

## 📊 Dashboard Preview

### Page 1: Executive Summary
![Executive Summary](Visualisation/page1_executive_summary.png)

### Page 2: Daily Action Workbench
![Action Workbench](Visualisation/page2_action_workbench.png)

### Page 3: Supplier Deep Dive
![Supplier Deep Dive](Visualisation/page3_supplier_deepdive.png)

## 📁 Repository Structure
