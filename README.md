# 🏦 Mitron Bank — Customer Spending Analysis for a New Credit Card (Power BI)

A market-analysis project for **Mitron Bank**, which is planning to launch a new credit card. This dashboard analyses customer demographics and spending behaviour to recommend **who to target** and **what card features** will drive adoption.

## 📌 Business Problem
Mitron Bank wants to enter the credit-card market. Before launch they need to understand their customers' spending patterns across categories, payment types, age groups, occupations and cities, and identify the most profitable target segments.

## 🛠️ Tools & Tech
- **Power BI** (Power Query, data modeling, DAX measures)
- Data modeling with a star schema (`dim_customers` + `fact_spends`)

## 📊 Key Analysis
- Spending by **category**, **payment type**, **city**, **occupation** and **age group**
- Income vs. spend behaviour and potential card-adoption segments
- Recommendations on target customers and card features

## 🗂️ Repository Structure
```
├── dashboard/        # Power BI dashboard (.pbix)
├── data/             # dim_customers.csv, a sample of fact_spends, and the data dictionary
└── docs/             # Problem statement
```
> **Note on data:** `fact_spends` is large, so a **1,000-row sample** is included here to illustrate the schema. Column definitions are in `data/data_dictionary.txt`.

## ▶️ How to View
Open `dashboard/Mitron_Bank_Dashboard.pbix` in **Power BI Desktop**.

## 🔑 Key Skills Demonstrated
Data modeling (star schema) · DAX · Customer segmentation · Power BI dashboarding · Business storytelling

---
*Project completed as part of the Codebasics data analytics resume challenge.*
