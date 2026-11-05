# Sales Performance Analytics Dashboard

## 1. About the Project

This is one of my beginner projects where I explored sales data using Microsoft Power BI.

I wanted to understand how businesses can use data to track their sales, profits, orders, products, and regional performance.

I used the Sample Superstore dataset to explore the data, create useful calculations, and plan an interactive dashboard.

## 2. Why I Built This Project

I wanted to get some hands-on experience with data analytics instead of just learning the concepts.

I wanted to understand things like:
- How much a business is selling.
- How much profit it is making.
- Which products are performing well.
- Which regions generate more sales.
- How sales and profits change over time.

Basically, I wanted to turn raw sales data into something easier to understand.

## 3. What I Explored

While working on this project, I explored different ways to understand sales performance.

The dashboard includes plans for:

- **Total Sales:** See how much revenue the business generates.
- **Total Profit:** Understand how much profit the business makes.
- **Total Orders:** Track the number of customer orders.
- **Average Order Value:** Understand the average value of each order.
- **Profit Margin:** Check how much profit is earned compared to sales.
- **Monthly Trends:** Explore how sales and profits change over time.
- **Regional Performance:** Compare sales across different regions.
- **Product Performance:** Identify top-performing products.
- **Interactive Filters:** Filter the results by date, region, and category.

## 4. Technologies I Used

- **Microsoft Power BI Desktop** – To build and explore the dashboard.
- **Excel / CSV** – To work with the sales dataset.
- **Power Query** – To import, clean, and prepare the data.
- **DAX** – To create calculations and business metrics.

## 5. Project Structure

Here's how I organised the project files:

- `dataset/` – Dataset information and instructions.
- `dax/` – DAX measures used for calculations.
- `power_query/` – Data cleaning steps and Power Query examples.
- `dashboard/` – Dashboard design and layout guide.
- `docs/` – Instructions and notes to help build and understand the project.

## 6. Dataset

For this project, I used Tableau's Sample - Superstore dataset.

I downloaded the sample workbook from Tableau's official website:

[Download Sample Superstore Dataset](https://www.tableau.com/learn/sample-data)

After downloading, I placed the workbook inside the `dataset/` folder.

**Note:** The dataset is not included in this repository. You need to download it separately.

## 7. How to Run This Project

1. Download and install [Microsoft Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop).
2. Download the Sample - Superstore Excel workbook from Tableau.
3. Place the downloaded workbook inside the `dataset/` folder.
4. Open Power BI Desktop.
5. Select **Get Data → Excel Workbook**.
6. Select the downloaded Superstore workbook.
7. Choose the `Orders` sheet or table.
8. Open Power Query and check the data types, blank rows, dates, and numerical columns.
9. Select **Close & Apply** to load the data.
10. Open `dax/measures.dax` and create the required DAX measures.
11. Follow `dashboard/DASHBOARD_GUIDE.md` to build the dashboard.
12. Add interactive slicers for Order Date, Region, and Category.
13. Save your completed dashboard as `Sales-Performance-Dashboard.pbix` inside the `dashboard/` folder.

## 8. How It Works

I used Power Query to prepare the dataset before loading it into Power BI.

Then, I used DAX to calculate important sales metrics such as total sales, profit, order count, and profit margin.

The dashboard visuals help present these calculations in a more understandable way.

I also used slicers so users can filter the data and explore different parts of the business.

## 9. Screenshots

I'll add screenshots here after building the dashboard in Power BI Desktop.

## 10. What I Learned

This project helped me get familiar with the basics of data analytics and Power BI.

Here are some things I learned:

- How to import Excel datasets into Power BI.
- How to clean and prepare data using Power Query.
- How to create calculated measures using DAX.
- How to use KPI cards, charts, and other visualisations.
- How to analyse sales, profits, and product performance.
- How to use slicers to filter and explore data.
- How to turn raw data into meaningful business insights.

Most importantly, I started understanding how data analytics can help businesses make better decisions.

## 11. Current Limitations

- The dataset needs to be downloaded separately.
- The Power BI dashboard needs to be built and saved locally using Power BI Desktop.
- The actual dashboard screenshots will be added after completing the report.
- Some DAX column names may need adjustments depending on the downloaded dataset.

## 12. Future Improvements

There is still room to improve this project. Some things I'd like to explore next:

- Year-over-year sales comparisons.
- More detailed product profitability analysis.
- Drill-through pages for deeper analysis.
- A proper date table for time-based analysis.
- More interactive dashboard features.

## 13. Credits

**Dataset:** Tableau Sample - Superstore

Source: https://www.tableau.com/learn/sample-data

---

*Still learning, still exploring, and getting better with every project. 🚀*
