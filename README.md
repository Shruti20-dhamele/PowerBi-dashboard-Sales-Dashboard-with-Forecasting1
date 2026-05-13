
# Sales Performance Dashboard with Forecasting

I built this project in Power BI using the SuperStore retail dataset. The idea was simple — take raw sales data and turn it into something that actually makes sense visually. You should be able to open this dashboard and within seconds know which products are selling, which regions are doing well, and what the next 15 days might look like in terms of sales.

## What I did in this project

I started by importing the data from Excel, then cleaned it up using Power Query. There were some formatting issues with dates, a few inconsistencies in category names — the usual stuff you deal with in real data. Once the data was clean, I built the relationships between tables and started designing the dashboard.

I wrote DAX measures for things like year-over-year growth, running totals, and average delivery days. The forecasting part was honestly my favourite — I used Power BI's built-in time series forecasting to predict the next 15 days of sales based on historical patterns. It was interesting to see how the model picked up on seasonal trends automatically.

## What the dashboard shows

The first page is a complete sales overview — KPI cards at the top showing total revenue, profit, number of orders, and average delivery time. Below that there are charts breaking down sales by category, sub-category, region, and customer segment. There's also a map visual showing which states contribute the most sales.

The second page is purely the 15-day forecast — a line chart showing past sales alongside the predicted trend, with confidence intervals so you can see the range of expected values.

## Dataset

I used the SuperStore Sales Dataset which has around 2 years of real retail transaction data — order dates, shipping details, product categories, customer segments, sales figures, discounts, and profit. It's a solid dataset to work with because it reflects the kind of data you'd actually see in a retail business.

## Tech Stack

Power BI · DAX · Power Query · Excel · Time-Series Forecasting

## What I learned

This project taught me that cleaning data properly takes more time than building the dashboard itself — and that's actually fine. A dashboard is only as good as the data behind it. I also got much more comfortable with DAX after this project, especially time intelligence functions.

## About me

I'm Shruti, an M.Sc Computer Science student with a focus on data analytics and Power BI.
LinkedIn: https://linkedin.com/in/shruti-dhamele-63b025222
GitHub: https://github.com/Shruti20-dhamele
