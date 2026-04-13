# Mobile Sales Performance Analytics (Mobile Bazar)

## Executive Summary
This project features a comprehensive, 360-degree sales analytics dashboard for **Mobile Bazar**, a fictional retail brand operating across various Indian cities. The dashboard transforms raw, fragmented sales data into an interactive visual reporting tool, enabling stakeholders to track a total revenue of **$769M**, monitor transaction volumes, and analyze customer sentiment in real-time.

---

## Business Problem & Objectives
Mobile Bazar management struggled with "Information Silos"—data was scattered across multiple Excel sheets, making it difficult to spot trends or regional underperformance.

**Key Objectives solved by this dashboard:**
* **Centralized Sales Tracking:** Consolidating regional performance (Delhi, Mumbai, etc.) into one view.
* **Trend Analysis:** Identifying seasonal spikes and monthly revenue dips.
* **Payment Method Optimization:** Analyzing the adoption of digital payments (UPI vs. Cards).
* **Customer Pulse:** Monitoring feedback to identify specific cities needing service improvements.

---

## Tech Stack & Methodology
* **Tool:** Power BI Desktop
* **Data Source:** Multi-table Excel/CSV (Sales, Customers, Transactions)
* **ETL Process:** Power Query (M Language) for data cleaning and normalization.
* **Data Modeling:** Star Schema implementation with structured Fact and Dimension tables.

### Technical Highlights (The "How")
* **Advanced ETL:** Unified disparate `Day`, `Month`, and `Year` columns into a single `Date` data type and standardized inconsistent text strings (e.g., converting "Sat" to "Saturday").
* **DAX Implementation:** Developed custom explicit measures including:
    * `Total Revenue` (using `SUMX` for row-level granularity).
    * `Transaction Volume` (using `COUNTROWS`).
    * `Average Unit Price`.
* **Dynamic UI/UX:** Applied a consistent **Navy Blue & White theme** with advanced formatting (shadow effects, rounded corners, and custom icons).

---

## Key Business Insights

| Category | Finding |
| :--- | :--- |
| **Revenue Leader** | **Apple** dominates the premium segment with a total sales value of **16.16 Cr**. |
| **Payment Trends** | **UPI** and **Debit Cards** are nearly equal (~26% each), indicating high digital payment adoption. |
| **Customer Pulse** | High concentration of **5-star ratings (1.49K)** suggests brand loyalty, while **0.31K 1-star ratings** pinpoint areas for service recovery. |
| **Regional Hubs** | Major sales activity is concentrated in **Western and Southern India**, highlighted via Map visualizations. |

---

## Dashboard Preview
[https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/dashboard_screenshot.png](https://github.com/Zaka98/Mobile-Sales-Performance-Analytics/blob/main/Snapshot%20of%20the%20Dashboard.PNG))
