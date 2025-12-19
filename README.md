# Retail Sales & Profitability Analysis (Nigeria)

##  Project Overview
This project analyzes sales performance, customer behavior, discount impact, and COVID-19 disruptions across regions in Nigeria in order to support strategic retail decisions.
This was conducted in order to uncover sales trends, assess the impact of COVID-19, evaluate customer contribution to profit, and provide actionable insights.

This project was conducted using Python for data wrangling and EDA with Power BI for dashboards.
___

## Business Questions
The following questions guided the project.
* What impact did COVID-19 have on sales and profit?
* Which customer segment contributed the most to profit?
* To what extent do discounts influence sales and profit?
* How are sales distributed across time?
* What insights can help position post-COVID pricing and recovery strategies?
___

## Data Description
Granularity: Transaction-level data
Time: 2020 - 2024
Key Columns:  Customer_ID, Order_ID, Order_Date, State, Category,
       Sub_Category, Segment, Quantity, Sales, Discount, Cost,  
       Profit, Profit_Margin
___

## Data Preparation & Feature Extraction
Data preprocessing and feature engineering were done in Python.
They include:
- Date features (Year, Month, Quarter)
- COVID-19 period flag
- Revenue_per
- Discount band categorization
- Profit margin categorization
- Customer order frequency calculation
- Customer segmentation based on order behavior
___

## Exploratory Data Analysis (Python)
EDA was conducted to identify trends and patterns.
* Monthly Sales Trend
![Chart_1](../figures/1.png)

* Sales by Product Category
![Chart_2](../figures/2.png)

* Discount vs Profit
![Chart_3](../figures/3.png)

* Customer Segment Distribution
![Chart_4](../figures/4.png)

* Average Profit by Customer Segment
![Chart_5](../figures/5.png)

* COVID-19 Impact Analysis
![Chart_6](../figures/6.png)
___

## Dashnoard Design (Power BI)
An interactive Power BI dashboard was created highlighting:
- *Executive Overview*  
  n- KPIs  
  - Sales & Profit Trends  
  - Revenue Contribution by Product Category  

- *Customer & Retention Analysis*  
  - Profitability by Customer Segment  
  - Customer Base Composition  
  - Customer Segment PErformance Overview  

- *Pricing & Discount Strategy*  
  - Impact of Discounting on Profitability  
  - Profit Contribution by Discount Level  

- *COVID Impact Analysis*  
  - COVID KPIs: COVID Sales, COVID Profit  
  - Top 5 Performing States by COVID Sales
  - Sales and Profit Comparison (COVID vs non-COVID periods)  

[Link to Power BI Dashboard](https://app.powerbi.com/groups/me/reports/b5c47fa1-e75c-4b94-8c13-0e637584b6ab/fcb58ff712fe4ffbd2a2?experience=power-bi)

___

## Key Insights
- There was a deviation in sales and profits by approximately 45% each in comparison to post-lockdown baseline.  
- Loyal customers contributed most to profits.  
- An inverse relationship exists between discounts and profits but moderate discounts contributed the most to profits.  
- Sales was uneven across regions.
___

## Implications for Businesses
Insights from this analysis can help
- Revenue recovery and resilience planning
- Customer loyalty anf retention strategies
- Discount and promotional policy optimization
- Regional sales strategy and expansion planning
___

## Tools & Technologies
- Python: Pandas, Numpy, Matplotlib
- Power BI: Data modeling, DAX, Dashboard design
- Jupyter Notebook: Analysis and Documentation
___

## Author
Etebom Ntuk
Data Analyst
[Linkedin](https://www.linkedin.com/in/ntuk-etebom/)
___
