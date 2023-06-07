# AtliQ Hardware Sales Analysis

#Problem Statement :

AtliQ Hardware is a company which supplies computer hardware and peripherals to many clients across India;
The company has a head office in Delhi and regional offices throughout India.

Business Issue:

The director is struggling to track the company's business growth, as overall sales have been declining. The director relies on regional managers for North India, South India, and Central India to provide insights into their respective regions. However, obtaining these insights involves calling the managers and receiving information over the phone, which hinders effective and efficient decision-making.

Insight:

As AtiQ is a significant business, the director recognizes the need for data-driven decision-making to increase sales effectively. The director is seeking a solution in the form of a user-friendly data visualization tool, such as Power BI, which will enable daily access to a customized sales dashboard. This project aims to assist AtiQ in developing their own sales-related dashboard to facilitate data-driven decision-making and enhance overall sales performance.

Solution:

Create a simple and informative dashboard about the company sales.

Step1:
ETL 
>Extract
>Transform
>Load

Step 2:
Importing this Data in MySQL.

Step 3:
Data Transformation in Power BI
Once the data is imported in Power BI, we do ‘transform data’ i.e. using the Power Query editor to perform certain operations on to the data. Ensuring correct data types, and creating custom/conditional columns are some fundamental task performed in Power Query.

Modeling Schema in Power BI
Created 'one to many' relationship model between dimension table and fact table using primary key and foreign key concept.

Created Measures
Created required measures using aggregation, filter DAX functions.

Step 4:
Creating a Report in Power BI
A report is created in Power BI with various charts depicting Revenue by Market, Sales Quantity by Market, Revenue Trend, Top 5 Customers by Revenue, Top 5 Customers by Quantity, Revenue by Zone, Sales Quantity by Zone and KPI such as Total Revenue & Total Sales Quantity. All these charts can be filtered using Year and Months slicer.

Deployment in Power BI
In Power BI, You can directly publish the report online to your workstation. If you do not have the work email-id then you can save the file in ‘.pbix’ version. This helps another viewer see your work and understand the story or insights you’re communicating.

Step 5:
Final Report
Based on the dashboards insights, I have made some conclusions and recommendation that Sales Marketing team should/can consider making a sales strategy.

Conclusions:
Sales were rapidly decreasing in 2020 compared to 2019.
Highest revenue generated from markets such as Delhi NCR, Mumbai, Ahmedabad, Bhopal, Nagpur and so on.
Highest quantities sold in Markets such as Delhi NCR, Mumbai, Nagpur, Kochi, Ahmedabad and so on.
The most important customer for company is Electricalsara Store by Revenue as well as quantity sold.

Recommendations:
Make a new sales strategy for lucknow since its showing lowest revenue and negative profit margin and if possible so as for Surat and Bhubaneshwar also.
Try to increase sales quantity in Patna, Surat and Kanpur since they have lowest sales quantity.
Try to give special benefits to Electronics and Excel stores as they are most profitable customers.
Make campaign strategy for mid year as they are showing high sales among other months.

#Tools, Software and Libraries :

1.MySQL

2.Microsoft Power BI

3.Power Query Editor
