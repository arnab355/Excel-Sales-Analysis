# Excel-Sales-Analysis
An Excel sales analysis project featuring PivotTable reporting, data cleaning, Goal Seek, and Scenario Manager modeling.

# Excel Sales Analysis & What-If Analysis

This repository contains my completed Excel project analyzing regional sales performance. The goal of this project was to clean raw sales data, build an interactive PivotTable dashboard, and run What-If analysis models (Goal Seek and Scenario Manager) to support business decision-making.

---

## What's Inside

The main workbook (`module-3-pivot-analysis.xlsx`) consists of four core tabs:

1. **`Sales Data`**
   * Preprocessed and cleaned 20 transaction records.
   * Standardized date formatting issues using Text-to-Columns (DMY format).
   * Formatted currency and built standard calculated fields (`Quantity` × `Unit Price` = `Total Sales`).

2. **`Pivot Report`**
   * Built a structured PivotTable set to **Tabular Form**.
   * Grouped raw order dates naturally into a **Years** and **Months** hierarchy.
   * Sorted records in descending order by Total Sales ($123,690.00 total) to highlight top revenue drivers.
   * Added top-level drop-down filters and interactive visual **Slicers** for Region and Product.

3. **`Goal Seek Result`**
   * Ran a Goal Seek analysis on Row 5 (Akash's Mouse record).
   * Determined that selling **55.56 units** at $90/unit achieves the target sales revenue of **$5,000.00**.

4. **`Scenario Summary`**
   * Configured three business forecasting scenarios in Scenario Manager:
     * **Low Sales** (5 units @ $3,000 = $15,000)
     * **Medium Sales** (10 units @ $4,000 = $40,000)
     * **High Sales** (15 units @ $5,000 = $75,000)
   * Auto-generated a clean summary table comparing changing input variables against total sales outcomes.

---

## Tools & Excel Techniques Used

* **What-If Analysis:** Goal Seek, Scenario Manager, Scenario Summary Reports
* **Data Processing:** Text to Columns (Date parsing), Custom Formulas (`YEAR`, `TEXT`)
* **Reporting:** PivotTables, Tabular Layouts, Subtotals, Multi-field Sorting, Visual Slicers

---

## How to View the Project

1. Download or clone `module-3-pivot-analysis.xlsx` directly from this repository.
2. Open in Microsoft Excel (2016 or newer recommended) to interact with the Slicers and Scenario Manager directly.
