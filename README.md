# Sales Data Analysis — Power BI Dashboard

An interactive Power BI dashboard analyzing sales, profit, and promotion performance across products, cities, and time periods, built on a star-schema data model.

## Dashboard Preview

![Overview Page](https://github.com/whyash27/Sales-Data-Analysis-using-PowerBI/blob/main/Screenshot%202026-07-25%20224037.png)

<br><br>

![](https://github.com/whyash27/Sales-Data-Analysis-using-PowerBI/blob/main/Screenshot%202026-07-25%20224110.png)

<br><br>

![](https://github.com/whyash27/Sales-Data-Analysis-using-PowerBI/blob/main/Screenshot%202026-07-25%20224137.png)

<br><br>

![](https://github.com/whyash27/Sales-Data-Analysis-using-PowerBI/blob/main/Screenshot%202026-07-25%20224210.png)

<br><br>

![](https://github.com/whyash27/Sales-Data-Analysis-using-PowerBI/blob/main/Screenshot%202026-07-25%20224236.png)

## Report Pages

- **Overview** — Sales trends over time, profit vs. net sales correlation, average discount by promotion category, sales by city (map), and total order count
- **Top/Bottom 5 Analysis** — Top and bottom 5 products by sales, quantity sold, and profit
- **Comparison (Sales/Profit/Quantity)** — Side-by-side comparison of total sales, profit, and quantity sold with slicer-based filtering
- **Edit Interaction** — Demonstrates custom visual-to-visual interaction/highlighting behavior across charts
- **Table Visual** — Detailed transaction-level table with multi-field slicers for drill-down analysis

## Data Model

Star schema with the following tables:

- `Fact Table` — transaction-level sales data
- `Dim Customers` — customer details
- `Dim Product` — product details
- `Dim Promotion` — promotion/discount campaign details
- `Date Table 1` / `Date Table 2` — date dimensions
- `Measures Table` — centralized DAX measures

**Key measures:** Total Sales, Total Profit, Net Sales, Quantity Sold, Units Sold, Discount, Discount Percentage, Price Per Unit.

## Tools Used

- Power BI Desktop
- DAX for measure calculations
- Power Query for data transformation
- Custom dark theme for report styling

## How to Use

1. Clone or download this repository
2. Open `Sales_Data_Analysis.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Explore the pages using the tabs at the bottom of the report
4. Use slicers to filter by product, city, promotion, or date range


## File Structure

```
├── Sales_Data_Analysis.pbix   # Main Power BI report file
├── README.md                  # Project documentation
└── screenshots/                # Dashboard preview images (add before pushing)
```
