# ETL- Data Analytics
ETL pipeline, star schema, and Power BI dashboard

### Summary:
An end-to-end ETL pipeline in Python to ingest, clean, and transform e-commerce transaction data into a star schema (fact_transactions + dim_customers + dim_products + dim_date). Created analytics artifacts (aggregates, RFM segmentation, cohort analysis) and interactive dashboards in Power BI to help stakeholders monitor revenue, customer value, and product performance.

### Deliverables:

• Raw + cleaned datasets (CSV)

• dim_date, dim_products, dim_customers, fact_transactions CSVs

• Jupyter Notebook with full ETL + visualizations

• Power BI dashboard (design & DAX measures)

• README, SQL DDL, and my recommendations as a data analyst

### Tools used

 ✔ Jupyter Notebook  for data exploration and manipulation
 
✔ Airflow for orchestration and scheduling ETL workflows

✔ Snowflake for data warehouse 

✔ Power BI for data visualization 

### Impact: 
Enables automated reporting, customer segmentation for retention campaigns, identification of high-value SKUs, and monitoring of return rates and payment performance.

## Dataset

<a href="https://github.com/CelesNeba/E-commerce-Transaction-ETL-Analytics/blob/main/etl_sample_2000.csv.csv">
  Click here to view the dataset
</a>

### Step one
• Import data for cleaning
![Imported Data Screenshot](https://github.com/CelesNeba/E-commerce-Transaction-ETL-Analytics/raw/main/Imported%20data%201.JPG)




• Data is cleaned, and all the necessary data manipulation is done, ready for visualization
![Clean Data Screenshot](https://github.com/CelesNeba/E-commerce-Transaction-ETL-Analytics/raw/main/Clean%20data.JPG)

#####  I want to visualize:
• Total revenue by product category

• Total revenue by product value

• Customers by the time of their last transaction

• Total revenue by country

• Total revenue by month

• Count of transactions by payment method

![ETL Dashboard Screenshot](https://github.com/CelesNeba/E-commerce-Transaction-ETL-Analytics/raw/main/ETL%20Dashboard.JPG)


### My recommendation 

This dashboard provides a comprehensive overview of key customer and sales trends derived from the ETL project. Based on the insights presented, I recommend focusing on strategies to improve customer retention, particularly within the 15-30 day purchase cycle. Further investigation into the factors driving product category performance and payment method preferences will enable targeted marketing and operational improvements to maximize revenue and customer lifetime value."



