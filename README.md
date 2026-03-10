# 🍷 Alco & Bev Sales Analytics Dashboard

An interactive **Business Intelligence solution** built in Power BI to monitor and analyze alcohol & beverage sales across multiple dimensions. The dashboard provides **executive-level KPIs** and **deep analytical insights** for operational teams to understand market performance, seasonal demand, and distribution strategies.

---

## 📌 Project Overview
The dashboard enables stakeholders to:
- Monitor overall sales performance  
- Identify top-performing brands and regions  
- Understand customer group contributions  
- Detect seasonal demand patterns  
- Analyze product packaging demand  
- Track geographic distribution of sales  

**Business Value:**  
Helps optimize inventory planning, marketing campaigns, regional distribution strategies, and product portfolio decisions.

---

## 🧰 Tech Stack
- **Power BI Desktop** → Interactive dashboard & visuals  
- **Power Query** → Data cleaning, transformation, and preparation  
- **DAX (Data Analysis Expressions)** → Measures & calculations  
- **Data Modeling** → Star Schema architecture for efficient filtering and performance  

---

## 🗄 Data Model
The project uses a **Star Schema architecture**, the most common modeling approach for analytical reporting systems.

### Structure
- **Fact Table** → `Fact Sales`  
- **Dimension Tables** → `Dim Product`, `Dim Customer`, `Dim Geography`, `Dim Calendar`  
- **Measures Table** → DAX calculations & KPIs  

![Data Model](https://github.com/user-attachments/assets/787fc499-b67d-40dd-b3f7-35f8731c25f6)

### Fact Table: `Fact Sales`
Contains transactional sales data.  
Key fields:
- `billing_date`, `invoice_date`, `created_date`  
- `invoice_quantity`, `bottles_quantity`  
- `price`, `net_value`, `trade_discount`  
- `customer_code`, `sku_code`, `btp_city`  

Acts as the central table connected to all dimensions.

### Dimension Tables
- **Dim Product** → Product details (`brand_description`, `product_hierarchy`, `sku`, `plant`, `unit_of_measure`)  
- **Dim Customer** → Customer info (`customer_code`, `customer_name`, `pricing_group_customer`)  
- **Dim Geography** → Location hierarchy (`city`, `state`, `region`, `country`, `zone`, `sales_officer`)  
- **Dim Calendar** → Date dimension (`Date`, `Month`, `Quarter`, `Year`, `Week Number`)  

### Measures Table
Contains all DAX measures, including:  
- `Total Sales`, `Total Revenue`, `Gross Sales`  
- `Discount %`, `Return %`  
- `Sales YTD`, `Sales PY`, `Sales YoY %`  
- `Average Order Price`, `ASP per Bottle`, `ASP per Case`

---

## ⭐ Features & Highlights

### Business Problem
Alcohol beverage companies generate massive transactional data across distributors, regions, brands, and packaging. Without analytics, it’s difficult to answer:
- Which regions generate the highest revenue?  
- Which brands perform best?  
- Which customer groups drive sales?  
- How do seasonal events affect demand?  
- Which product pack sizes sell the most?  

### Dashboard Goals
Provide an **interactive BI solution** to:
- Monitor KPIs  
- Identify high-performing brands & markets  
- Understand customer purchasing patterns  
- Detect seasonal sales trends  
- Optimize packaging demand  

---

## 📊 Walkthrough of Key Visuals

### KPI Overview
| KPI            | Value   | Description                          |
|----------------|---------|--------------------------------------|
| Total Sales    | ₹19bn   | Overall alcohol sales value           |
| Total Revenue  | ₹22bn   | Total revenue generated               |
| Total Orders   | 590bn   | Number of transactions                |
| Return %       | -0.01%  | Percentage of returned goods          |

---

### Top & Least Sold Products
- **Top Product:** Imperial Spirit Co. → Highest sales volume & revenue  
- **Least Sold Product:** CRGOLD 12x75 → Lowest performance  
- **Business Impact:** Inventory planning, promotions, pricing adjustments  

Includes slicers for **Country (India, Bhutan, Sri Lanka)**, **Region**, and **Year → Month** filters.  

---

### Sales by State (Map Visualization)
![Sales by State](https://github.com/user-attachments/assets/2c2f8fcc-f5a5-4968-964e-4d11bb801176)

---

### Monthly Sales Trend
![Monthly Sales Trend](https://github.com/user-attachments/assets/99e21740-b336-4de8-a4cb-b98e78c3fd1f)

---

### Order Volume by Customer Groups
![Order Volume](https://github.com/user-attachments/assets/ec7299c0-45e8-4ad7-a7fd-7d0ca8aa7ff7)

---

### Sales Breakdown by Case Size
![Case Size Breakdown](https://github.com/user-attachments/assets/8fa85924-8b0f-4bed-b0ad-a4f33826ee1c)

---

### Seasonal Revenue Analysis
![Seasonal Revenue](https://github.com/user-attachments/assets/90b7ad25-87bd-48cd-9644-ccbbc7146877)

---

### Brand-wise Sales Performance
![Brand Performance](https://github.com/user-attachments/assets/e4670b31-252c-4a3f-8b26-b21cc19437cd)

---

### Region-wise Sales Performance
![Region Performance](https://github.com/user-attachments/assets/7af4e2fb-a44d-472e-ba94-1652b517c312)

---

## 📈 Key Business Insights
- Wholesalers drive majority of sales  
- 24-bottle cases are most popular  
- Sales spike during festive seasons & holidays  
- COVID-19 lockdown caused major temporary drop  
- Few brands dominate overall revenue  
- Certain regions contribute significantly more than others  

---

## 📷 Dashboard Screenshots
![Main Dashboard](https://github.com/user-attachments/assets/4b3018d2-09e8-4e1a-a454-1ba103c91aba)

---

## 🚀 Conclusion
The **Alco & Bev Sales Dashboard** transforms raw transactional data into actionable insights, empowering organizations to make smarter decisions in inventory, marketing, and regional distribution.

---

## 📈 Final Insights
From this dashboard, several key insights emerge:
- Wholesalers drive the majority of alcohol sales.  
- 24-bottle cases are the most popular packaging format.  
- Sales increase significantly during festive seasons and holidays.  
- The COVID-19 lockdown caused a major temporary drop in revenue.  
- A few brands dominate the overall revenue contribution.  
- Certain regions contribute significantly more revenue than others.  
