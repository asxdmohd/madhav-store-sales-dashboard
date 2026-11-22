# Madhav Store – E-commerce Sales Dashboard (Power BI)

An interactive one-page Power BI dashboard that tracks and analyses a year of online sales (2018) for Madhav Store, an Indian e-commerce retailer.

## Dataset

| File | Rows | Contents |
|---|---|---|
| `Orders.csv` | 500 | Order ID, Order Date, Customer Name, State, City |
| `Details.csv` | 1,500 | Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode |

The two tables are related one-to-many on **Order ID**. Every order line matches an order.

## Dashboard

- **KPI cards:** Total Sales, Total Profit, Total Quantity and Average Order Value (a DAX measure)
- **Quarter slicer** that filters the whole page
- **Sales and profit by state** (bar chart)
- **Top customers by sales and profit** (column chart)
- **Monthly profit trend** (column chart)
- **Profit by sub-category** (bar chart)
- **Quantity by category and by payment mode** (donut charts)

## Key insights

- **₹4.38 lakh in sales and ₹36,963 in profit** for the year, an overall margin of about 8.4%, across 5,615 units sold.
- **Electronics leads on sales** (₹1.66 lakh), but **Clothing earns slightly more profit** (₹13.3k against ₹13.2k).
- **Maharashtra and Madhya Pradesh** are the two biggest markets, together about 43% of revenue.
- **Cash on delivery accounts for 46% of transactions**, ahead of UPI at 22%.
- **Profit is seasonal:** January–March and November are strong, while May, July, September and December are loss-making.

## Skills demonstrated

Data modelling (relationships between tables) · DAX measures · Interactive filtering with slicers · KPI design · Custom report theming

## How to open

1. Download `Madhav e comm.pbix`.
2. Open it in Power BI Desktop (free).
3. If prompted, point the data source to `Orders.csv` and `Details.csv`.

## Tools

Power BI Desktop · DAX · Power Query
