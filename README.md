# Sales Performance Analytics Dashboard

## 1. About the project
This project is a beginner Power BI exercise for exploring sales, profit, orders, product categories and regional performance.

## 2. Problem statement
A business may need a clear view of sales performance over time and across products and regions. This project provides the dataset preparation files, DAX measures and a build guide.

## 3. Features and planned visuals
- KPI cards for total sales, total profit, order count, average order value and profit margin.
- Monthly sales and profit trends.
- Sales by region and category.
- Top products.
- Date, region and category slicers.

## 4. Technologies used
Microsoft Power BI Desktop, Excel/CSV, Power Query and DAX.

## 5. Project folder structure
- `dataset/`: source and cleaned data instructions.
- `dax/`: measures to create in Power BI.
- `power_query/`: suggested cleaning steps and optional M example.
- `dashboard/`: page layout plan.
- `docs/`: beginner instructions and interpretation guidance.

## 6. How to obtain the dataset
Download the **Sample - Superstore** Excel workbook from Tableau's official sample data resources: https://www.tableau.com/learn/sample-data. Save the workbook as `dataset/Sample - Superstore.xls` or `.xlsx`. The exact workbook name may vary by download. This ZIP does not contain a copied dataset.

## 7. How to build in Power BI Desktop
1. Open Power BI Desktop.
2. Select **Get data → Excel** and choose the downloaded Superstore workbook.
3. Select the `Orders` sheet/table.
4. In Power Query, check data types, remove blank rows and confirm dates and numeric columns.
5. Select **Close & Apply**.
6. Create the measures in `dax/measures.dax`.
7. Build the visuals described in `dashboard/DASHBOARD_GUIDE.md`.
8. Add slicers for Order Date, Region and Category.
9. Save as `dashboard/Sales-Performance-Dashboard.pbix`.

## 8. How it works
Power Query is used to connect to and clean data before loading it. DAX measures calculate totals and ratios based on the current filter context. Slicers filter the visuals interactively.

## 9. Screenshots
No screenshots are included because a real Power BI report has not been rendered in this environment. Capture screenshots after you assemble the report in Power BI Desktop.

## 10. What I learned
Importing and cleaning data, choosing suitable visuals, writing DAX measures, and interpreting business metrics.

## 11. Limitations
A real `.pbix` file cannot be generated or validated in this environment. You must assemble and save the report in Power BI Desktop. The measures assume the common Sample Superstore field names; check your downloaded workbook and adjust names if needed.

## 12. Future improvements
Add year-over-year comparisons, drill-through pages, a date table and a product profitability view.

## 13. Dataset/API credits
Tableau Sample Data: https://www.tableau.com/learn/sample-data. Follow the source's current terms and attribution guidance.
