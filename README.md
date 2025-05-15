# OLA_Data_Analysis_Power-BI
🚗 Ola Data Analyst Project
📋 Overview
Welcome to the Ola Data Analyst Project, where we analyze Ola ride bookings using a combination of SQL queries and Power BI dashboards. Our goal is to gain insights into booking statuses, cancellations, ride distances, and customer/driver ratings.

🚀 Project Workflow
1. SQL Analysis
We start with PostgreSQL queries to retrieve and manipulate data for key business metrics. These queries allow us to answer questions such as ride volume, cancellation reasons, and average ride distances.

2. Power BI Dashboards
The output from SQL queries is visualized using Power BI to create interactive, insightful dashboards that provide a clear picture of the ride booking patterns.

📊 Power BI Dashboard Insights
1. Overall Ride Volume Over Time
A time-series chart showing the number of rides per day/week.

2. Booking Status Breakdown
A pie or doughnut chart showing the proportion of different booking statuses (Success, Cancelled by Customer, Cancelled by Driver).

3. Top 5 Vehicle Types by Ride Distance
A bar chart ranking vehicle types based on the total distance covered during the month.

4. Average Customer Ratings by Vehicle Type
A column chart displaying the average customer ratings for each vehicle type (Auto, Prime Sedan, Mini, etc.).

5. Cancelled Ride Reasons (Customer vs. Driver)
Bar charts illustrating the most common reasons for cancellations by both customers and drivers.

6. Revenue by Payment Method
A stacked bar chart showcasing the total revenue split by payment methods (Cash, UPI, Credit Card).

7. Top 5 Customers by Total Booking Value
A leaderboard visual highlighting the customers who spent the most on bookings.

8. Ride Distance Distribution
A scatter plot showing the distribution of ride distances over time.

9. Driver Ratings
A box plot visualizing the distribution of driver ratings for different vehicle types.

🛠️ Problem-Solving Approaches
Handling Missing Data:

SQL was used to filter out incomplete or missing ride data by focusing on successful bookings.
Power BI visuals were set to ignore null values in charts, ensuring clean visualizations.
Dealing with High Cancellation Rates:

Identified the cancellation patterns by both customers and drivers through SQL queries.
Power BI breakdown charts allowed for better understanding of peak cancellation reasons.
Optimizing Performance for Large Data:

Aggregation techniques in SQL (e.g., GROUP BY, AVG()) reduced the data complexity.
Power BI slicers and filters were implemented to refine data views for large datasets.
⚡ Conclusion
This project provided key insights into Ola's ride bookings for a month. We leveraged SQL for detailed data extraction and analysis, while Power BI allowed us to visualize the data effectively. The final dashboard helps in understanding customer behaviors, vehicle preferences, and cancellation reasons, enabling more informed decision-making for business improvements.

