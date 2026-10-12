# SuperMart Sales Analysis | MIS Project

An MIS (Management Information System) project built in **Microsoft Excel** using **Pivot Tables and Pivot Charts**. It analyses 2025 sales data for a fictional retailer, SuperMart, and answers three business requests from different stakeholders.

## Project Files

| File | Description |
|---|---|
| `SuperMart_Sales_Analysis_Project.xlsx` | The complete Excel workbook (data, pivot tables, charts, reports) |
| `README.md` | Project documentation (this file) |

## Dataset

- **Source sheet:** `Super-Market (Raw Data)`
- **Size:** about 420 orders, 2025
- **Columns:** Order ID, Order Date, City, Region, Category, Product, Qty Sold, Unit Price (Rs), Gross Amount (Rs), Discount %, Discount Amount (Rs), Net Sales (Rs), Sales Rep, Payment Mode, Customer Type
- **Regions:** North, South, East, West
- **Categories:** Apparel, Electronics, Groceries, Home & Kitchen, Personal Care
- **Payment modes:** Cash, Credit Card, Debit Card, Net Banking, UPI
- **Customer types:** Retail, Wholesale, Online

## The Three Tasks

### Task 1: Regional Sales Performance Report (`Sales Report` sheet)
**Requested by:** Regional Sales Head

- Region-wise and category-wise Net Sales (cross-tab pivot)
- Month-over-month Net Sales trend (line pivot chart)
- City-wise discount amount vs Net Sales
- Average order value by customer type
- Top 5 products by Net Sales

### Task 2: Payment Mode & Revenue Reconciliation (`Finance Report` sheet)
**Requested by:** Finance Team

- Order count and Net Sales by payment mode
- Gross amount vs discount amount by payment mode
- Region-wise Gross vs Net Sales with a calculated Discount % field
- Month-wise discount trend
- Payment mode vs customer type cross-tab
- Total discount leakage for the year

### Task 3: Sales Rep Performance & Incentive Review (`REP Performance` sheet)
**Requested by:** Sales Manager

- Net Sales and order count by sales rep (Top 3 and Bottom 3)
- Sales rep vs category cross-tab (each rep's strongest category)
- Average order value per rep
- Region/city coverage per rep
- Top 5 reps bar chart
- Incentive recommendation backed by data

The task briefs are also kept in the `Project To Do List` sheet of the workbook.

## Skills Demonstrated

- Pivot tables and pivot charts
- Calculated fields (Discount %)
- Cross-tab analysis
- Data sorting, ranking and Top-N filters
- Currency formatting (Rs #,##0)
- Turning data into business recommendations

## Key Findings

> Add your top insights here after you finalise the analysis, for example:
> - Highest-selling region and category: ...
> - Peak discount month: ...
> - Total discount leakage for the year: Rs ...
> - Recommended reps for incentive: ...

## How to Use

1. Download `SuperMart_Sales_Analysis_Project.xlsx`.
2. Open it in Microsoft Excel (pivot tables and charts work best in the desktop version).
3. Go through the sheets in this order: Raw Data, Sales Report, Finance Report, REP Performance.
4. To refresh the pivots after changing data, use **Data > Refresh All**.

## Tools

- Microsoft Excel (Pivot Tables, Pivot Charts)

## Author

**Your Name**
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)
