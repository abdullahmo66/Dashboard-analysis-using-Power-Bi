# 📊 Power BI Analysis Dashboard

This repository contains the **Analysis.pbix** Power BI dashboard,
designed to provide interactive insights across key business metrics.
The report helps users explore performance trends, identify
opportunities, and support decision‑making using clear visual analytics.

------------------------------------------------------------------------

## 🚀 Features

### **✔ Key Metrics**

-   Total Sales & Revenue\
-   Total Profit\
-   Quantity Sold\
-   Performance KPIs\
-   Trend Comparison (Monthly / Yearly)

### **✔ Visual Insights**

-   Sales & profit trends\
-   Comparison by product, customer, or region\
-   Interactive filters and slicers\
-   Top and bottom performer analysis\
-   Territory or category breakdowns (if included in model)

------------------------------------------------------------------------

## 🛠 Data Model

This Power BI report uses a **Star Schema** for optimized performance.

### **Fact Table**

-   Sales / Transactions (Amounts, profit, quantity, dates, IDs)

### **Dimension Tables**

-   Products\
-   Customers\
-   Dates\
-   Territories / Categories (based on dataset)

------------------------------------------------------------------------

## 📘 Example DAX Measures

    Total Sales = SUM(Sales[SalesAmount])

    Total Profit = SUM(Sales[Profit])

    Total Quantity = SUM(Sales[Quantity])

    Profit Margin = DIVIDE([Total Profit], [Total Sales])

------------------------------------------------------------------------

## 📂 File Contents

  -----------------------------------------------------------------------
  File                   Description
  ---------------------- ------------------------------------------------
  **Analysis.pbix**      Complete Power BI report with visuals, measures,
                         and data model

  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 📥 How to Use

1.  Download **Analysis.pbix**\
2.  Open using **Power BI Desktop**\
3.  Refresh the data source if needed\
4.  Explore visuals, KPIs, and filters to analyze performance

------------------------------------------------------------------------

## 🤝 Contributions

Feel free to open issues or suggest improvements.

------------------------------------------------------------------------

## 📄 License

This project is available under the **MIT License**.
