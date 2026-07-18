# Business Insights 360 📊

A dynamic Power BI dashboard built for **AtliQ Hardware**, giving Finance, Sales, Marketing, Supply Chain and Executive teams one connected, real-time source of truth for decision-making.

🔗 **Live dashboard:** https://app.powerbi.com/view?r=eyJrIjoiNjYyMmU2YzgtN2FlMi00NDVkLTkwOGEtNzE4Nzg5M2EwY2Q4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

---

##  Problem Statement

- AtliQ Hardware is a consumer electronics and computer hardware company with operations across multiple countries
- The business was growing rapidly, but data analysis still relied on scattered Excel files
- This gap became costly — the company suffered a major loss in Latin America due to a lack of data-backed decision-making
- Senior executives decided to invest in a dedicated data analytics project

##  Goal

- Build a Power BI solution connecting Finance, Sales, Marketing, Supply Chain and Executive stakeholders
- Replace disconnected spreadsheets with one shared, connected data model

##  About AtliQ Hardware

- **What it makes:** PCs, laptops, printers, mice and accessories
- **Where it sells:** India and worldwide
- **Sold through:** Croma, Amazon, Flipkart, Best Buy, Walmart, Staples
- **Go-to-market:** Retailer, Direct (AtliQ e-Store, AtliQ Exclusive) and Distributor channels
- **Product divisions:** PC · Peripherals & Accessories (P&A) · Networking & Storage (N&S)

##  Data Structure

- Built on a **snowflake schema** data model
- Dimension and fact tables structured for scalable, accurate reporting
- Data sourced via SQL

##  Tools Used

- Power BI Desktop
- SQL
- DAX
- Power Query
- DAX Studio (query optimization)

##  Key DAX Concepts Used

- `CALCULATE`
- `ALLEXCEPT`
- `ALL`
- `SWITCH`
- `HASONEVALUE` / `SELECTEDVALUE`

##  Approach

- **Scoping** — Defined project boundaries and identified what each stakeholder group needed to see
- **Data Preparation** — Used Power Query to clean data, build calculated columns, and reconcile mismatches
- **Data Modeling** — Built the snowflake schema and wrote DAX measures for dynamic titles and KPIs
- **Dashboard Design** — Built 9 report pages with role-based navigation
- **Performance Enhancement** — Used DAX Studio to analyze and optimize slower queries for faster load and rendering
- **Iteration** — Refined visuals, filters and P&L logic (Benchmark / Last Year / Target comparisons)

##  Report Pages

- **Home** — Navigation hub
- **Info** — Refresh cadence, data source notes
- **Finance View** — Full P&L, Net Sales, Gross Margin %, Net Profit % vs. Benchmark/LY/Target
- **Sales View** — Customer & product performance
- **Marketing View** — Segment & regional performance, GM% vs NS$ matrix
- **Supply Chain View** — Forecast Accuracy, Net Error, risk flags (Excess Inventory / Out of Stock)
- **Executive View** — Top-level KPI summary, revenue by division/channel, top 5 customers & products
- **Support** — FAQs, feedback, contingency plan

##  Key Insight

- Net Sales grew from **$111.37M (2019)** to a projected **$3.74bn (2022 EST)** — over 33x growth
- Net Profit % declined to **-13.98%** in the same period
- Revenue growth was masking a cost problem the raw sales numbers alone wouldn't reveal



---

**Author:** Kashish Arora
📧 arorakashish224@gmail.com
🔗 [linkedin.com/in/kashisharora12](https://linkedin.com/in/kashisharora12)
