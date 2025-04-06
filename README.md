# Business Insight 360

## 🏢 Company Overview
AtliQ Hardwares is one of the fastest-growing companies in the electronic goods market, specializing in high-quality PCs, keyboards, mouse, and printers for both consumers and businesses.

## ❓ Problem Statement
- AtliQ relied on Excel and assumption-based decision-making, which led to poor outcomes, especially in the Latin American market.
- As the company scales, it needs to adopt advanced analytics to stay competitive with industry giants like Dell.
- This project aims to bring transparency, data-backed decisions, and strategic insights using Power BI.

## 📊 Dataset
Below is a breakdown of the datasets used for this project:

| Source Type     | Table Name                    | Description                                           |
|------------------|-------------------------------|-------------------------------------------------------|
| MySQL (GDB041)   | Fact_Forecast_Monthly         | Forecasted demand for products by month              |
| MySQL (GDB041)   | Fact_Sales_Monthly            | Actual sales data by month                           |
| MySQL (GDB056)   | Fact_Manufacturing_Cost       | Monthly manufacturing cost per product               |
| MySQL (GDB056)   | Fact_Freight_Cost             | Freight or shipping cost details                     |
| MySQL (GDB056)   | Fact_Gross_Price              | Gross price assigned to products                     |
| MySQL (GDB056)   | Fact_Pre_Invoice_Deduction    | Discounts or deductions before invoicing             |
| MySQL (GDB056)   | Fact_Post_Invoice_Deduction   | Discounts or deductions after invoicing              |
| MySQL (GDB041)   | Dim_Customer                  | Customer master data                                 |
| MySQL (GDB041)   | Dim_Product                   | Product master data                                  |
| MySQL (GDB041)   | Dim_Market                    | Market and region mapping                            |
| Excel            | Target                        | Sales targets for comparison                         |
| Excel            | Market_Share                  | Competitor-wise market share data                    |
| Excel            | Operational_Expenses          | Operating expenses for each region                   |

## 🔗 Data Model Diagram
The data model integrates multiple fact and dimension tables to support comprehensive business analysis.

![Data model for BI 360 Project](https://github.com/user-attachments/assets/e646449b-4bf4-4a20-a3df-4bb5652b39fa)

## 📑 Report Features

### 📘 Home Page 
A welcome screen featuring the project title, and navigation menu for seamless user experience.

![Buisness Insight 360 Dahboard_page-0001](https://github.com/user-attachments/assets/7a2f5ab4-769d-4a28-a995-03637b195093)

---

### 📘 Finance View  
Profit & Loss statement to evaluate financial performance across different products, markets, and customer segments.  

![Buisness Insight 360 Dashboard_page-0002](https://github.com/user-attachments/assets/f2e11b13-f4f5-43db-883c-785991df0de9)

---

### 📘 Sales View  
Identifies top and bottom customers using revenue contribution and other KPIs to support strategic sales decisions.  

![Buisness Insight 360 Dahboard_page-0003](https://github.com/user-attachments/assets/e6d6c77c-6921-431a-b222-2495967cffdd)

---

### 📘 Marketing View  
Analyzes product-level and regional performance to uncover trends, inefficiencies, and market behavior.  

![Buisness Insight 360 Dahboard_page-0004](https://github.com/user-attachments/assets/ab0060b3-8cdd-4db2-aa11-0cd217da19cb)

---

### 📘 Supply Chain View  
Focuses on forecast accuracy and inventory health to improve supply chain reliability and efficiency.  

![Buisness Insight 360 Dahboard_page-0005](https://github.com/user-attachments/assets/46703be6-f678-43bb-b128-9341b4421845)

---

### 📘 Executive View  
Provides a high-level summary of business performance, highlighting strategic metrics for leadership decisions.  

![Buisness Insight 360 Dashboard_page-0006](https://github.com/user-attachments/assets/2d99c5f2-ca43-486b-8150-60eee6d42e43)

---

## 💡 Insights
- **Finance View:** Net profit is declining despite growing sales. Expense optimization is needed.
- **Sales View:** Key accounts like Amazon and Flipkart drive revenue, while smaller accounts underperform.
- **Marketing View:** Product and regional inefficiencies hurt margins, especially in the Gaming category and APAC region.
- **Supply Chain View:** While forecast accuracy is fair, regions like LATAM and India face stock issues.
- **Executive View:** Market share is rising, but profitability is shrinking. PCs and regions like NA and India show growth potential.

## ✅ Recommendations
- Cut down operational and freight costs to improve profit margins.
- Double down on high-revenue accounts and reassess strategy for low performers.
- Optimize marketing spend and control costs in underperforming regions.
- Improve demand forecasting and inventory planning.
- Phase out underperforming products and focus on high-growth markets and categories.

## 🎯 Learnings
**Technical Skills:**  
- Data modeling and relationship building using Power BI
- DAX measures for KPIs like gross profit, forecast accuracy, and net profit
- Designing executive-level dashboards with slicers, bookmarks, and custom navigation
  
**Soft Skills:**  
- Business problem-solving through data
- Visual storytelling and dashboard structuring
- Aligning stakeholder needs with report design

## 🧾 Conclusion
This project transformed scattered data into actionable insights, enabling AtliQ to shift from assumption-based decisions to a data-driven strategy.

## 🔗 Useful Links
- [Project Presentation (PDF)](sample-link.com)
- [Dashboard Preview](sample-link.com)
- [GitHub Repository](sample-link.com)

## 🙏 Acknowledgment
This project is part of CodeBasics Data Analytics Bootcamp's Power BI course.

