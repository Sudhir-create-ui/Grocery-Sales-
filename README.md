# Grocery-Sales-Analysis
My First Project 
# Grocery Sales Analysis Dashboard (Excel + Power BI)

This project demonstrates a complete end-to-end data analytics workflow using Excel for data cleaning and Power BI for dashboard development. The dataset simulates weekly grocery sales performance across multiple items, seasons, and store locations.

---

## 1. Project Objectives
- Clean and structure raw sales data in Excel.
- Build analytical measures using DAX in Power BI.
- Design a professional dashboard with KPIs and visuals.
- Provide insights on revenue trends, category performance, and store comparisons.


## 2. Tools & Technologies
- **Excel**: Data cleaning, formatting, and preparation  
- **Power BI**: Data modeling, DAX measures, dashboard design  
- **DAX**: Custom calculations for KPIs and visuals  

---
## 3. Dataset Description
Columns included:
- Item  
- Category  
- Season  
- Store Location  
- Units Sold  
- Revenue  
- Week Number  
- Seasonal Index  
- Sales Level  

Dataset size: **300 rows**

---
## 4. Excel Data Cleaning Steps
1. Removed duplicates  
2. Standardized date and column formats  
3. Added calculated columns where necessary  
4. Verified all numeric columns  
5. Exported clean dataset to Power BI  

---

## 5. Power BI DAX Measures
``DAX
 Total Revenue = SUM(cleaned[Revenue])

Avg Units Sold = AVERAGE(cleaned[Units Sold])

Max Revenue = MAX(cleaned[Revenue])

Rank Item by Revenue =
RANKX(ALL(cleaned[Item]), [Total Revenue], , DESC)

---
## 6. Dashboard Features
- KPI Cards
  - Total Revenue  
  - Avg Units Sold  
  - Max Revenue  
  - Top Performing Item  
- Donut Chart: Revenue Share by Category  
- Bar Chart: Category Performance  
- Line Chart: Units Sold Trend by Week  
- Column Chart: Store Location Comparison  
- Slicers: Category, Store, Week Number  

---

## 7. Key Insights
- Highest revenue category  
- Strongest store location  
- Week-to-week performance behavior  
- Top-selling items  
- Seasonal performance patterns  

---

## 8. How to Use This Repository
- Download the dataset (`grocery_sales_raw.csv`)  
- Download the Power BI file (`.pbix`)  
- Open in Power BI Desktop  
- Explore the visuals and DAX formulas  

---

## 9. Dashboard Screenshot
(Insert PNG of dashboard here)

---

## 10. Author
Your Name  
Aspiring Data Analyst  
LinkedIn: (your profile)

---

## 11. License
MIT License

