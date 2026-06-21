# Powerbi
# Data Analytics Portfolio 📊

Welcome to my Power BI data analytics repository! This folder contains a collection of end-to-end business intelligence projects designed to transform raw transactional, operational, and retail data into clear, actionable business insights.

---

## 📂 Repository Structure

All project files are neatly organized inside the main `Powerbi` directory:

*   **`Powerbi/dashboards/`**: Houses the interactive source `.pbix` files.
    *   `NCR_Ride_Analytics.pbix` — Contains the 3-page interactive ride-hailing tracking system.
    *   `Salesdata.pbix` — Focuses on commercial revenue streams, seasonal sales trends, and product performance.
    *   `cafe.pbix` — Tracks operational metrics, item popularity, and order fulfillment dynamics for food & beverage retail.
    *   `pizza.pbix` — Analyzes specialized transaction details, peak order hours, and category sales velocity.
*   **`Powerbi/screenshots/`**: Visual interface captures showing the design layouts and core metrics for all 4 project views.

*Note: The raw datasets are compressed and fully embedded directly within the `.pbix` files, so you can explore the entire data model, relationships, and DAX measures immediately upon opening the files.*

---

## 🚗 Feature Project: NCR Ride Analytics Dashboard (Uber Simulation)

An end-to-end performance and supply-demand analysis simulating real-world operational bottlenecks in the National Capital Region (NCR).

### 📈 Core Operational Benchmarks
*   **Total Trips Tracked:** 102K
*   **Total Revenue Generated:** 52M
*   **Average Fare per Trip:** 508.30
*   **Average Customer Rating:** 4.40 / 5.00

### 🛠️ Key Analytical Features
*   **Executive Overview:** Tracks monthly booking trends to isolate critical seasonal demand spikes midway through the year. Includes dynamic slicing across vehicle classes (Auto, Mini, Sedan, eBike).
*   **Operational Deep-Dive:** Maps localized pickup density across the Delhi/NCR footprint, measures customer vs. vehicle turnaround metrics, and isolates friction points like customer demand drops vs. vehicle breakdown tracking.
*   **Customer Insights:** Uses Power Query ETL pipelines to clean data anomalies (such as transforming raw database `null` values into clean `"Completed Trip"` labels) and features a scatter matrix correlating customer value against star ratings.

---

## 💡 Key Technical Skills Applied Across All 4 Dashboards
*   **Data Refinement (Power Query):** Cleaning multi-table schemas, transforming data types, and resolving missing values/null parameters across various domains (Retail, Operations, and Mobility).
*   **Data Modeling & DAX:** Building clean relational models and crafting custom Data Analysis Expressions for dynamic time, sales, and segment metrics.
*   **UX/UI Design:** Building intuitive, scannable dark-themed dashboards prioritizing scannability and clear filtering hierarchies.
