# AdventureWorks-bike-sales-BI-dashboard
## overview
This Power BI project delivers comprehensive business insights across customer behaviour, product performance, regional sales trends, and profitability analysis for Adventure Works, a fictional retail company. By combining interactive dashboards with KPI modelling and visual storytelling, the project spans multiple dimensions over a two year(2020-2022) period and supports strategic decision making with actionable data. Through this work, I translated raw datasets into meaningful insights and strategic recommendations helping the business fine-tune its pricing, inventory, and market focus.
## 🎯objective

1. **Customer Revenue & Segmentation**
   - Analyze how income levels and occupations impact purchasing behavior
   - Identify high-value segments for targeted campaigns  
   💼 *Skills:* Customer profiling, segmentation, lifetime value analysis

2. **Product Performance**
   - Evaluate sales, profitability, and return trends
   - Guide inventory planning and quality control  
   💼 *Skills:* Product analytics, KPI tracking, return rate modeling

3. **Regional Sales Performance**
   - Compare global sales across regions
   - Support geo-targeted marketing initiatives  
   💼 *Skills:* Geo-analysis, regional segmentation, interactive reporting

4. **Mountain Tire Tube KPI Simulation**
   - Dynamic performance simulation of a single product
   - Model pricing decisions and profitability impact  
   💼 *Skills:* Pricing strategy, forecast simulation, scenario modeling

---
## 📁 Data Tables Description

1. 👥 Customer Detail
    Fields: CustomerID, Name, Age, Gender, Location, Income  
    Purpose: Enables customer segmentation and behaviour analysis based on demographics and region.
2. 💰 sales details
    Fields: OrderID, OrderDate, CustomerID, ProductID, Quantity, Unit Price, Total Amount, ReturnID, ReturnReason, Return Rate, Return Date  
    Purpose: Helps track sales performance, purchase patterns, and high-demand periods. Identifies product issues and customer dissatisfaction trends to reduce losses.
3. 🛍️ Product Detail
    Fields: ProductID, ProductName, Category, Type, Unit Price  
    Purpose: Supports evaluation of product profitability and category-level contributions.     
5. 🗺️ Territory Detail
    Fields: TerritoryID, Territory Name, Region  
    Purpose: Allows geographic sales analysis and targeted regional strategy development.

## 🚀 Use Cases

- Customer segmentation and profiling  
- Sales forecasting and revenue analysis  
- Product trend identification  
- Return rate investigation  
- Regional performance insights  

---

## 🔗 Entity Relationship Diagram (ERD)

  This Power BI project uses a star-schema relational data model designed for scalable retail analytics across Adventure Works. The ERD visualizes how core business entities like customers, orders, products, and returns are interconnected to support segmentation, profitability tracking, and geographic performance analysis.
  
 ### 🔗 Key Relationships Explained
- Customers → Orders (1:M): Each customer can place multiple orders, allowing analysis of purchasing behaviour and lifetime value.
- Orders → Products (M:1): Orders link directly to individual products, enabling performance and return rate insights.
- Orders → Territory → Regions (M:1 → M:1): Orders flow through defined territories and regions to support market segmentation and global sales tracking.
- Orders → Calendar (M:1): Enables time-based trends such as monthly revenue, seasonal performance, and YOY comparisons.
- Orders → Returns (1:1): Returns are tracked per order to monitor customer satisfaction and product quality.
- Products → Subcategory → Category (M:1 → M:1): Products are hierarchically grouped for granular performance tracking and visual drill-throughs.

### 📊 Purpose of the ERD
 ✅ Clarifies the structure of data powering Power BI dashboards
 ✅ Highlights the logical flow from dimensional tables to the fact table
 ✅ Demonstrates scalable design suitable for cross-domain insights
This ERD serves as the foundation for building dynamic dashboards on customer revenue segmentation, product performance, regional sales distribution, and return trends—all powered by structured and reliable data modelling.

<img width="1610" height="952" alt="Screenshot 2025-07-13 165959" src="https://github.com/user-attachments/assets/2aa3924e-bef2-4fda-a83c-b4767e39034d" />


---

## 📊 Performance Summary – AdventureWorks Bike Shop(2020–2022)

### 👥 Customer & Revenue Insights 
Between **2020 and 2022**, AdventureWorks maintained a strong customer base, totalling **17,400** unique customers. These customers generated an average of **$1,430** per person in revenue. However, there was a noticeable decline in per-customer revenue across this period, indicating the need to re-engage customers through loyalty initiatives or review pricing strategies.

### 🔹 Income-Level Purchase Behaviour
- Middle-income customers were the most active, placing **11,600** orders during the three-year span.
- The low-income group contributed **10,300** orders, showing sensitivity to value and affordability.
- High-income customers made **2,800** orders, suggesting an opportunity to increase sales through premium offerings or targeted marketing.
 
### 🔹 Occupational Trends
- Professionals led with **7,900** orders from **2020–2022**, followed by Skilled Manual workers at **6,000**, and Management roles at **4,400** orders.
- This trend emphasizes strong engagement from working-class and career-driven segments.

### 🔹 Key Customer Contributions
- The Top 100 customers brought in **$663,900** through **1,307** orders, proving the value of cultivating relationships with loyal buyers.
- Notably, **MR. MAURICE SHAN** was the top individual contributor, spending **$12,400** across 6 orders between **2020 and 2022**.
- Within the Skilled Manual segment, **MR. RUBEN SUAREZ** stood out in **2022**, generating **$4,700** in revenue.

