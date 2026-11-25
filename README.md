# E Commerce Business Intelligence Platform

We used Excel, Python (Matplotlib), and Power BI to explore the same e-commerce dataset from January 2024 to December 2025. The project covers 2,000 orders from 492 distinct customers across four areas: sales, customers, products, and profitability.

## Power BI Dashboard Preview

![Power BI Home dashboard](./Power%20BI/Screenshots/Home.png)

## Matplotlib Dashboard Preview

![Matplotlib dashboard showing e-commerce sales, customers, products, and profitability](./Python%20Matplotlib/E_Commerce_Matplotlib_Dashboard.png)

## Excel Dashboard Preview

![Excel dashboard showing sales, customers, products, and profitability](./Excel/Final.png)

## Explore the project

| Version | What you can explore |
|---|---|
| [Excel](./Excel/) | Four dashboards cover sales, customers, products, and profitability. The final dashboard brings them together. |
| [Matplotlib](./Python%20Matplotlib/) | A single dashboard with 11 charts shows monthly sales and profit, top products, order status, and margins by sales channel. |
| [Power BI](./Power%20BI/) | The Home page gives an overview. Four interactive pages let you explore each area using filters and rankings. The Insights page explains the figures and highlights key findings. |

## Reading the sales figures

The Matplotlib dashboard shows ₹111.37 million in recorded net sales across all order statuses. The Power BI Delivered Sales card shows ₹72.27 million for delivered orders only. The order status filter explains the difference.

## Key Findings

- Maharashtra led all states with ₹20.3 million in recorded net sales, followed by Uttar Pradesh at ₹19.4 million.
- The Consumer segment accounted for 1,187 of 2,000 orders (59.4%).
- Of all orders, 65.7% were delivered, 17.5% were returned, and 16.8% were cancelled.

## Run the Python notebook

1. Download the repository. The `Python Matplotlib` folder contains the notebook and the [MySQL database export](./Python%20Matplotlib/ecommerce_database.sql).
2. In MySQL Workbench, open **Server → Data Import**, select **Import from Self-Contained File**, choose `ecommerce_database.sql`, and click **Start Import**.
3. Open the `.ipynb` file in Jupyter. The connection cell uses `localhost`, port `3306`, and the database `e_commerce_business_intelligence_platform_v4`. Update the MySQL username if yours differs from `root`.
4. Run the cells in order and enter your own MySQL password when prompted.
