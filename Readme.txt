Fruit Sales Performance Dashboard
This repository features a Power BI project focused on retail analytics, specifically tracking sales performance, profitability, and quantity trends across a fruit inventory dataset. 

Project Overview
The goal of this dashboard is to provide a granular view of sales health. By utilizing advanced DAX measures, the report breaks down revenue streams and profit margins to identify top-performing products and sales efficiency over time. 

Key Metrics & DAX Calculations
I implemented the following measures to drive deep-dive analysis:

Revenue & Volume:

Total Sales: A core metric calculating the total revenue generated. 

Total Quantity: Tracks the physical volume of goods moved. 



Profitability Analysis:

Total Profit: Calculates the net gain after costs. 


Profit %: Uses the DIVIDE function to calculate the margin percentage ([Total Profit] / [Total Sales]), ensuring a safe calculation even if sales are zero. 



Performance Benchmarking:

Average Sales: Calculated using AVERAGE('Fruit Sales'[Sales]) to understand typical transaction value. 

Max/Min Sales: Utilized MAX and MIN functions to identify the highest and lowest sales peaks within the dataset. 

Counting Logic:

Total Number of Rows: Created a measure using COUNTROWS to track the total volume of transactions recorded in the 'Fruit Sales' table. 



Technical Implementation

Tool: Power BI Desktop. 

DAX Expertise: Developed specific measures for profitability ratios and statistical sales ranges. 

Data Structure: Managed the 'Fruit Sales' table to ensure accurate aggregation across multiple categories. 



Key Insights Delivered

Sales Consistency: Comparing Average Sales against Max/Min peaks to understand revenue volatility. 


Margin Tracking: Monitoring Profit % to identify which fruit categories are the most cost-effective, rather than just high-volume. 


Transactional Scale: Using the Total Number of Rows to gauge the size of the operation and customer frequency.