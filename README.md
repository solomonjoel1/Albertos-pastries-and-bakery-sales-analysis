# Albertos-pastries-and-bakery-sales-analysis
Power BI Dashboard Project

An interactive Power BI dashboard that transforms raw data into clear, actionable insights through data cleaning, modeling, and visualization.

📊 Project Overview
This project covers the full Power BI workflow — from importing and cleaning raw data to building an interactive dashboard that allows users to explore trends by region, category, and time period.

🛠️ Tools Used
- Power BI Desktop
- Power Query (Data Cleaning & Transformation)
- DAX (Measures & Calculated Columns)
- Data Modeling

⚙️ Project Process

**1. Data Import & Cleaning**
- Imported raw dataset into Power BI
- Cleaned data in Power Query: removed duplicates, handled missing values, fixed data types, and standardized columns

**2. Data Modeling**
- Created relationships between tables
- Built a Date table for time-based analysis
- Optimized model for performance

**3. DAX Measures**
- Created key measures using DAX for totals, averages, growth, and comparisons
- Example: Total Sales by country, Total Profit by category, YoY Growth, Avgprofit by product

**4. Visualization & Dashboard Design**
Built an interactive, single-page dashboard with:
- **Slicers** – Filter by Region, Category, and Year
- **Maps** – Visualize performance by location / state
- **Stacked Column Charts** – Compare values across categories and time
- **KPI Cards** – Show total sales, profit, and key metrics at a glance
- **Line / Bar Charts** – Track trends over time
- **Gauge bars** – Track key measures across years

**5. Interactivity**
- Cross-filtering between visuals
- Dynamic filtering via slicers
- Custom canvas layout for a clean, scrollable report

**📈 Key Insights**

✅ Massive Growth: Performance grew from 65% of target in 2016 → 140% in 2019. We didn’t just hit target in 2018 (110%), 2019 hit the utmost peak in productivity.

✅ £46.88M Total Profit on £11.72M Total Cost with 13M units sold - a very healthy margin.

✅ 2017 was the Peak Profit Year - Profit spiked to over £9M, driven mainly by Food.

✅  Food generated £4.48M in Sales and 42.51% of all orders (4.25K orders), ahead of Pastries (38.43%) and Beverages (19.06%).

✅ USA is the #1 Market: USA alone contributed 560K units (18.67% of total quantity sold), followed by UK (444K – 14.8%) and Germany (375K – 12.5%).

 **Operations Insight**
 Order volume is highly seasonal – with sharp peaks in March, June, and December, and dips in February. This is key for stock and staffing planning.


1.**Profit is Concentrated – High Risk, High Reward**

USA is not just #1, it’s carrying the business.

USA = 560K units (18.67%), UK = 444K (14.8%), Germany/Australia = 375K (12.5%).

Top 3 countries = almost 46% of ALL quantity sold.

*Insight:* If USA has a supply issue, almost 1 in 5 sales is at risk. Operations needs a backup plan for USA.


**2. Food Sells More, But Pastries Order More Often**

Look at this mismatch:

-	*By Sales Value:* Food £4.48M > Beverages £4.05M > Pastries £3.00M

-	*By Number of Orders:* Food 42.51% (4.25K) > Pastries 38.43% (3.84K) > Beverages 19.06% (1.91K)




*Insight:* Pastries gets almost as many orders as Food, but makes much less money. That means Pastries orders are small / low-value. Operations opportunity: Bundle Pastries with Beverages to increase average order value.

**3. Beverages is the Efficiency Problem**

Beverages is only 19.06% of orders, but £4.05M in sales – almost as much as Food.

*Insight:* Beverages orders are few but HIGH value. This is your most efficient category. Don’t cut Beverages – push it more, because each order brings more money with less operational work.


**4. Cost Follows Profit – But Not Everywhere**

On  the “Total Profit and Total Cost by Country” chart, the profit line (yellow) stays well above the cost line for USA, Germany, UK, France.

But as you go to smaller countries on the right, the two lines get very close together.

*Insight:* Small markets are barely profitable. Cost to serve them is almost the same as the profit they bring. Operations should review delivery/logistics cost for the bottom 5 countries.



**5. Operations is Very Seasonal & Unstable**

The  “Count of Order ID and Average SalesQuantity by Month” line is very spiky.

-	Peaks in Month 3, 6, 8, 10, 12

-	Sharp drops in Month 2, 4, 7, 9, 11




*Insight:* This is not smooth demand. It’s stop-start. That means staffing, baking, and inventory planning is hard. You need to stock up before Month 3, 6, and 12 (your December peak), and reduce production in the dip months to avoid waste – especially important for a bakery with perishable products.



**6. Average Quantity Per Order Drops When Orders Spike**

When Order ID count spikes (dark line goes up), Average SalesQuantity (yellow line) often stays flat or drops.

*Insight:* During busy months, there is  MORE customers, but each customer buys LESS. That’s a classic operations bottleneck – maybe queues, stock-outs, or limited range. Fixing that could unlock a lot of profit in peak months.

**Operations takeaway**
The business is heavily dependent on the USA and on Food, Beverages are the most efficient category per order, and demand is highly seasonal with peaks in March, June and December. For a bakery, this means planning production and inventory around those peaks is critical to avoid waste and stock-outs.

📁 Files in this Repo
- `PowerBI_Dashboard.pbix` - Power BI file
- `data.csv` - Cleaned dataset
- `README.md` - Project documentation

🚀 How to View
1. Download the `.pbix` file
2. Open with Power BI Desktop
3. Use slicers to interact with the dashboard
