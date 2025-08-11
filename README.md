# 📊 Sales Insights Dashboard – Retail Domain

An interactive *Power BI dashboard* project developed to analyze and visualize retail sales performance using *MySQL* as the backend, *Power Query* for ETL, and *DAX* for calculations.  
This project helps uncover trends in *revenue, sales quantity, market performance, product ranking, and customer profitability* across multiple years.


## 📌 Features

- *Interactive Year & Month Filters* (2017–2020) for dynamic time-based analysis
- KPI Cards for Revenue, Sales Quantity, and Total Profit Margin
- *Market-Level Analysis* – Revenue, sales quantity, and profit contribution % by region
- *Customer Profitability Analysis* – Identifies both profitable and loss-making customers
- *Top Products View* – Lists top products by revenue
- *Revenue Trends* – Detects seasonal and monthly performance changes
- *Data Quality Highlight* – Detects missing product details (Blank values)


## 🛠 Tools & Technologies

- *Power BI Desktop*
- *MySQL* (Data Source)
- *Power Query Editor*
- *DAX (Data Analysis Expressions)*
- *Git* (Version Control)


## 📁 Project Structure
```bash
SalesInsights/SalesInsights
│
├── Sales-Insights.pbip              
├── Sales-Insights.Reports/          
├── Sales-Insights.SemanticModel/

```



## 🚀 Getting Started

1. *Clone this repository*  
   bash
   git clone https://github.com/jlokesh14/SalesInsights
   

2. *Open Power BI Desktop* and load the .pbip file.  

3. *Update MySQL credentials* in Power Query:  
   - Go to *Transform Data → Data Source Settings*
   - Update *Server, **Database, and **Authentication* details.


## 📈 Key Metrics Tracked

- *Total Revenue*
- *Total Sales Quantity*
- *Total Profit Margin*
- *Revenue Contribution % by Market*
- *Profit Contribution % by Market*
- *Top Customers*
- *Top Products*
- *Monthly Revenue Trend*



## 📸 Dashboard Screenshots
![image alt](https://github.com/jlokesh14/SalesInsights/blob/main/Images/Screenshot%202025-08-11%20164910.png)
![image alt](https://github.com/jlokesh14/SalesInsights/blob/main/Images/Screenshot%202025-08-11%20164841.png)



## 💡 Insights Retrieved from Dashboard

From the analysis:

1. *High Market Dependency* – Delhi NCR alone contributed over *50% of total revenue* and nearly *48% of profit*.  
2. *Customer Concentration Risk* – The top customer accounted for *₹138.54M revenue*.  
3. *Profitability Concerns* – Certain high-revenue customers operated at *negative profit margins*, signaling the need for pricing or contract review.  
4. *Seasonal Revenue Trends* – Sales peaked mid-year (July) and saw a drop toward year-end.  
5. *Data Quality Issue* – “(Blank)” product category generated ₹154.6M in revenue, indicating missing product mapping in the dataset.  
6. *Emerging Profitable Markets* – Smaller markets like Surat and Patna had high profit % despite lower sales volumes.
