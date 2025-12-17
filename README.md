
# 📊 Final Sales Analysis Dashboard - Global Superstore

![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## 📸 Dashboard Preview
![Dashboard Screenshot](dashboard_screenshot.png)
*(Note: Visuals are interactive. Download the .pbix file to explore.)*

## 📝 Project Overview
This project analyzes sales data from a global "Superstore" to identify business performance trends, profitability, and customer behavior. The goal was to transform raw sales data into a professional **Net Sales Performance Dashboard** that helps stakeholders make data-driven decisions.

**Key Focus:** Ensuring data accuracy by calculating **Net Sales** (excluding returned items) to provide a realistic view of revenue.

## ❓ Business Problem
The stakeholders wanted to understand:
1. **Real Revenue:** How much money are we actually making after refunds?
2. **Top Performers:** What are our best-selling products and categories?
3. **Trends:** When do sales peak during the year?
4. **Profitability:** Which regions have high sales but low profit margins?

## 🛠️ Tech Stack & Methods
*   **Tool:** Microsoft Power BI Desktop
*   **Data Source:** Excel/CSV (Orders, Returns, People tables)
*   **Data Transformation (Power Query):**
    *   Merged `Orders` and `Returns` tables to identify returned items.
    *   Cleaned data types and handled null values in the 'Return Status' column.
    *   Created a standard Date Hierarchy.
*   **Data Modeling:** Established One-to-Many relationships between tables (Star Schema).
*   **DAX Calculations:** Created measures for:
    *   `Total Revenue` (SUM)
    *   `Net Profit` (SUM)
    *   `Profit Margin %` (DIVIDE)
    *   `Returns Rate %`

## 📂 Data Source
I used the *Global Superstore* dataset for this project. You can access the raw files here:
*   📂 [Orders Table](./Dataset/Orders.csv)
*   📂 [Returns Table](./Dataset/Returns.csv)
*   📂 [People Table](./Dataset/People.csv)

## 🔍 Key Insights & Findings
1.  **Business Health:** The company generated **$2.12M in Net Revenue** with a **12% Profit Margin**.
2.  **Product Performance:** The *Canon imageCLASS* copier is the top revenue generator ($47.6K), significantly outperforming other items.
3.  **Category Trends:** **Technology** accounts for the largest share of sales (36%), followed by Furniture and Office Supplies.
4.  **Geographic Profitability:** While sales volume is high across the US, certain states show **negative profit margins** (indicated by red/orange bubbles on the map), suggesting operational inefficiencies in those regions.
5.  **Growth:** Revenue shows a consistent Year-over-Year growth trend, peaking in 2017.

## 📂 Project Structure
*   `FUTURE_DS_01.pbix` - The Power BI file containing the dashboard and data model.
*   `dashboard_screenshot.png` - Preview of the final report.
*   `Dataset/` - Folder containing the raw CSV files.

## 🚀 How to Use
1.  Download `FUTURE_DS_01.pbix`.
2.  Open the file in **Microsoft Power BI Desktop**.
3.  Interact with the slicers (Year, Region, Segment) to filter the data.
4.  Hover over charts to see custom tooltips with detailed metrics.

---
## 📬 Contact
Created by **B Kamachari** - Feel free to reach out!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/buragapalli-kamachari-931624269/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kamachariburagapalli@gmail.com)
