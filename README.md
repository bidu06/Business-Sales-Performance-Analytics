# Business-Sales-Performance-Analytics
E-Commerce Sales Analytics Dashboard built with Tableau | Future Interns Project
# 🛒 E-Commerce Sales Dashboard (2023–2024)

> **Interactive Tableau dashboard analyzing e-commerce sales performance across product categories, geographies, and time periods for 2023–2024.**

---

## 📊 Live Dashboard

👉 **[View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/bidusha.shrestha/viz/Ecommerce-Sales-Dashboard-Future-Interns/E-CommerceSalesDashboard2023-2024?publish=yes)**

---

## 📌 Project Overview

This project presents a comprehensive **E-Commerce Sales Analytics Dashboard** built using **Tableau**, covering transactional sales data for **January 2023 – December 2024**. It was developed as part of the **Future Interns** program to analyze key business metrics, uncover seasonal trends, identify top-performing products and markets, and deliver strategic recommendations.

---

## 🎯 Objectives

- Track total revenue, orders, customers, and units sold across 2023–2024
- Identify top-performing product categories and individual products
- Analyze geographic sales distribution across 10 countries
- Monitor monthly and quarterly revenue trends and year-over-year changes
- Deliver actionable business recommendations based on data findings

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Tableau Public** | Dashboard design & interactive visualization |
| **Microsoft Excel** | Data cleaning, analysis & KPI computation |
| **GitHub** | Project documentation & version control |

---

## 📂 Dataset

| Field | Details |
|-------|---------|
| **Source** | Online Retail Dataset — Kaggle / UCI Machine Learning Repository |
| **Period** | January 2023 – December 2024 |
| **Raw Records** | 4,066 transactions |
| **Cleaned Records** | 3,948 transactions (after removing nulls & returns) |
| **Key Columns** | InvoiceNo, StockCode, Description, Category, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, Revenue |

> 📁 Dataset is available in the [`/dataset`](./dataset/) folder.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value |
|--------|-------|
| 💰 **Total Revenue (2023–2024)** | £97,234 |
| 📦 **Total Orders** | 1,195 |
| 👥 **Unique Customers** | 1,124 |
| 🛍️ **Units Sold** | 31,421 |
| 💳 **Average Order Value (AOV)** | £81.37 |
| 📉 **Year-over-Year Revenue Change** | -2.7% (2023 → 2024) |

### Year-over-Year Breakdown

| Year | Revenue (£) | Orders | Customers | Units | AOV (£) |
|------|-------------|--------|-----------|-------|---------|
| 2023 | £49,290 | 582 | 564 | 15,931 | £84.69 |
| 2024 | £47,944 | 613 | 594 | 15,490 | £78.21 |

### Quarterly Revenue

| Quarter | 2023 (£) | 2024 (£) |
|---------|----------|----------|
| Q1 | £7,341.99 | £8,292.67 |
| Q2 | £10,917.42 | £12,001.23 |
| Q3 | £12,627.06 | £11,160.17 |
| Q4 | £18,403.66 | £16,489.78 |
| **Total** | **£49,290** | **£47,944** |

---

## 🏆 Top 5 Products by Revenue

| Rank | Product | Category | Revenue (£) | Units Sold |
|------|---------|----------|-------------|------------|
| 1 | Picnic Basket Wicker Large | Outdoor | £14,381.87 | 1,689 |
| 2 | Advent Calendar Gingham Sack | Seasonal | £8,698.54 | 1,753 |
| 3 | Party Bunting | Party Supplies | £7,859.65 | 1,588 |
| 4 | Hot Water Bottle Keep Calm | Novelty | £7,549.20 | 1,529 |
| 5 | Jam Making Set with Jars | Kitchenware | £6,428.30 | 1,515 |

---

## 📦 Revenue by Product Category

| Rank | Category | Revenue (£) | Revenue % | Orders | Units Sold |
|------|----------|-------------|-----------|--------|------------|
| 1 | Kitchenware | £18,817.36 | 19.4% | 446 | 4,553 |
| 2 | Outdoor | £14,381.87 | 14.8% | 191 | 1,689 |
| 3 | Seasonal | £13,052.50 | 13.4% | 334 | 3,233 |
| 4 | Home Decor | £12,690.86 | 13.1% | 574 | 6,482 |
| 5 | Novelty | £9,810.21 | 10.1% | 308 | 2,905 |
| 6 | Party Supplies | £9,206.90 | 9.5% | 345 | 3,177 |
| 7 | Bags | £8,912.73 | 9.2% | 499 | 4,949 |
| 8 | Craft | £5,506.10 | 5.7% | 169 | 1,476 |
| 9 | Kitchen | £4,855.45 | 5.0% | 315 | 2,957 |

---

## 🌍 Revenue by Country

| Rank | Country | Revenue (£) | Revenue % | Orders | AOV (£) |
|------|---------|-------------|-----------|--------|---------|
| 1 | United Kingdom | £71,873.17 | 73.9% | 895 | £80.31 |
| 2 | France | £5,980.37 | 6.2% | 60 | £99.67 |
| 3 | Germany | £5,652.19 | 5.8% | 75 | £75.36 |
| 4 | Netherlands | £5,309.47 | 5.5% | 51 | £104.11 |
| 5 | EIRE (Ireland) | £2,393.73 | 2.5% | 34 | £70.40 |
| 6 | Spain | £1,928.75 | 2.0% | 25 | £77.15 |
| 7 | Belgium | £1,696.76 | 1.7% | 23 | £73.77 |
| 8 | Portugal | £845.22 | 0.9% | 13 | £65.02 |
| 9 | Switzerland | £795.77 | 0.8% | 9 | £88.42 |
| 10 | Australia | £758.55 | 0.8% | 10 | £75.86 |

