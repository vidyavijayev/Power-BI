# Power-BI
Axon sales analysis
AXON SALES ANALYSYS

Business Request:
A small company Axon, which is a retailer selling classic cars, is facing issues in managing and analyzing their sales data. The sales team is struggling to make sense of the data and they do not have a centralized system to manage and analyze the data. The management is unable to get accurate and up-to-date sales reports, which is affecting the decision-making process.
To address this issue, the company has decided to implement a Business Intelligence (BI) tool that can help them manage and analyze their sales data effectively. They have shortlisted Microsoft PowerBI and SQL as the BI tools for this project.
The goal of the project is to design and implement a BI solution using PowerBI and SQL that can help the company manage and analyze their sales data effectively. The solution should be able to:
•	Import and integrate the data from MySQL database into PowerBI
•	Clean and transform the data to make it ready for analysis.
•	Build interactive dashboards and reports using PowerBI that can help the sales team and management make sense of the data.
•	Enable the management to access the dashboards and reports in real-time and make data-driven decisions.

Business demand overview:

Report to: Sales Manager Axon
Value of change: Visual dashboards and better reporting to manage and analyse their sales data effectively.
Necessary system: Power BI And SQL
Other relevant info: Data tables of 2003,2004 ,2005 included that contains typical business data such as customers, products, payments, orders etc.

All About Dataset:
The MySQL sample database schema consists of the following 8 tables:
•	Customers: stores customer’s data.
•	Products: stores a list of scale model cars.
•	ProductLines: stores a list of product line categories.
•	Orders: stores sales orders placed by customers.
•	OrderDetails: stores sales order line items for each sales order.
•	Payments: stores payments made by customers based on their accounts.
•	Employees: stores all employee information as well as the organization structure such as who reports to whom.
•	Offices: stores sales office data



Steps for analysis:
•	Connect to Data Sources/Data Extraction:
Database was available in MySQL and the same was loaded in PowerBI.

•	Data Preparation and Transformation:
	Data Cleaning: Replaced missing values, reordered columns and corrected errors.
	Data Transformation: Used Power Query Editor to transform data, such as changing data types, combining columns etc
	Data Merging: Combined multiple tables using joins 

•	Data Modelling: Managed the different table relationships and created 6 additional tables which includes Dim table, two calendar tables, order cart value, merge table and status count. Did include measures like YTD, PYTD, YoY%, QoQ% etc which are listed in Key Measures

•	Analysis and Insights:
	Applied Filters and Slicers: Used these to drill down into specific aspects of data like product line, customer country, year, status.
	Used Advanced Analytics Features: Applied forecasting to find out the total sales for 2006 and 2007 with 99% confidence
•	Design and Build Reports:
	Created Visualizations: Used Power BI’s drag-and-drop interface to create charts, graphs, tables, maps, and other visual elements.
	Customized Visuals: Adjusted visual settings, formatting, and interactions to enhance clarity and usefulness.
	Created Dashboards: Combined multiple visuals/reports into dashboard for a comprehensive view of the data.

Key insights:
•	Total sales were determined as $ 9.6M (profit $3.83M) considering all the orders placed whereas it was $8.87M (profit $3.53M) when only the shipped orders were taken into consideration.

•	Total sales, year on year sales growth, number of orders etc were maximum in the year 2004 (36.13% YOY sales growth). Total sales increased from 2003 to 2004 whereas a sharp decline was found when it reached 2005(the entire year details are not there though). A forecast for 2006 and 2007 with 99% confidence also shows a gradual decrease in Total sales.

•	The profit was maximum in 2003 and 2004 during the month of November

•	Highest sales were from customers in USA and least from Singapore

•	The country wise total sales contribution was highest from US ($3.48M) branch followed by France($3.08M) and city wise Madrid($0.9M) and San Rafael ($0.5M) respectively

•	Around 93% ordered items were shipped and on an average, it took 3.7 days for the same

•	Most of the customers were under High credit segment and more profit were reaped from the same

•	The QoQ% is seen to be negative in first quarter for all the years. This negative growth is attributed to the higher growth of sales in the 4th quarter of each year

•	Gerard Hernandenz can be considered the top performing employee as the sales was maximum from his end. Diego (Euro+ shopping channel) can be considered the premium customer with maximum credit limit

•	Average order value is 29.46k with most of the orders in the cart value range 20k-40k

•	At $3.85 Million, Classic Cars had the highest sales and the lowest sales was for trains at $0.19 Million. Classic Cars accounted for 40.13% of Total Sales.

•	In the Classic cars category 1992 Ferrari 360 Spider red had the maximum order whereas the most profitable car model was 1952 Alpha Renault 1300.



