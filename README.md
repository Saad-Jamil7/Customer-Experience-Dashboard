# Customer-Experience-Dashboard

# E-Commerce Executive Suite: Customer Experience & Operations Dashboard

An advanced, interactive 3-page Power BI dashboard designed to provide enterprise-level business intelligence for a global E-Commerce organization. This project transforms complex relational customer transaction, engagement, and service logs into a unified, dark-mode analytic application optimized for executive decision-making (CFO, CMO, and COO).

## 📊 Dashboard Overview & Live Architecture

The suite features a robust **Human-Computer Interaction (HCI)** grid layout, utilizing custom dark-mode UI aesthetics to minimize visual fatigue while maximizing data contrast.

### Page 1: Executive Overview
*   **Target Audience:** CEO / CFO / Strategy Leads
*   **Core Metrics:** Total Revenue ($7.83M), Churn Rate (15.32%), Lifetime Value ($18.54M), Total Customer Count (15K).
*   **Key Visualizations:** 
    *   *Total Revenue by Month:* High-density line chart mapping macroscopic seasonal financial trends.
    *   *Revenue & Churn by Subscription Type:* Dual-axis combo chart cross-examining financial intake against user attrition metrics.
    *   *Revenue by Payment Method:* Donut chart highlighting transactional channel distributions.

### Page 2: Marketing & User Acquisition
*   **Target Audience:** CMO / Growth Marketing Managers
*   **Core Metrics:** Marketing Spend, Average Order Value (AOV), Email Open Rates, and Email Click-Through Rates (CTR).
*   **Key Visualizations:**
    *   *App Engagement vs. Spending:* Deep exploratory scatter plot analyzing the correlation between a user's average session duration and their total monetary output.
    *   *Acquisition Channel Performance:* High-impact horizontal bar chart isolating top-performing marketing funnels.

### Page 3: Operation & Customer Health
*   **Target Audience:** COO / Customer Success Director
*   **Core Metrics:** Average Customer Satisfaction (Avg CSAT), Net Promoter Score (NPS), Total Support Ticket Volume, and Average Delivery Delay Days.
*   **Key Visualizations:**
    *   *Regional Operational Breakdown:* Custom matrix table mapping City-level performance with integrated conditional formatting heatmap data bars.
    *   *NPS Distribution:* Radial gauge chart tracking organizational customer loyalty against targeted boundaries.
    *   *Support Tickets & Delays by CSAT:* Secondary-axis clustered column and line visual proving the statistical impact of shipping/logistics delays on low-tier CSAT evaluations.

---

## 🛠️ Tech Stack & Engineering Pipeline

*   **Business Intelligence & Visualization:** Power BI Desktop
*   **Data Transformation & ETL:** Power Query (M Language) utilizing advanced column parsing, data type normalization, and semantic cleanup.
*   **Data Modeling:** Relational Star Schema framework.
*   **UI/UX Framework:** Custom asset container layout with high-contrast font sheets (Segoe UI Semibold/Arial) to ensure strict accessibility compliance.

---

## 💡 Key Analytical Insights Delivered

1.  **Logistical Friction Drives Churn:** The operational analysis on Page 3 demonstrates a definitive mathematical correlation between average delivery delays exceeding a 3-day threshold and sharp spikes in 1-star to 2-star CSAT ratings, directly feeding back into the macro churn patterns surfaced on Page 1.
2.  **Subscription Tier Resilience:** While annual subscription tiers carry a lower macroscopic churn footprint, monthly subscription tiers exhibit higher overall immediate revenue generation velocity, advising a strategic pivot toward blended marketing promotions.
3.  **Engagement Elasticity:** Scatter analysis indicates diminishing monetary returns on user session duration past a specific time ceiling, allowing product development teams to refocus app optimizations on conversion speed rather than infinite scrolling mechanics.

---

## 🚀 How to Open and Interact

1.  Clone this repository to your local machine:
```bash
    git clone [https://github.com/YOUR_USERNAME/Ecommerce-Customer-Experience-Dashboard.git](https://github.com/YOUR_USERNAME/Ecommerce-Customer-Experience-Dashboard.git)
    ```
2.  Ensure you have **Power BI Desktop** installed (latest version recommended).
3.  Open the `.pbix` file: `Sales.pbix`.
4.  Use the persistent **Right-Hand Filter Panel** to segment data dynamically across `Country`, `Device`, `Acquisition Channel`, and `Subscription Type` to test cross-page cross-filtering capabilities.

---

## 🧑‍💻 Author
*   **Data Analyst Portfolio**
*   **Specialization:** SQL | Power BI | Advanced Data Visualization | Python EDA
