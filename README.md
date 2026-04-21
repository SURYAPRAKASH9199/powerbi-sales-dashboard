# Sales Performance Dashboard — Power BI Capstone Project

## Student Details
| Field | Details |
|-------|---------|
| **Name** | SURYA PRAKASH |
| **Roll Number** | 2306236 |
| **Batch / Program** | B.Tech (Information Technology) |
| **Submission Date** | April 21, 2026 |

## Project Overview
An interactive Power BI dashboard built on a retail sales dataset (Jan–Dec 2024) with 56 transaction records. It provides dynamic KPI summaries, regional sales comparison, category-wise profit analysis, and product performance tables — all controlled by interactive slicers.

## Key Findings
- **Total Sales:** INR 16M across all regions
- **Total Profit:** INR 3M (Profit Margin ~19%)
- **Top Region:** South — INR 5M in sales
- **Top Product:** Mobile Phone — INR 4.97M in sales
- **Electronics vs Furniture:** Electronics contributes 83%+ of profit in every region

## Project Structure
```
PowerBI_Project/
├── dataset/
│   └── sales_data.csv          ← Source dataset (56 records)
├── Sales_Dashboard.pbix        ← Power BI dashboard file
├── Project_Documentation.pdf   ← Full project report (5 pages)
├── HOW_TO_CREATE_PBIX.txt      ← Step-by-step Power BI guide
└── README.md                   ← This file
```

## Dashboard Features
- **KPI Cards** — Total Sales, Total Profit, Units Sold, Unit Price Sum
- **Regional Bar Chart** — North / South / East / West comparison
- **Year-wise Sales Chart** — 2024 reference trend
- **Category Donut Chart** — Electronics vs Furniture profit split
- **Product Performance Table** — Units, Sales & Profit per product
- **Interactive Region Slicer** — Filters all visuals simultaneously

## Tech Stack
| Component | Tool |
|-----------|------|
| Visualization | Microsoft Power BI Desktop |
| Data Source | CSV / Excel |
| Calculations | DAX (Data Analysis Expressions) |
| ETL | Power Query (M Language) |

## How to Run
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Open `Sales_Dashboard.pbix`
3. If prompted, update the data source path to `dataset/sales_data.csv`
4. Use the Region slicer to explore regional performance

## Dataset Columns
`Order_ID | Date | Product | Category | Region | Salesperson | Units_Sold | Unit_Price | Total_Sales | Profit | Customer_Name`