---

## 🔍 Key Insights & Findings

### 📈 1. Seasonal Demand Surge — November is the Biggest Month
- November revenue is **85–90% higher than the monthly average** due to holiday shopping demand
- The **Q4 period (Oct–Dec) accounts for approximately 38% of annual revenue** across both years
- November 2023 peaked at £7,372 and November 2024 at £5,768 — both far above the £3,000–£4,000 monthly average

### 🏆 2. Kitchenware & Home Decor Dominate Revenue
- Kitchenware (19.4%) and Home Decor (13.1%) together account for over **32% of total revenue**
- Kitchenware leads with £18,817 in revenue across 446 orders, with a consistent average unit price of £4.14
- The top 3 Kitchenware products alone (Jam Making Set, Regency Cakestand, Cake Tins) generated over £18,800

### 🌍 3. UK Market Concentration Risk
- **United Kingdom accounts for ~74% of all revenue (£71,873)** — a significant single-market dependency
- Germany, France, Netherlands, and EIRE are contributing organically without any targeted campaigns
- Netherlands has the **highest AOV at £104.11** — indicating premium buying behavior in that market

### 📉 4. Year-over-Year Slight Revenue Decline
- Revenue dipped **-2.7%** from 2023 (£49,290) to 2024 (£47,944), despite order count increasing by 5.3% (582 → 613)
- AOV dropped from £84.69 in 2023 to £78.21 in 2024 — suggesting smaller basket sizes or lower-priced product mix
- Q1 and Q2 improved year-over-year; the decline was driven by a weaker Q3 and Q4 in 2024

### ⚠️ 5. Product Returns — Recoverable Cost Drain
- Approximately **3% of all transaction lines are customer returns** (negative quantity invoices)
- Returns cluster in Party Supplies and Seasonal categories — likely due to size/expectation mismatch
- Reducing return rate from 3% to 1.5% could save approximately **£6K–£10K annually**

### 💡 6. B2B Wholesale — High AOV Untapped Segment
- Multiple invoices show bulk orders (50–200 units) indicating wholesale/trade buyers exist in the data
- B2B customers have **3–5× higher AOV** than retail and tend to place recurring orders
- Top 30 bulk-order customers represent a potential **£25K recurring revenue** opportunity if formally converted to B2B accounts

---

## 🚀 Strategic Recommendations

| # | Recommendation | Priority | Timeline | Expected Impact |
|---|---------------|----------|----------|-----------------|
| 1 | Seasonal inventory pre-build (Sep–Oct) | 🔴 HIGH | Q3 annually | +£20K–£40K Q4 revenue |
| 2 | EU market localisation & campaigns | 🔴 HIGH | 6 months | £40K–£70K new revenue |
| 3 | Expand Kitchenware & Home Decor SKUs | 🟡 MEDIUM | Q1 next year | +20% category revenue |
| 4 | Wholesale B2B portal launch | 🟡 MEDIUM | 9 months | £25K recurring revenue |
| 5 | Reduce product return rate to <1.5% | 🟡 MEDIUM | 3 months | Save £6K–£10K/year |
| 6 | Post-holiday Jan–Feb retention campaign | 🟢 LOW | Jan annually | Reduce Jan drop by 30% |

---

## 🖼️ Dashboard Preview

> 📸 *Add your Tableau dashboard screenshot here*

![E-Commerce Sales Dashboard](dashboard/dashboard_screenshot.png)

---

## 🗂️ Repository Structure

```
ecommerce-sales-dashboard/
│
├── README.md                        # Project documentation (this file)
├── dataset/
│   └── ecommerce_data.csv           # Cleaned dataset used for analysis
├── dashboard/
│   └── dashboard_screenshot.png     # Tableau dashboard screenshot
└── images/
    └── preview.png                  # README banner/preview image
```

---

## 🚀 How to View the Dashboard

1. Click the **[Live Dashboard Link](https://public.tableau.com/app/profile/bidusha.shrestha/viz/Ecommerce-Sales-Dashboard-Future-Interns/E-CommerceSalesDashboard2023-2024?publish=yes)** above
2. Use the **Year** filter to toggle between 2023 and 2024
3. Use **Category** and **Country** filters to drill down into specific segments
4. Hover over any chart element for detailed tooltips

---

## 👩‍💻 Author

**Bidusha Shrestha**
- 🌐 Tableau Public: [View Profile](https://public.tableau.com/app/profile/bidusha.shrestha)
- 💼 GitHub: *[Add your GitHub profile link]*
- 🏢 Program: Future Interns Internship 2024

---

## 🏷️ Topics

`tableau` `data-visualization` `ecommerce` `sales-analytics` `dashboard` `future-interns` `business-intelligence` `excel` `data-analysis` `retail-analytics`

---

⭐ *If you found this project useful, please consider giving it a star!*