<img width="1757" height="985" alt="Screenshot 2025-07-12 160203" src="https://github.com/user-attachments/assets/6169363c-2a56-45e1-9f56-484ecff98111" />

---

## 💰Sales Performance Analyse
Between **January 2020 and January 2022**, AdventureWorks demonstrated stable growth in overall revenue and profitability, supported by strong product demand and effective category management.

### 📌 Key Metrics
- Total Revenue: **$24.9 million**
- Profit: **$10.5 million**
- Orders: **25,225 units**
- Return Rate: **2.2%**
### 📈 Performance Trends
- Revenue **increased** consistently over the **2-year period**, reflecting healthy market traction.
- Recent monthly performance shows revenue of **$1.83 million (+3.31%)**, indicating continued growth.
- A slight decline in order volume **(-0.88%)** suggests potential seasonal variation or demand shift.
- Return activity rose to 166 units **(+1.78%)**, necessitating attention to product quality and customer experience.
### 🛒 Product & Category Highlights
- Accessories remain the top-selling category **(17K orders)**, followed by **Bikes (13.9K)** and **Clothing (7K)**.
- The most ordered product was the **Water Bottle – 30 oz**. with **3,983 orders**.
- High-revenue items included **Sport-100 Helmet, Red**, generating **$73K** but carrying a notable **return rate (3.33%)**.
- Shorts were the most frequently returned product, possibly indicating sizing or quality issues.
- Tires and Tubes emerged as top-performing product types in order volume.

<img width="1765" height="992" alt="Screenshot 2025-07-12 160031" src="https://github.com/user-attachments/assets/3d125d55-9a45-4607-adbc-077d7b2a9a9f" />

----

### 🛍️Product Performance Analyse
- Orders: **275 (Target: 293)** — just shy of goal, but quite close
- Revenue: **$2,735 (Target: $2,827)** — around 97% to target
- Profit: **$1,712 (Target: $1,770)** — not far off either
Slight underperformance, but not alarming. Might just be seasonal or tied to pricing dynamics.
 
### 📈 Graph Trends (July '21 to May '22)
 🔹Total Profit vs Adjusted Profit:
- Price adjustments yield visible profit lift, showcasing pricing elasticity.
- Even minor tweaks (like +0.10%) show positive shifts in profitability.

🔹Time Series:
- Revenue and profit trends hold steady through the simulated months.
- Return volume remains low and consistent suggesting product quality is strong.
- Low returns reassure stakeholders about product quality and customer satisfaction.


<img width="1760" height="989" alt="Screenshot 2025-07-12 160140" src="https://github.com/user-attachments/assets/12260ebe-d912-4562-b59d-c756671be4e8" />

---

## 🌍Regional Performance Analyse
AdventureWorks has established operations across key strategic territories, highlighting its international growth and diversified market footprint.
### 🔹 Countries Active
- North America: United States, Canada
- Europe: United Kingdom, France, Germany
- Pacific Region: Australia
### 📌 Strategic Implications
- These countries represent a mix of mature and emerging markets with strong demand for retail and outdoor products.
- Presence across three continents supports supply chain resilience and broader customer reach.
- Enables region-specific marketing campaigns, localized pricing strategies, and inventory optimization.
### 🧭 Business Advantages
- North America: Strong infrastructure and large customer base support high-volume sales.
- Europe: Growing interest in biking and sustainable mobility opens product innovation opportunities.

- Australia: Seasonal counterbalance enhances year-round revenue flow.<img width="1739" height="989" alt="Screenshot 2025-07-12 160114" src="https://github.com/user-attachments/assets/ffe07fb1-7d74-48f9-8f28-7ee5c8df0f36" />

---

## ✅ Conclusion
The AdventureWorks BI Dashboard project successfully delivers a data-driven narrative that illuminates key facets of business performance. By integrating product metrics, customer segmentation, and geographic analytics into a cohesive visual platform, the dashboards empower timely and informed decision-making. The platform has proven effective in tracking KPIs, identifying growth opportunities, and diagnosing areas requiring intervention  such as high product return rates and underperforming categories.This project positions AdventureWorks as a forward-thinking business that leverages business intelligence to optimize operations, personalize customer experiences, and explore global expansion with precision.
## 💡Recommendations
### 🛍️ Product Strategy
- Investigate high return items like Shorts to improve product design, sizing accuracy, or quality control.
- Create bundled offerings for popular accessory categories (e.g., tubes + tools + hydration products) to increase average order value.
- Continue price elasticity testing to optimize profit margins on essential inventory items.
### 👤 Customer Engagement
- Launch a tiered loyalty program rewarding top spenders with exclusive benefits (early access, discounts, etc.).
- Implement persona-targeted marketing based on occupation and income segments  e.g., professional discounts or referral perks.
- Use dashboard insights to identify and reward brand champions, like Mr. Shan and Mr. Suarez, with VIP perks or personalized outreach.
### 🌍 Geographic Expansion
- Prioritize market entry exploration into Asia and Latin America, starting with Japan, Brazil, and India.
- Tailor campaigns with region-specific promotions, cultural alignment, and localized content.
- Use dashboard filters to pilot and monitor performance in new regions before scaling globally.




