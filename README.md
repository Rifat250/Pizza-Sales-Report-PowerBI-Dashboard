🍕 __Pizza Sales Performance Analysis Dashboardhboard | Power BI__

1️⃣ __Title__

Pizza Sales Performance & Business Insights Dashboard 

2️⃣ __Executive Summary__

📌 __Business Problem__

The business needed a comprehensive analysis of pizza sales performance to understand revenue trends, customer ordering behavior, product popularity, and underperforming items. Management lacked a centralized dashboard to track KPIs and identify actionable insights.

💡 __Solution__

An interactive Power BI dashboard was developed to:
* Track key performance indicators (KPIs)
* Analyze daily and monthly sales trends
* Identify best and worst performing pizzas
* Understand category and size contribution to revenue
* Enable dynamic filtering by pizza category, size, and month

The dashboard integrates a structured data model with calculated DAX measures and dynamic visualizations to support real-time decision-making.

📊 __Number Impact__
* Total Revenue: $817.86K
* Total Orders: 21.35K
* Total Pizzas Sold: 49.57K
* Average Order Value: $38.31
* Average Pizzas per Order: 2.32

📍 __Key insights__:
* Orders peak on Thursday and Friday
* Highest monthly sales observed in May and July
* Classic category drives maximum revenue and orders
* Large size pizzas contribute highest sales percentage
* Thai Chicken Pizza generates the highest revenue
* Brie Carre Pizza is the most underperforming product

3️⃣ __Business Problem (Scenario Explanation)__

The pizza company operates across multiple categories and sizes but lacked visibility into:

* Which products generate the most revenue?
* Which pizzas are underperforming?
* What days and months experience peak demand?
* How customer ordering behavior impacts revenue?
* What size and category combinations drive profitability?

Without structured analytics, management could not:
* Optimize inventory
* Adjust marketing strategies
* Remove or promote specific pizzas
* Plan staffing for rush days

The dashboard visualizes:
* 📅 Daily order trends
* 📆 Monthly sales patterns
* 🍕 Category & size contribution
* 🏆 Top 5 best sellers
* ⚠️ Bottom 5 worst sellers

This enables data-driven decision-making rather than assumptions.

4️⃣ __Methodology__

🔷 __Data Modeling__
* Created a Star Schema Model
* Fact Table: pizza_sales
* Dimension Table: Calendar Table
* Dedicated _Measure Table for clean DAX organization
* Established one-to-many relationship between Calendar and Sales

🔷 __KPI Calculations (DAX)__

Key Measures:
* Total Revenue = SUM(total_price)
* Total Orders = DISTINCTCOUNT(order_id)
* Total Pizzas Sold = SUM(quantity)
* Average Order Value = Total Revenue / Total Orders
* Average Pizzas per Order = Total Pizzas Sold / Total Orders

🔷 __Analytical Approach__
* Trend Analysis (Daily & Monthly patterns)
* Category Contribution Analysis
* Size Preference Analysis
* Product Performance Ranking
* Comparative Analysis (Top vs Bottom Performers)

I designed and built the dashboard entirely in Power BI, focusing on:
* Clean visual storytelling
* KPI-driven layout
* Interactive slicers
* Business-focused insights

4️⃣ __Skills Used__
* Data Modeling (Star Schema)
* DAX Measures & Calculations
* Time Intelligence
* Slicers & Filters
* KPI Cards
* Bar Charts & Line Charts
* Donut & Pie Charts
* Funnel Chart
* Ranking (Top N / Bottom N logic)

6️⃣ __Results & Business Recommendations__

📊 __Key Findings__
1. Revenue is highly concentrated in the Classic category.
2. Large pizzas drive the largest percentage of sales.
3. Sales peak on Thursday & Friday, suggesting weekend demand preparation.
4. Thai Chicken Pizza is the strongest revenue contributor.
5. Brie Carre Pizza consistently underperforms across revenue, quantity, and orders.
6. Customers order an average of 2.32 pizzas per order, indicating bundle potential.

🚀 __Business Recommendations__
1. __Inventory Optimization__

Increase stock of top-performing pizzas (Thai Chicken, Classic Deluxe).

2. Marketing Strategy
* Promote underperforming pizzas through discounts.
* Create combo deals to increase average pizzas per order.

3. Operational Planning
* Increase staffing on Thursdays and Fridays.
* Prepare inventory for peak months (May & July).

4. Menu Engineering
* Consider reformulating or replacing the Brie Carre Pizza.
* Highlight best sellers in promotional campaigns.

5. Upselling Strategy

Since customers order 2.32 pizzas per order, introduce:
* Family bundles
* Size upgrades
* Add-on offers

📂 __Files__
* Power BI file (.pbix)
* Dashboard screenshots
* Data model diagram

👤 Author

Maksud-Ur-Rashid

Data Analyst | EXCEL | SQL | POWER BI | PYTHON
