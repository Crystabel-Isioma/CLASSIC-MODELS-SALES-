# CLASSIC MODELS SALES 

This project is a business sales dashboard and performance tracker built to evaluate product line performance, sales distribution by region, and overall profitability. The dataset mimics real-world business operations, helping uncover revenue drivers, regional strengths, and areas of improvement in profitability.

![Screenshot 2025-05-11 172428](https://github.com/user-attachments/assets/857a8dc9-d638-44ed-9b5a-ddc39bf17754)


---

## TABLE OF CONTENT  
- [Sales Dashboard Overview](#sales-dashboard-overview)  
- [Data Source](#data-source)  
- [Tools](#tools)  
- [Data Processing](#data-processing)  
- [Skills Demonstrated](#skills-demonstrated)  
- [Objectives / Problem Statement](#objectives--problem-statement)  
- [Data Analysis and Visualization](#data-analysis-and-visualization)  
- [Insights](#insights)  
- [Recommendations](#recommendations)  

---

## SALES DASHBOARD OVERVIEW  
This dashboard provides a dynamic overview of sales and net profit performance. It allows users to switch between Sales and Net Profit views, analyze performance by product line, country, and office location, and uncover patterns in profitability and cost management. The dashboard is fully interactive and filterable by date and product line.

---

## DATA SOURCE  
The dataset was extracted from the Classic Models sample database and includes the following fields:  
- OrderDate  
- OrderNumber  
- QuantityOrdered  
- PriceEach  
- ProductName  
- ProductLine  
- BuyPrice  
- Country  
- City  
- SalesValue  
- CostOfSales  
- NetProfit  

---

## TOOLS  
- *Microsoft Excel* – Data cleaning and preparation  
- *SQL* – Data analysis and transformation  
- *Power BI* – Dashboard creation and visualization  

---

## DATA PROCESSING  
- Cleaned and structured raw data in Excel  
- Used SQL to calculate:  
  - SalesValue = QuantityOrdered × PriceEach  
  - CostOfSales = QuantityOrdered × BuyPrice  
  - NetProfit = SalesValue − CostOfSales  
- Categorized data by product line, region, and time  
- Created date and toggle logic for interactivity  

---

## SKILLS DEMONSTRATED  
- Data modeling and transformation in SQL  
- KPI calculation and DAX logic in Power BI  
- Dynamic report development  
- Data visualization and storytelling  
- Business performance analysis  

---

## OBJECTIVES / PROBLEM STATEMENT  
To analyze sales performance and net profitability across different business dimensions in order to:  
- Identify high-performing product lines  
- Track trends in sales and cost over time  
- Analyze profit contributions by office and customer location  
- Support strategic planning with data-backed insights  

---

## DATA ANALYSIS AND VISUALIZATION  
The Power BI dashboard includes the following features:  
- *Key KPIs:* Total Sales, Net Profit, Average Order Value  
- *Toggle Button:* Switch between Sales and Net Profit view  
- *Sales Trends:* Line chart of order count over time  
- *Bar Chart:* Product line-wise sales or net profit  
- *Donut Chart:* Breakdown by office country  
- *Map Chart:* Customer country contribution  
- *Scatter Plot:* Sales vs Cost analysis  
- *Filters:* By date and product line  

---

## INSIGHTS  
- Classic Cars were the top-performing product line in both sales and profit  
- Offices in the USA and Japan had the highest regional sales  
- Higher BuyPrice led to lower profit margins in specific categories  
- Sales and cost of sales followed a closely aligned upward trend  
- Certain countries contributed disproportionately to total profit  

---

## RECOMMENDATIONS  
- Focus more on high-profit product lines (e.g., Classic Cars)  
- Re-evaluate pricing or cost structure for underperforming items  
- Target marketing in countries with untapped potential  
- Strengthen inventory planning in high-performing office regions  
- Continue monthly tracking to refine strategic decisions
