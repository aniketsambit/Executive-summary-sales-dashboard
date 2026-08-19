# 📊 Executive Summary & Retail Sales Dashboard

A comprehensive **Power BI** end-to-end data analytics project designed to evaluate global retail performance, customer purchasing behavior, store-level operational metrics, and product category profitability.

---

## 📌 Project Overview & Objective

Retail executives often struggle to combine fragmented operational data into actionable business strategies. The primary goal of this project is to consolidate disparate transactional datasets—spanning customer profiles, store locations, product lines, and overall sales records—into a central, interactive **Power BI Dashboard**.

### Key Business Questions Addressed:
* **Sales Trends:** What are the total revenue, total profit margins, and sales volume trends across time?
* **Customer Demographics:** Who are the high-value customers, and how do purchasing behaviors vary across geographic regions?
* **Store Performance:** Which physical or digital store locations drive the highest profitability and sales efficiency?
* **Product Analytics:** What are the top-selling items, highest profit margin categories, and underperforming inventory lines?

---

## 🛠️ Tools, Technologies & Methodologies

* **Business Intelligence:** Power BI Desktop (Data Transformation, Interactive Visualizations, Executive KPIs)
* **Data Transformation & Preparation:** Power Query (Data cleaning, handling missing values, type casting)
* **Data Analytics & Calculations:** DAX (Data Analysis Expressions for custom KPIs, measures, and calculated columns)
* **Data Sources:** Microsoft Excel (`.xlsx` formatted datasets)
* **Data Modeling:** Star Schema (Central Fact Sales table connected via 1-to-Many relationships to Dimension tables: Customers, Products, Stores)

---

## 🔑 Key Features & Insights

* **Executive Dashboard:** High-level overview of revenue metrics, order fulfillment rates, and gross profit margins.
* **Customer Segment Analysis:** Geographical breakdown and purchasing frequency analysis across customer tiers.
* **Store Operational Metrics:** Side-by-side performance comparison across regional store locations and channel types.
* **Product Profitability Matrix:** Categorical breakdown identifying high-volume vs. high-margin products to optimize inventory stocking.

---

## 📊 Dashboard Preview

![Sales Performance Dashboard](./Dashboard.png)

---

## 📁 Repository Structure

```text
├── Customers.xlsx                      # Customer profiles, demographics, and regional data
├── Dashboard.png                       # High-resolution dashboard screenshot for preview
├── Executive Summary Dashboard.pbix    # Interactive Power BI report file
├── Products.xlsx                       # Product catalog, categories, and unit pricing
├── README.md                           # Documentation and project overview
├── Sales.xlsx                          # Order transactions, sales volume, and order dates
└── Stores.xlsx                         # Store locations, channel metadata, and region details
