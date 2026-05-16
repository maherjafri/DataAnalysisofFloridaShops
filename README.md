# 🛍️ Florida Retail Chain — Sales Analytics Dashboard

An end-to-end data analytics project exploring how weather patterns and customer demographics drive daily sales across four retail locations in Florida.

---

## 📌 Project Overview

Four retail shops (Miami, Tampa, Jacksonville, and Orlando) experience significant day-to-day sales fluctuations. Store leadership lacked clarity on the root causes. This project identifies the key drivers — weather, seasonality, and customer mix — and surfaces them through an interactive Power BI dashboard to support better planning, staffing, and promotions.

---

## 🎯 Problem Statement

> *"Daily sales fluctuate, but leadership lacks clarity on why. Understanding how weather and customer demographics impact performance will provide insights to improve planning, staffing, and promotions."*

---

## 🗂️ Dataset

| Dataset | Description |
|---|---|
| Daily Sales Records | Transaction totals per store per day |
| Weather Data | Temperature and rainfall by location and date |
| Customer Survey Data | Demographics — gender, family/single status, visit patterns |

All three datasets were joined on **date** to create a unified analytical table.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **MySQL** | Database design and storage |
| **SQL** | Data joining, cleaning, and transformation |
| **ODBC SQL Connector** | Automated data pipeline into Power BI |
| **Power BI** | Dashboard development and visualization |

---

## ⚙️ Workflow

```
Raw Data (Sales + Weather + Survey)
        ↓
  Data Cleaning & Transformation
        ↓
   MySQL Database (Joined on Date)
        ↓
  ODBC SQL Connector → Power BI
        ↓
  Interactive Dashboard → Insights
```

1. **Collect & Clean** — Gathered daily sales, weather, and survey data; handled missing values and standardized formats
2. **Build Database** — Designed relational schema in MySQL and loaded all three datasets
3. **Join Datasets** — Unified records on date for cross-dataset analysis
4. **Connect to Power BI** — Used ODBC SQL Connector to load data directly into Power BI
5. **Build Dashboard** — Created interactive visuals for KPIs, trends, and demographic breakdowns
6. **Derive Insights** — Translated dashboard patterns into actionable business recommendations

---

## 📊 Dashboard Questions Answered

| Question | Finding |
|---|---|
| How strongly do temperature and rainfall affect daily sales? | Very strongly — temperature positively correlated, rainfall negatively correlated |
| Which shop performs best and why? | Miami — driven by tourism and favorable weather |
| Who are the customers, and how does the mix change over time? | Weekends attract more families; weekdays skew toward singles |
| Are there predictable seasonal patterns? | Yes — summer months consistently drove higher sales |
| What actions should management take? | See recommendations below |

---

## 💡 Key Insights & Recommendations

**Weather-Driven Strategy**
- Sales rise with temperature → stock up and increase staffing on warm days
- Rainy days suppress footfall → deploy targeted discounts to pull customers in

**Location Strategy**
- **Miami** is the top performer → prioritize expansion during peak tourism months
- **Jacksonville** underperforms → launch loyalty programs and local campaigns to build repeat visits

**Customer Targeting**
- **Weekends** → family-oriented promotions, bundle deals, larger cart sizes
- **Weekdays** → single-shopper campaigns, quick-purchase offers

---

## 📁 Repository Structure

```
├── Miami_Retail_Shop.pbix              # Power BI dashboard file
├── Data_Analysis_of_Florida_Retail_Shops.pptx   # Presentation deck
└── README.md                           # Project documentation
```

---

## 🚀 How to Use

1. Open `Miami_Retail_Shop.pbix` in **Power BI Desktop**
2. If prompted, update the data source connection to point to your local MySQL instance
3. Refresh the dataset to load the latest data
4. Explore the dashboard filters by location, date range, and customer segment

---

## 📬 Contact

Feel free to reach out for questions, feedback, or collaboration opportunities.
