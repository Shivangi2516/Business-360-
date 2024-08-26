# AtliQ Business Insights 360

# Project overview


AltiQ Hardware, a rapidly growing company that operates globally, specializes in selling hardware products through three main channels: retailers, direct sales, and distributors.

Despite its growth, the company suddenly ran into a serious issue of losses after opening a store in America. These setbacks were identified through surveys, intuition, and basic Excel analysis. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities to thrive in the industry.

To surpass competitors and enable data-driven decision-making, the company has decided to implement Power BI for analytics. This project aims to provide stakeholders with insights into finance, sales, marketing, and supply chain, ensuring informed decisions at all levels.


I worked on this project by following the Codebasics PowerBi Course,

here is my report link :

https://app.powerbi.com/view?r=eyJrIjoiNjZhNjY4OTUtN2FjZS00NjEzLWIxZjQtZDE3MDUxODA4NzA5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9


#Datasets:


Before starting the analysis, understanding the datasets is important. The datasets consist of two tables:

Dimension table: Static data like customer and product details.

Fact table: Transaction data.

gdb041:

dim_customer
dim_market
dim_product
fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.
gdb056:

freight_cost
gross_price
manufacturing_cost
Pre_invoice_dedutions
Post_invoice_deductions
Importing Data and Data Modeling:
Data was imported from MySQL into Power BI, and a data model was created after cleaning and transforming the data. But why data modeling is very important for analysis right??

If you break down the whole work of a data analyst then you will come up with 4 steps of work

✅ Data Extract ---> ✅ Data Cleaning---> ✅ Data Modelling ---> ✅ Data Analysis

See you can't skip the 3rd step if you want to reach the last step (analysis part), Data modeling is essential because it lays the foundation for reports. All visuals are built upon the data model, and poor modeling can affect report performance.

In this project, we have followed the Snowflake schema data modeling method.


![image](https://github.com/user-attachments/assets/30ca5626-5a9f-468c-8b28-87c75b3e2145)





#Power BI Dashboard Overview:

The dashboard contains six pages-->

 #Home Page: A landing page with buttons to navigate to different pages.






