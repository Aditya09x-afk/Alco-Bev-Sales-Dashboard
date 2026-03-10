🍷 Alco & Bev Sales Analytics Dashboard

The dashboard provides both high-level KPIs for executives and deep analytical insights for operational teams to understand market performance, seasonal demand patterns, and distribution strategies.

📌 Project Overview

The Alco & Bev Sales Dashboard is a Business Intelligence solution designed to help organizations monitor and analyze alcohol sales data across multiple business dimensions.

The dashboard allows stakeholders to:

• Monitor overall sales performance
• Identify top-performing brands and regions
• Understand customer group contributions
• Detect seasonal demand patterns
• Analyze product packaging demand
• Track geographic distribution of sales

These insights help companies optimize:

Inventory planning

Marketing campaigns

Regional distribution strategies

Product portfolio decisions

🧰 Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop

Primary platform used for building the interactive dashboard and visuals.

📂 Power Query

Used for:

Data cleaning

Data transformation

Column restructuring

Preparing the dataset for analysis

🧠 DAX (Data Analysis Expressions)

Used to create measures and calculations such as:

Total Sales

Total Revenue

Discount %

Return %

Sales YTD

Sales PY

Year-over-Year Growth

Average Selling Price

🗄 Data Modeling

A Star Schema Data Model was implemented to improve query performance and enable efficient filtering across dimensions.

📁 File Formats

.pbix → Power BI dashboard file
.png → Dashboard preview screenshots for GitHub

🗄 Data Model

The project uses a Star Schema architecture, which is the most common modeling approach for analytical reporting systems.

The model contains:

<img width="1211" height="705" alt="Screenshot 2026-03-10 200242" src="https://github.com/user-attachments/assets/787fc499-b67d-40dd-b3f7-35f8731c25f6" />


⭐ Features & Dashboard Highlights
Business Problem

Alcohol beverage companies generate massive volumes of transactional sales data across:

distributors

regions

brands

product packaging

However, it is difficult to quickly answer important questions such as:

• Which regions generate the highest revenue?
• Which brands perform best?
• Which customer groups drive sales?
• How do seasonal events affect demand?
• Which product pack sizes sell the most?

Without analytics dashboards, these insights are difficult to derive from raw data.

Goal of the Dashboard

The goal of this dashboard is to provide an interactive Business Intelligence solution that enables stakeholders to:

• Monitor overall sales performance
• Identify high-performing brands and markets
• Understand customer purchasing patterns
• Detect seasonal sales trends
• Analyze product packaging demand

📊 Walkthrough of Key Visuals
KPI Overview

The dashboard begins with key performance indicators summarizing overall sales performance.

KPI	Value	Description
Total Sales	₹19bn	Overall alcohol sales value
Total Revenue	₹22bn	Total revenue generated
Total Orders	590bn	Total number of transactions
Return %	-0.01%	Percentage of returned goods

These KPIs provide a quick snapshot of business performance.

Top & Least Sold Products

This section highlights the best and worst performing products.

Top Product

Example: Imperial Spirit Co.

Insight:
This product generated the highest sales volume and revenue.

Business Impact:

Maintain strong inventory levels

Invest in marketing and promotions

Least Sold Product

Example: CRGOLD 12x75

Insight:
Lowest sales performance.

Business Impact:

Possible promotions

Pricing adjustments

Product lifecycle evaluation

Interactive Filters

The dashboard includes slicers that allow dynamic filtering.

Country Filter

Users can analyze performance across:

India

Bhutan

Sri Lanka

Region Filter

Allows comparison across internal sales regions.

Year → Month Filter

Allows users to explore time-based trends.

Total Sales by State (Map Visualization)

This geographic bubble map shows sales distribution across states.

Bubble Size = Sales volume.

Insights:

Southern and central states show strong demand.

Some states show lower penetration.

Business Value:

Optimize distribution networks

Identify emerging markets

Focus marketing in low-sales regions

Monthly Sales Trend

This bar chart visualizes monthly revenue trends.

Key observations:

Sales spike during December and January

Demand increases during festive seasons and weddings

