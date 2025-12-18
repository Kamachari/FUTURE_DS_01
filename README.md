
# 📊 Final Sales Analysis Dashboard - Global Superstore

![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## 📸 Dashboard Preview
![Dashboard Screenshot](dashboard_screenshot.png)
*(Note: Visuals are interactive. Download the .pbix file to explore.)*

## 📝 Project Overview
This project analyzes sales data from a global "Superstore" to identify business performance trends, profitability, and customer behavior. The goal was to transform raw sales data into a professional **Net Sales Performance Dashboard** that helps stakeholders make data-driven decisions.

**Key Focus:** Ensuring data accuracy by calculating **Net Sales** (excluding returned items) to provide a realistic view of revenue.

## 📄 Project Documentation
*   **[Download Full Executive Report (PDF)](./Global%20Superstore%20Analysis.pdf)** - A detailed breakdown of findings and strategies.
  
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

## 📊 Business Insights
### 1. Growth & Seasonality
*   **Trend:** The business is trending upward, with **2017 being the peak performance year**.
*   **Seasonality:** Sales consistently spike in **Q4 (Nov-Dec)**, driven by holiday demand.
*   **Action:** Inventory planning needs to account for a 30-40% surge in demand during these months to prevent stockouts.

### 2. Product Performance
*   **The "Hero" Product:** The *Canon imageCLASS Copier* is the #1 revenue driver ($47.6K).
*   **Category Analysis:** **Technology** generates the highest sales (36%) and healthy margins. Conversely, **Furniture** drives volume but suffers from low margins due to high shipping costs.

### 3. Geographic Profitability ("The Red Bubble" Issue)
*   **Observation:** While sales volume is high in states like **Texas, Ohio, and Pennsylvania**, these regions are generating **negative profit**.
*   **Hypothesis:** High shipping costs for bulky items or excessive local discounts are eating into margins.

---

## 💡 Strategic Recommendations
Based on the analysis, I recommend the following actions to improve profitability:

1.  **🛑 Stop the Bleeding in Unprofitable Regions:**
    *   Review shipping policies for Texas and Ohio. Consider removing "Free Shipping" for heavy furniture items in these specific zones to restore positive margins.

2.  **📦 Q4 Inventory Optimization:**
    *   Increase stock levels of Top 10 Technology products by October to maximize revenue during the holiday rush.

3.  **↩️ Reduce Returns Impact:**
    *   With $180K in lost revenue due to returns, implement a feedback loop with the warehouse to check for packaging improvements on frequently returned items.

## 📂 Project Structure
*   `FUTURE_DS_01.pbix` - The Power BI file containing the dashboard and data model.
*   `dashboard_screenshot.png` - Preview of the final report.
*   `Dataset/` - Folder containing the raw CSV files.

## 📂 Data Source
I used the *Global Superstore* dataset for this project. You can access the raw files here:
*   📂 [Orders Table](./Dataset/Orders.csv)
*   📂 [Returns Table](./Dataset/Returns.csv)
*   📂 [People Table](./Dataset/People.csv)

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
