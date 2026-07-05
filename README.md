# Power-BI-JCars-Logistics-
The goal of this project was to create an interactive Business Intelligence (BI) dashboard for JCars Logistics using Power BI.  The dashboard empowers users to effectively monitor logistics performance, analyze key operational data, uncover important business trends, and make informed, data-driven decisions through dynamic visualizations.
Importing the Data into Aiven- Here's what I did during the setup process: I Created a PostgreSQL database service on Aiven,Connected it to the new database using the hostname, port, username, password, and database name provided by Aiven.I Created the necessary tables for the project and Imported the logistics dataset into the database using SQL import tools .Lastly Double-checked that all records were successfully uploaded before connecting Power BI to the database.
On DAX Measures & Calculations I created several custom measures to better analyze the logistics performance. Key ones include:Total Revenue,Total Orders,Gross Profit and Profit Margin (%).
On the visuals I designed the dashboard with several interactive visuals to make it easy to explore. Key KPI Cards at the top shows Total Revenue, Total Orders, Gross Profit, Profit Margin, and On-Time Delivery Rate.Revenue Trend Chart – a line chart shows how revenue has changed over time.Orders by Region – a bar chart (and map) highlighting performance across different locations.Delivery days displays number of days taken to deriver the goods.Top Customers & Routes – ranks to quickly spot the biggest contributors. Profit Breakdown shows breaking down profit by category or service type.Slicers & Filters shows the dates, regions, customers, and transport mode used while derivering the goods.
On the Key Insights from the Project,Working on this dashboard really helped bring the data to life.I discovered,Profit margins vary quite a bit depending on the service type thus making categories are very healthy, while others are barely breaking even.Faster delivery times seem to lead to more repeat business. Most customers preferred to pay through Mpesa.The most sold Car model was certainly the Toyota.Overall, the dashboard shows that JCars Logistics is doing well in several areas, but there are clear opportunities to improve delivery reliability and focus on the most profitable segments to drive even better results.
After spending time analyzing the data and building this dashboard, here are a few things I believe would make a real difference for JCars Logistics, its would be better to Prioritize on high-margin services.Some categories are doing great, while others are barely profitable. Its will be certainly good to Give more attention to the western region , they are areas that have more business opportunies more than Nairobi or central regions.





















