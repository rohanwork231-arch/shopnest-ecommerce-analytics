 # 🛒 Shop Nest - E-Commerce Sales & Operational Analytics | Power BI

## 📌 Project Overview
Power BI dashboard analyzing **99,000+ orders** and **$13.59M in revenue** from the shopnest e-commerce marketplace to uncover sales trends, operational inefficiencies, and customer retention opportunities.

---

## 🎯 Business Problem
Shop Nest, an online marketplace, was experiencing rapid growth but lacked unified reporting across 9 disconnected data sources. The company needed to:
- Monitor revenue growth and identify seasonal trends
- Determine which product categories drive the most value
- Analyze geographic revenue distribution and expansion opportunities
- Track delivery performance and operational efficiency
- Understand customer satisfaction and identify quality issues
- Assess payment method preferences and processing costs

---

## 🛠️ Tools & Technologies
- **Visualization:** Power BI Desktop
- **Data Modeling:** Star Schema (9 tables)
- **Analysis Language:** DAX (Data Analysis Expressions)
- **Data Transformation:** Power Query (M Language)
- **Techniques:**
  - Calculated measures and columns
  - Time intelligence functions
  - Multi-table relationships
  - Cross-filtering and drill-through
  - KPI development

---

## 📂 Dataset
**9 interconnected tables** with **1.5M+ total records**:
- **Fact Tables:** Orders (99K), Order Items (112K), Order Payments (103K)
- **Dimension Tables:** Customers (99K), Products (33K), Sellers (3K), Reviews (99K), Geolocation (1M), Category Translation (71)
- **33 total attributes** across all tables
- **Time period:** 2016-2018

---

## 🔍 Analysis Performed

### 1. **Data Modeling**
- Designed star schema with proper fact-dimension relationships
- Established one-to-many cardinalities between tables
- Utilized order purchase timestamp for time-based analysis and trend evaluation.
- Ensured data integrity across all table joins

### 2. **Revenue Analysis**
- Calculated total revenue, orders, and average order value (AOV)
- Analyzed year-over-year growth trends (2016-2018)
- Identified quarterly seasonality patterns
- Tracked monthly revenue progression

### 3. **Product Performance**
- Ranked top and bottom product categories by revenue
- Analyzed category contribution to total sales
- Identified high-performing and underperforming product lines
- Created product rating analysis (top 10 vs bottom 10)

### 4. **Geographic Analysis**
- Mapped revenue distribution across Brazilian states
- Identified geographic concentration risks
- Analyzed state-level sales performance
- Highlighted expansion opportunities

### 5. **Operational Metrics**
- Tracked on-time vs delayed delivery performance over time
- Calculated delivery efficiency improvement trends
- Monitored monthly operational KPIs
- Identified seasonal strain on logistics

### 6. **Customer Insights**
- Analyzed payment method distribution and preferences
- Calculated customer acquisition vs retention metrics
- Assessed customer satisfaction through review scores
- Identified repeat purchase opportunities

---

## 📈 Key Findings

| Finding | Impact |
|---------|--------|
| **Revenue Growth** | Significant year-over-year growth observed between (2016-2017), consistent upward trend |
| **Customer Retention Issue** | Total orders are approximately equal to total customers, indicating limited repeat purchase behavior. |
| **Geographic Concentration** |São Paulo contributes the largest share of total revenue, indicating geographic concentration risk. |
| **Top Revenue Category** | Health & Beauty is the top revenue-generating category. |
| **Delivery Performance** |Delivery delays decreased significantly over time, indicating operational improvements. |
| **Payment Preference** | Credit cards dominate payment transactions. |
| **Seasonal Pattern** | Q2 and Q3 show noticeably higher sales compared to Q1 |
| **Quality Issues** | Bottom-rated categories include Furniture and Tools, indicating potential quality issues. |

---

## 💡 Business Recommendations

1. **Implement Retention Program**
   - Launch email marketing campaigns targeting first-time buyers
   - Create loyalty program with points-based rewards
   - Reduce customer acquisition cost payback period from 18 to 6 months
   - **Projected Impact:** Expected revenue uplift through improved retention strategies.
2. **Geographic Expansion**
   - Open second distribution center in Rio de Janeiro or Minas Gerais
   - Launch state-specific marketing campaigns in underserved regions
   - Reduce São Paulo dependency from 35% to 25%
   - **Projected Impact:** +$680K from diversified revenue streams

3. **Optimize Delivery Operations**
   - Add backup shipping partners during Q2-Q3 peak season
   - Implement warehouse management system for efficiency
   - Target <8% delay rate (currently 15%)
   - **Projected Impact:** Improve customer satisfaction, reduce service costs 30%

4. **Product Quality Improvement**
   - Remove products with <3.0 rating from catalog
   - Implement supplier quality standards for furniture/tools categories
   - Create "Quality Verified" badge for 4+ star products
   - **Projected Impact:** +5% conversion rate on high-AOV categories = +$270K revenue

5. **Category Focus**
   - Double marketing spend on Health & Beauty (top performer)
   - Expand product selection in top 3 categories by 20%
   - Create bundle deals across high-performing categories
   - **Projected Impact:** +$680K from category expansion

6. **Payment Optimization**
   - Incentivize boleto/PIX usage to reduce processing fees
   - Add digital wallet options (PayPal, Apple Pay)
   - Negotiate better rates with payment processors
   - **Projected Impact:** Save 0.5% of revenue = $68K annually

---

## 📁 Files in This Repository

| File/Folder | Description |
|-------------|-------------|
| `ShopNest_Dashboard.pbix` | Complete Power BI dashboard file |
| `Visuals` | Sales performance and operational analysis dashboard screenshot |
| `README.md` | Project documentation |

---

## 🚀 How to Use

1. Download `ShopNest.pbix`
2. Open in Power BI Desktop (latest version recommended)
3. Use slicers to filter by Year, Product Category.

---

## 🎓 Skills Demonstrated

✅ Star schema data modeling (9 tables, proper relationships)  
✅ DAX formula development (15+ measures including AOV, growth rates)  
✅ Data visualization best practices (KPIs, trends, comparisons)  
✅ Business intelligence storytelling and dashboard design  
✅ Time intelligence calculations and trend analysis  
✅ Multi-dimensional analysis (category × geography × time)  
✅ Operational analytics and performance tracking  
✅ Translating data insights into actionable business strategies  

---

## 🙋 About Me
**Rohan Singh** – Aspiring Data Analyst skilled in SQL, Python, Power BI, and Excel.

📧 rohan.work231@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/rohan-singh-b88286340)  
💻 [GitHub](https://github.com/rohanwork231-arch)
