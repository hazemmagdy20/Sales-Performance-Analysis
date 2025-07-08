# Sales-Performance-Analysis

✅ What the Dashboard Does ?

This dashboard analyzes sales performance, discounts, returns, and profitability trends over multiple years.
It was built using Power Query for data cleaning, Power Pivot for modeling, and Excel for interactive charts and KPIs.
It helps managers and analysts understand the impact of discounts, identify top-performing products, segments, and regions, and monitor returns rates.

❓ Key Questions Answered

📌 Which year and quarter achieved the highest sales and profit?

📌 Which products, categories, segments, cities, and states drive the most revenue?

📌 How do discounts affect profit margins? At what point do they turn negative?

📌 What percentage of orders come back as returns, and which products have the highest returns?

📌 Where are lowest sales and lowest profits happening?

📌 What are net sales, net cost, net profit, and return rates at a glance?

⚙️ How to Open It

The dashboard is an Excel file (.xlsx).

Open it with Microsoft Excel — Power Query and Pivot Tables are used, so make sure you have a version that supports Power Pivot (Excel 2016 or newer recommended).

Enable macros & data connections if prompted.

Use the slicers, filters, and visuals to explore insights interactively.

📌 Highlights from the Insights

✔️ 2017 has the highest total sales ($564,299), especially in Q4 ($222,871).

✔️ 2016 has the highest profit ($79,183), especially in Q4 ($37,531).

✔️ Q1 2014 shows the lowest sales ($55,437) and profit ($3,687).

✔️ Discounts above 30% can wipe out profit margins.

✔️ Net profit margin is around 14.47% after costs & discounts.

✔️ 5.91% of orders are returned.

✔️ Top customer segment: Consumer.

✔️ Top product: Canon imageCLASS 2200 Advanced Copier.

✔️ Top category: Technology.

✔️ Top region (sales): East; Top region (profit): West.

✔️ Top city: New York City; Top state: California.


🧹 How the Data Was Prepared
Cleaned with Power Query: header fixes, date parsing, splitting location fields, and creating calculated columns (discounted value, sales after discount, cost).

Modeled as a star schema:

Fact table: Orders

Dimension tables: Returns, People, Shipping Cost

New measures were created for Net Sales, Net Cost, Net Profit, etc.

📸 Screenshots

![Dashboard ](https://github.com/user-attachments/assets/917c2f72-edee-40ae-9537-8c8afa2ec0fd)

🚀 How to Use
1️⃣ Open the .xlsx file.
2️⃣ Check the slicers for year, quarter, region, segment, city and category.
3️⃣ Use the cards for key KPIs: Net Sales, Net Profit, Return Rate, Total Orders sold, Total customers, etc.
4️⃣ Use interactive charts for trends by time, region, product, and category.


