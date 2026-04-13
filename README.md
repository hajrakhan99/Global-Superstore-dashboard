# Global-Superstore-dashboard
Power BI dashboard for a Global Superstore dataset visualizing sales, profit, and order KPIs by product category — featuring bar, donut, line, stacked area charts, a KPI visual, and a category slicer.

# 🛒 Global Superstore Sales & Profit Analysis
 
> A single-page Power BI dashboard delivering at-a-glance insight into global store performance — tracking total sales, profit, and order volume broken down by product category with interactive filtering.
## 📊 Dashboard Overview
 
This `.pbix` file contains a single-page Power BI report titled **"Global Superstore Sales & Profit Analysis"**. It is designed to give business users a fast, interactive overview of store performance across product categories, supported by three headline KPI cards and five complementary chart types.
 
The report is built on a single `Orders` table and uses a custom background image with the CY24SU10 base theme for a polished, branded look.
 
---
 
## 📁 File Structure
 
| Component | Description |
|---|---|
| `GLOBAL_STORE_DASHBOARD.pbix` | Main Power BI report file |
| `Report/Layout` | Page definitions, visual configurations, and layout |
| `DataModel` | Embedded compressed data model (XPress9) |
| `DiagramLayout` | Data model relationship diagram layout |
| `Report/StaticResources/` | Background image (`.jfif`) and base theme (CY24SU10) |
 
---
 
## 📈 Visuals Included
 
| # | Visual Type | What It Shows |
|---|---|---|
| 1 | **Clustered Bar Chart** | Sales by Category |
| 2 | **Donut Chart** | Profit share by Category (Sales & Quantity as tooltips) |
| 3 | **Line Chart** | Profit trend by Category |
| 4 | **100% Stacked Area Chart** | Profit composition by Category (proportional view) |
| 5 | **KPI Visual** | Profit indicator with Category as trend axis |
| 6 | **Card — Total Sales** | Headline total sales figure |
| 7 | **Card — Total Profit** | Headline total profit figure |
| 8 | **Card — Total Orders** | Headline total order count |
| 9 | **Slicer** | Filter all visuals by Category |
| 10 | **Text Box** | Dashboard title |
| 11 | **Shape** | Decorative layout element |
 
---
 
## 🗃️ Dataset Fields
 
All visuals draw from a single `Orders` table with the following fields used in visuals:
 
### Columns
 
| Field | Description |
|---|---|
| `Category` | Product category (e.g., Furniture, Office Supplies, Technology) |
| `Sales` | Revenue value per order line |
| `Profit` | Profit value per order line |
| `Quantity` | Number of units per order line |
 
### DAX Measures
 
| Measure | Description |
|---|---|
| `TOTAL SALES` | Aggregated sum of all sales |
| `TOTAL PROFIT` | Aggregated sum of all profit |
| `TOTAL ORDERS` | Total count of orders |
 
> **Note:** The Global Superstore dataset typically also includes fields such as `Order ID`, `Order Date`, `Ship Mode`, `Customer Name`, `Segment`, `Country`, `City`, `State`, `Region`, `Sub-Category`, and `Discount` — these may be present in the embedded data model but are not currently used in report visuals.
 
---
 
## 🎨 Design & Theme
 
| Property | Detail |
|---|---|
| Background | Custom store-themed image (`download_(5).jfif`) |
| Base Theme | CY24SU10 (Power BI 2024 theme) |
| Card Style | Rounded rectangle with shadow and glow effects |
| Font | Cambria Math (KPI and card values) |
| Color Accent | Theme ColorId 9 used across cards and KPI visuals |
 
---
 
## 🛠️ Tools & Technologies
 
- **Power BI Desktop** — report authoring and data modelling
- **DAX** — custom measures (`TOTAL SALES`, `TOTAL PROFIT`, `TOTAL ORDERS`)
- **Power Query** — data ingestion and transformation
- **Dataset:** Global Superstore (commonly sourced from Kaggle or Tableau Sample Data)
 
---
 
## 🚀 How to Use
 
1. Download and open `GLOBAL_STORE_DASHBOARD.pbix` in **Power BI Desktop** (free from Microsoft).
2. The data model is fully embedded — no external data source or connection needed.
3. Use the **Category slicer** to filter all visuals simultaneously.
4. Hover over the **Donut Chart** for tooltip details on Sales and Quantity.
5. The **KPI visual** displays profit with a category trend line for quick performance assessment.
 
---
 
## 📋 Requirements
 
- **Power BI Desktop** (latest version recommended — uses CY24SU10 theme features)
- No external database, API, or file connection required
 
---
 
## 📂 Suggested Repository Structure
 
```
global-store-dashboard/
│
├── GLOBAL_STORE_DASHBOARD.pbix    # Main Power BI file
├── README.md                      # This file
└── assets/
    └── dashboard_preview.png      # (Optional) Screenshot of the dashboard
```
 
---
 
## 👤 Author
 
**Hajra Khan**
Created: February 2026 | Last updated: April 2026
