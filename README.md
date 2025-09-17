`Salon & Spa` 

Industry Scenario 
The Salon & Spa industry provides a range of services such as haircuts, facials, massages, 
manicures, pedicures, etc. Business managers want to understand customer booking 
behavior, service popularity, and staff performance to improve operations, allocate 
resources better, and increase customer satisfaction.  

-Use Case 
Analyze customer appointments to identify popular services, peak booking times, customer 
spending patterns, and staff performance. 
This project analyzes customer appointment data for a Salon & Spa business using PySpark 
on Databricks. 
The goal is to identify popular services, peak booking times, customer spending patterns, 
and staff performance. 
The analysis helps the business improve resource allocation, pricing strategies, and 
customer satisfaction. 


-Dataset - File Name: salon_spa_dataset.csv - Records: 80 (sample) - Columns: - appointment_id – Unique ID of the appointment - customer_id – Unique ID of customer - customer_name – Customer name - service_type – Type of service (Haircut, Facial, Massage, etc.) - service_price – Price of the service - appointment_date – Date of appointment - appointment_time – Time of appointment - staff_id – ID of staff handling service - staff_name – Name of staff - customer_feedback_rating – Rating given by customer (1–5 scale) 
Tech Stack - Databricks (for data processing & visualization) - PySpark (ETL + analytics) - Spark SQL (querying) - Databricks Dashboard (visualizations) 

-Metrics & Insights 
We calculated the following business KPIs: 
1. Popular Services – Count of appointments per service type 
2. Peak Booking Hours – Most frequent appointment times 
3. Average Spend per Customer – Total spend / number of visits 
4. Top 5 Customers – Highest total spenders 
5. Staff Performance – Average customer rating per staff 
