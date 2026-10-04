# PowerBi_Sales_Analysis
# Sales Analysis Dashboards (Power BI)

A four-part Power BI project analysing internet sales for a retail business, built progressively from basic charts to an interactive multi-page dashboard.

## Data
- Sales data from the AdventureWorks sample dataset, loaded from Excel extracts via Power Query.
- Tables: `fact_InternetSales`, `dim_Customer`, `dim_Product`, `dim_Currency`, `dim_SalesTerritory`, `dim_Date`.
- Data preparation in Power Query: set column data types, removed unused columns, and created a customer `Username` field by extracting the text before "@" in the email address.

## Project Stages
| File | What it covers |
|---|---|
| `Task_Three.pbix` | Sales amount by currency and by month (date hierarchy), plus a pivot table of sales by currency and customer. |
| `Task_Four.pbix` | Sales by country with a country slicer, KPI cards, and a switch between number and percentage views using a disconnected table and DAX measures. |
| `Task_Five.pbix` | Single-page dashboard: sales by country, customer gender, and product colour (donut and bar charts), KPI cards for sales, customers, and products sold, and a Q&A visual. |
| `Task_Six.pbix` | Two-page dashboard with a currency selector, previous 1/3/6-month comparisons, a map, a timeline slicer, dynamic titles, and navigation buttons. |

## Key Features
- DAX measures for total sales, products sold, customers, % of sales, and sales for the selected currency.
- Month-over-month comparison measures (previous 1, 3, and 6 months).
- Dynamic titles that change with the selected filters.
- Interactive filtering with slicers, a timeline slicer, and a map.
- Custom visual (Timeline) imported from AppSource.

## Tools
Power BI Desktop, Power Query (M), DAX, Excel

## Key Insights
- [Add 2-3 findings with numbers, e.g., top country by sales, share of sales by gender]

## Screenshots
![Task Six dashboard](path/to/screenshot.png)