Lower demand during regular working months

Business Impact:

Helps companies plan:

inventory

marketing campaigns

seasonal promotions

Order Volume by Customer Groups

This chart segments sales by customer type.

Customer groups include:

Wholesalers

Government

Private Distributors

Military

Insights:

Wholesalers

Largest contributors due to bulk purchasing.

Government

Institutional demand via state liquor distribution systems.

Military

Smallest demand segment.

Business Impact:

Supports optimization of sales channel strategies.

Sales Breakdown by Case Size

Donut chart showing demand for different packaging sizes.

Case sizes include:

24 bottles

12 bottles

48 bottles

Insights:

Case Size	Share
24 Bottle Case	42%
12 Bottle Case	39%
48 Bottle Case	18%

Business Impact:

Helps optimize packaging and production strategy.

Seasonal Revenue Analysis

A time-series chart showing daily revenue fluctuations.

Key observation:

Revenue dropped significantly during March–May 2020.

Reason:

COVID-19 lockdown caused closure of liquor stores and distribution interruptions.

Business Insight:

External events such as policy changes can significantly impact alcohol sales.

Brand-wise Sales Performance

This chart ranks brands based on total revenue.

Example brands include:

Highland Shot

Regal Legacy

Classic Fusion

Royal Drop

Grey Goose

Insights:

Top brands dominate revenue share, while lower-ranked brands may require marketing support.

Region-wise Sales Performance

Displays revenue distribution across regions.

Regions include:

CSD

North

East

West

South

BSF

HO

LHA

Insights:

CSD generates the highest revenue

North and East are strong markets

HO and LHA contribute minimal revenue

Business Impact:

Supports regional strategy optimization.

Drill-Through Analysis

The dashboard includes a drill-through page for deeper analysis of seasonal revenue patterns.

Features include:

Interactive drill-down

Expanded time-series analysis

Back navigation

This allows users to explore specific time periods and anomalies in sales performance.

📈 Key Business Insights

From this dashboard, several key insights emerge:

• Wholesalers drive the majority of alcohol sales.

• 24-bottle cases are the most popular packaging format.

• Sales increase significantly during festive seasons and holidays.

• The COVID-19 lockdown caused a major temporary drop in revenue.

• A few brands dominate the overall revenue contribution.

• Certain regions contribute significantly more revenue than others.

📷 Dashboard Screenshots
Main Dashboard
<img width="1289" height="727" alt="Snapshot of Dashboard" src="https://github.com/user-attachments/assets/4b3018d2-09e8-4e1a-a454-1ba103c91aba" />

Sales by State (Geographic Map)
<img width="940" height="660" alt="Screenshot 2026-03-10 195105" src="https://github.com/user-attachments/assets/2c2f8fcc-f5a5-4968-964e-4d11bb801176" />

Seasonal Revenue Analysis
<img width="1817" height="767" alt="Screenshot 2026-03-10 195237" src="https://github.com/user-attachments/assets/90b7ad25-87bd-48cd-9644-ccbbc7146877" />

Months Reflect Impact of New Year, Festivities & Holidays on Sales
<img width="1549" height="753" alt="image" src="https://github.com/user-attachments/assets/99e21740-b336-4de8-a4cb-b98e78c3fd1f" />

Order Volume by Top 4 Customer Group
<img width="1485" height="758" alt="image" src="https://github.com/user-attachments/assets/ec7299c0-45e8-4ad7-a7fd-7d0ca8aa7ff7" />

Sales Breakdown by Top 3 Case Sizes (BT)
<img width="1053" height="733" alt="image" src="https://github.com/user-attachments/assets/8fa85924-8b0f-4bed-b0ad-a4f33826ee1c" />

Brand-wise Sales Performance
<img width="1539" height="759" alt="image" src="https://github.com/user-attachments/assets/e4670b31-252c-4a3f-8b26-b21cc19437cd" />

Region-wise Sales Performance
<img width="1491" height="743" alt="image" src="https://github.com/user-attachments/assets/7af4e2fb-a44d-472e-ba94-1652b517c312" />
