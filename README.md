# 🍕 Pizza Sales Dashboard (Excel)

An interactive **Pizza Sales Dashboard** built in Microsoft Excel, using Pivot Tables and Pivot Charts to analyze sales performance and uncover key business insights. The results were also **cross-verified using SQL Server** to ensure data accuracy.

---

## 📌 Project Overview

This project analyzes a pizza restaurant's sales data to answer key business questions such as:
- What is the busiest day and time for orders?
- Which pizza category and size sell the most?
- Which pizza is the best-seller and which is the worst-seller?

The final output is a clean, interactive Excel dashboard supported by KPIs, Pivot Tables, and Pivot Charts.

---

## 🛠️ Tools Used

- **Microsoft Excel** – Data cleaning, KPIs, Pivot Tables, Pivot Charts, Dashboard design
- **Microsoft Word** – Documenting SQL queries used for validation
- **SQL Server (T-SQL)** – Running queries to cross-check and validate Excel results

---

## 🔄 Project Workflow

1. **Data Sorting & Filtering**
   Cleaned the raw dataset by sorting and filtering out inconsistencies, duplicates, and irrelevant records.

2. **KPI Calculation**
   Created key performance indicators (KPIs) to summarize overall sales performance, including:
   - Total Revenue
   - Total Orders
   - Total Pizzas Sold
   - Average Order Value

3. **Pivot Tables & Pivot Charts**
   Built Pivot Tables to summarize data by category, size, day, and time, then created corresponding Pivot Charts for visual analysis.

4. **Dashboard Design**
   Combined all KPIs, Pivot Tables, and Pivot Charts into a single, easy-to-read Excel dashboard.

5. **SQL Cross-Verification**
   Wrote SQL queries (documented in a Word file) and ran them in SQL Server to validate every insight generated in Excel, ensuring the dashboard numbers were accurate.

6. **Presentation**
   Summarized the full analysis — busiest day & time, sales by category & size, and best/worst selling pizzas — into a PowerPoint presentation (`Pizza_Sales_Analysis.pptx`) for easy sharing and review.
---

## 📊 Key Insights

- **Busiest Day & Time:** Identified the day of the week and time slot with the highest order volume.
- **Sales by Category:** Compared performance across pizza categories (e.g., Classic, Veggie, Chicken, Supreme).
- **Sales by Size:** Analyzed which pizza sizes (S, M, L, XL) contribute the most to revenue and order count.
- **Best-Selling Pizza:** Identified the top-performing pizza by quantity sold and revenue generated.
- **Worst-Selling Pizza:** Identified the lowest-performing pizza to flag for menu review.

---

## 📁 Repository Contents

| File | Description |
|------|--------------|
| `PIZZA_SALES_Dashboard.xlxs` | Excel file containing raw data, Pivot Tables, Pivot Charts, and final dashboard |
| `PIZZA_SALES_SQL_QUERIES.docx` | Word document containing all SQL queries used for cross-verification |
| `Dashboard_Image.png` | Dashboard preview images |
| `Pizza_Sales_Analysis.pptx` | PowerPoint summary of the dashboard analysis and key insights |

---

## 🖼️ Dashboard Preview

![Pizza Sales Dashboard](image/Dashboard_Image.png)

---

## ✅ Data Validation

All insights derived in Excel were cross-checked by writing equivalent SQL queries and executing them in **SQL Server**, confirming consistency between the Pivot Table results and the raw database records.

---

## 📬 Contact

If you have any questions or feedback about this project, feel free to reach out or open an issue in this repository.
