# 🧴 Power BI Retail Skincare Sales Analysis (2020–2023)

![Screenshot 2025-06-24 004937](https://github.com/user-attachments/assets/abaeff4b-de5f-49cb-baee-f08cf8801cd4)


## 📌 Project Summary

This Power BI project explores historical sales transaction data for a retail skincare company from 2020 to 2023. It uncovers trends in product performance, regional sales, customer segments, and profitability to guide strategic decision-making for stakeholders.

---

## 🧠 Outline

- Introduction  
- Story of Data  
- Data Splitting and Preprocessing  
- Pre-Analysis  
- In-Analysis  
- Post-Analysis and Insights  
- Data Visualizations & Charts  
- Recommendations and Observations  
- Conclusion  
- References & Appendices  

---

## 🎯 Introduction

### Objective of the Project  
To analyze retail skincare sales performance and customer behavior across four years using Power BI. The goal is to identify growth drivers, diagnose profitability decline in 2023, and offer actionable insights for business growth.

### Problem Being Addressed  
Despite rising sales, 2023 showed a noticeable decline in profitability. The project investigates this discrepancy while identifying top-performing products, segments, and regions.

### Tools & Methodologies  
- **Tool**: Microsoft Power BI  
- **Techniques**: DAX calculations, data modeling, visuals, slicers, KPIs  
- **Timeframe**: 2020–2023

---

## 🗂️ Story of Data

- **Source**: Created and provided by NTE Daniel  
- **Structure**: Each row represents a sales transaction with fields such as:
  - Product
  - Category/Sub-category
  - Region
  - Segment
  - Sales, Profit, Quantity
  - Order Date

### Key Features
- `Segment`, `Market`, `Category`: Useful for customer/product segmentation  
- `Sales`, `Profit`, `Quantity`: Key performance metrics  
- `Order Date`: Enables time-based trend analysis  

---

## 🧹 Data Splitting and Preprocessing

### Data Cleaning  
- Dataset cleaned prior to analysis  
- Verified for missing values (none found)

### Data Transformation  
- Created DAX measures:
  - Year-on-Year Sales
  - Previous Year Sales
  - Profit Margin
  - Growth Rate

### Variable Classification  
**Independent Variables**  
- Segment, Country, Region, City, Category, Sub-category, Product  

**Dependent Variables**  
- Quantity, Sales, Discount, Profit, Order Date  

---

## 🕵️ Pre-Analysis Highlights

### 📈 Identified Trends  
- Sales increased consistently from 2020 to 2023  
- Quantity sold also grew — suggesting strong demand

### 🔗 Potential Correlations  
- Rising sales but falling profits in 2023 point to margin pressure or cost increases  

### 💡 Initial Insights  
- Corporate clients drive the highest revenue  
- Lipstick category shows instability  

---

## 🔍 In-Analysis Findings

### Key Observations  
- **Corporate Segment** leads revenue generation  
- **Self-Employed Segment** shows strong growth potential  
- **Lipstick** underperforms in 2023 despite strong earlier performance  

### Power BI Features Used  
- DAX for dynamic measures  
- Slicers for real-time filtering  
- Card KPIs for high-level overview  
- Line, bar, and donut charts for visualization  
- Drill-downs for category-level insights

---

## 📊 Post-Analysis & Insights

### Core Discoveries  
- 📉 Profit declined sharply in 2023 despite record sales  
- 🌍 Asia Pacific continues to dominate overall performance  
- 🧴 Personal care product lines show reliable contribution  
- 💄 Lipstick category's 2023 drop suggests potential internal or market issue  

---

## 📌 Recommendations & Observations

### ✅ Actionable Business Insights  
- Target **Self-Employed** and **Consumer** segments for growth  
- Review **Lipstick** category for relaunch or replacement  
- Refine **cost structure** to recover profit margins  
- Leverage **Asia Pacific** market strength; invest in **LATAM** and **Africa**  

### ⚙️ Strategic Optimizations  
- Adjust marketing budget towards fast-growing customer segments  
- Re-evaluate pricing and supplier contracts  
- Consider automation in warehousing or supply chain  

### 🚨 Unexpected Outcome  
- Lipstick’s 2023 decline signals the need for competitive analysis or product review  

---

## 📈 Visual Highlights
- **Dashboard**: Executive overview with KPIs, matrix table, and filters
![Screenshot 2025-06-24 004937](https://github.com/user-attachments/assets/0944c53a-bdac-4000-a755-48846256277a)


---

## 🧾 Conclusion

### Key Learnings  
- Sales growth doesn't ensure profitability — margin control is crucial  
- Region and segment analysis helps target high-growth areas  
- Product volatility, like that of Lipstick, can destabilize revenue

### Future Work  
- Analyze **seasonality** and **campaign impact**  
- Calculate **Customer Lifetime Value (CLV)** and churn  
- Integrate **cost breakdown** and marketing spend data for deeper profitability analysis  

---

## 📚 References & Appendices

- [🔗 Dataset Access](https://drive.google.com/drive/folders/1ow1zaN9krTteCUj4GWgyljzwhohqBNKN?usp=sharing)  
- **Software**: Microsoft Power BI   

---

> 💼 _“Data without actionable insight is noise. This project turns raw retail data into strategic business direction.”_

