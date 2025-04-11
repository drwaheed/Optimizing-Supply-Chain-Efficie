# Optimizing-Supply-Chain-Efficiency
# Overview
A Power BI dashboard optimizing supply chain efficiency by analyzing supplier performance, production efficiency, inventory evaluation, order fulfillment, shipping & logistics, and sales overview. Visuals highlight key interdependencies, track performance metrics, and provide actionable insights to enhance decision-making, reduce inefficiencies, and improve supply chain resilience. Ideal for supply chain managers to monitor operations and drive strategic improvements.
# Visuals Included

![image](https://github.com/user-attachments/assets/07fb26e1-7fd3-4df8-9e13-d3d660fe4228)

**1. Supplier Evaluation**
- No.of Supplier, Avrg.Lead Time, Avrg.Lead Time Variance, Total Qty Supplied, Supplier on Time Delivery Qty Rate, Supplier Efficiency 
-  Total Quantity Supplied With Supplier on Time Delivery Qty Rate
-  No. Of order delivered on time, No. orders delivered late and Supplier Efficiency Per Supplier
-  Order Qty received on time, Total Qty supplied and supplier On-Time Delivery Quantity Rate by Product type
-  Production volumes and Avg. Manufacturing lead time by Product type
 
![image](https://github.com/user-attachments/assets/0e304cd7-7e04-48bf-9c31-694c0cdcc9a5)

**2. Production Evaluation**
- Defect Rate % , Production Volume , Manufacturing Cost , Avrg. Manufacturing Lead Time, Order Quantity from supplier
- Total NO. of products by Inspection results
- Production volumes and Defect Rate % by Product type
- Qty Sold, Production Volume and Order quantities from supplier by Product type
- Manufacturing cost by Product type and Inspection results
- Order quantities from supplier and supplier On-Time Delivery Quantity Rate by Inspection results

![image](https://github.com/user-attachments/assets/da18a375-8949-4662-8858-1d24a9eb8e0f)

**3. Inventory Evaluation**
- Stock Availability, Stock Levels, Inventory Turnover Ratio, Days Sales of Inventory, Stock Out Rate
- Stock Levels per warehouse
- Stock levels, Qty Sold and Inventory Turnover Ratio by Product type
- Stock Cost and Stock levels by Product type
- Stock levels, Production volumes, and Avg. Manufacturing lead time by Product type

![image](https://github.com/user-attachments/assets/07fcfb02-5e58-4479-87c5-629182ef9e60)

**4. Order Fulfilment**
- Lowest Order Cycle, Highest Order Cycle, Avrg. Order Cycle , Order on Time Delivery Rate, Order Volume Per Month, Order Fullfilment Time
- Total NO.order delivered on time Vs.Total Order
- Order volume per month, Average of Order Processing Time(Days) and Order On-Time Delivery Rate by Product type
- Order volume per month
- Factors Affecting Order Fulfillment per Product Type
- Order volume Vs. Production volume per warehouse

![image](https://github.com/user-attachments/assets/ab0f85b3-aef6-4be5-881a-ab1fa5f40b40)

**5. Shipping And Logistics**
- Average of Shipping times (day), Shipping Cost
- Average of Shipping times (day) by Transportation modes
-  Shipping  Costs by Shipping carriers
-  Average of Shipping times (day) by Shipping carriers

![image](https://github.com/user-attachments/assets/2da2a515-8d54-440a-8bab-e1e7c1b667fe)

**6. Summary**
Each component is interconnected, forming a continuous feedback loop. A weak supplier disrupts production, leading to inventory shortages, order delays, and logistical inefficiencies. Conversely, an optimized evaluation process ensures a smooth, cost-effective, and reliable supply chain, improving customer satisfaction and business profitability.

![image](https://github.com/user-attachments/assets/ccecc025-6ef1-4d77-b6e1-20cc0c344ca2)

**7. Sales Overview**
- Avrg.Price, Total Sales, Total Cost, Total Profit, Profit Margin %, Qty Sold, Total No. order
- Total cost, Total Sales, Total profit and Profit Margin% by Product type
- No. of products per category
- Total Sales & Profit by Product Type with inventory turnover
- Qty Sold and Total Sales by Product type

# Data Processing, Model View, and Calculations 
 ![image](https://github.com/user-attachments/assets/0a2a2649-238b-4d9b-98f8-895e4aa8313a)

This Power BI dashboard leverages several key tools and technologies to perform data transformations and calculations:

- **Power Query:** Used for data importation and transformation, Power Query enables the cleaning, shaping, and loading of data from various sources into the Power BI environment. This process ensures that the data is in the correct format for analysis.

- **DAX (Data Analysis Expressions):** DAX is utilized for creating custom calculations and measures within the dashboard. It allows for advanced data modeling and enables the creation of dynamic calculations that respond to user interactions and filter selections.

- **Data Modeling:** The relationships between different data tables are established to create a comprehensive data model. This ensures accurate insights and visualizations throughout the dashboard.
