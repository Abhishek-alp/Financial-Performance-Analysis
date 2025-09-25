### **Project: Financial Performance Analysis** 💰

---

### **Project Objective**

The objective of this project was to design and implement a **financial analytics solution** that delivers deep insights into the company’s profitability, sales performance, and market trends. Using a **Star Schema data model**, **Power Query**, and **Power Pivot**, I built dynamic reports such as **Profit & Loss (P&L) statements, Market vs. Target performance, and Customer Performance Reports**.

The solution transformed raw financial data into a **centralized, interactive reporting system** that empowered stakeholders with accurate, actionable insights.

---

### **Purpose & Importance**

This project plays a vital role in ensuring **financial transparency** and driving **data-driven decision-making**:

* **Monitor Profitability** – P&L statements provide clear visibility into revenues, costs, and margins across months, fiscal years, and markets.
* **Assess Performance** – Market and customer performance reports highlight top vs. underperforming areas.
* **Support Strategic Decisions** – Growth, margin, and target comparisons enable informed leadership decisions on pricing, resourcing, and market focus.
* **Ensure Data Integrity** – Power Query transformations (cleaning, standardization, handling negative values) ensured reliable financial reporting.

This shifted the organization from **reactive reporting** to **proactive strategy execution**.

---

### **Technical Skills**

**Tools & Technologies**

* Microsoft **Power Query**
* Microsoft **Power Pivot (Excel)**

**Data Engineering (Power Query)**

* Automated data extraction from multiple files in a folder (customer, market, product, sales).
* Cleaning and standardization: corrected headers, replaced invalid values, converted negatives to absolutes.
* Created a **custom `dim_date` table** using M-code and marked as a proper Date Table.

**Data Modeling (Power Pivot)**

* Built a **Star Schema** linking dimensions (`customer`, `market`, `product`, `dim_date`) to `fact_sales_monthly`.
* Implemented **fiscal year logic** (Sept–Aug) with custom FY quarters.

**DAX Measures**

* Aggregations: `Net Sales`, `Net Target`, `Manufacturing Cost`, `Freight Cost`.
* Growth metrics: `Sales Growth YoY`, `% Growth vs Target`.
* Advanced calculations: `COGS`, `Gross Margin %`, and profitability KPIs.

**Report Design**

* P&L reports, Market vs. Target dashboards, Customer Performance reports.
* Conditional formatting for highlighting growth and underperformance.

---

### **Soft Skills**

* **Solution Design** – Translated business problems into structured BI solutions.
* **Problem-Solving** – Created custom fiscal logic and a `dim_date` table from scratch.
* **Attention to Detail** – Ensured accuracy in DAX, transformations, and reporting logic.
* **Business Acumen** – Aligned analytics directly with financial KPIs and stakeholder needs.

---

📌 **Stakeholder Questions Answered**

* *What is the company’s Profit & Loss (P&L) performance across markets, customers, and fiscal years?*
  👉 [Insert Report Link]

* *Which markets and customers exceeded or fell short of their targets?*
  👉 [Insert Report Link]

* *What are the key drivers of Gross Margin % changes across quarters and sub-zones?*
  👉 [Insert Report Link]

* *How do sales trends and profitability vary across fiscal years (Sept–Aug)?*
  👉 [Insert Report Link]

* *Which customers are top contributors to revenue growth?*
  👉 [Insert Report Link]
