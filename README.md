# ECommerce Sales Analysis Dashboard

## Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNWMwMjMzYmItNTdlNS00NDhiLWIwY2EtYjMwZGZhODkwMGZlIiwidCI6IjFlYzU0YzVlLWI2OTAtNGM5Yi04NzQ5LTkyNWE4ODkyZDlmMCJ9

## Problem Statement

This dashboard helps the ECommerce business to understand their business better. It helps the business to know if their sales are in good shape and their consumers are satisfied with their services. Through different regions, they get to know their improvement area, & thus they can improve their services by identifying these area.


## Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Unnecessary rows and columns has been removed to reduce ambiguities and anomalies of the data.
- Step 5 : All sorts of ETL operations has been executed to get the structured data.
- Step 6 : Data modelling has been created for One-to-many relationship cardinality following Star Schema to optimize the report performance. 

The Analysis is based on ECommerce Sales where client wants us to analyze and create KPIs and sales, profit trends on Year on Year analysis, Year To Date and Previous Year To Date calculation alongwith Profit Margin. This report is based on dynamic dasboarding and calendar table is created on for various sales and profit generated for further analysis. DAX functions has been implemented. Data blending, cleaning, transformation and ETL being performed like changing data types based upon data received, removing bad data, null values, anomalies and ambiguities for better optimization and good analysis performance.

KPI plays a very important role in any of the business to analyze and interpret how currently business is performing over the years based on comparison to previous years. How much target has been achieved in business and how much revenue has been generated. Company is more concerned about the key metrices of cards and KPI visuals to drive the business.

Slicer has been implemented on customer segmentation which has categorized into 3 parts: Consumer, Corporate and Home Office. Matrix visuals tells us to compare PYTD Sales, YTD Sales, YoY Sales and Trends among Furniture, Office Supplies and Technology of Category wise in respect to Sales. YoY Sales in Furniture seems to be in positive mode.

Overall YTD Profit has generated around $1.34M and YoY Profit increased by 4.50% and its in increasing streamline and trend. YTD Sales has generated around $11.53M but YoY Sales decreased by 0.83% as well as YTD Quantity by 7.29%. Overall Profit Margin maintained good amount of percentage with 11.58% and YOY Profit Margin increased by 5.37%.

![YTD Sales](https://github.com/Rishi-Kalpa/ECommerce-Sales-Analysis-Dashboard/assets/98646729/f98a0d09-8609-4a5d-972e-6713688a9412)  ![YTD Profit](https://github.com/Rishi-Kalpa/ECommerce-Sales-Analysis-Dashboard/assets/98646729/7fcb6db8-fff8-447d-9804-c4abc4f0a73b)  ![YTD Quantity](https://github.com/Rishi-Kalpa/ECommerce-Sales-Analysis-Dashboard/assets/98646729/e232381c-2087-417d-88e1-f39397276d56)  ![YTD Profit Margin](https://github.com/Rishi-Kalpa/ECommerce-Sales-Analysis-Dashboard/assets/98646729/ff65d04c-80f7-414f-af86-626d8fa64eed)

Based upon Top 5 Sales with respect to Products, Staple Envelope is the highest trending product which generated amount of $57K followed by Staples, Easy-Staple so on and so forth.

Mapping Visuals has been implemented among sales in respect to 4 different regions like Central, East, South and West. Bigger the bubble size, higher the sales being generated, smaller the bubble size, lower the sales being generated. Based upon visual, central sales seems to be on top generating region.

Based upon Sales in respect to category wise, office supplies covers 60% of total revenue created around $6.92M of YTD sales followed by Furniture with $2.52M and Technology with $2.10M.

# Snapshot of Dashboard (Power BI Service)
![Snapshot](https://github.com/Rishi-Kalpa/ECommerce-Sales-Analysis-Dashboard/assets/98646729/a9c38896-09ef-4d80-8c0c-cd97cfae122f)

## Insights and Recommendations
Company agents should organize a marketing campaign for giving more valuable details, features regarding the products and services. They need to upgrade the product & they should do market research on what actually customers requirements is. This is how they should survey and take feedbacks from customers and would drive the business accordingly, efficiently & make data driven decisions for consistent business growth.
