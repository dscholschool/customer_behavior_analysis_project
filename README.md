**Customer Behavior Analysis Project**

📝 Overview
This project analyzes consumer shopping patterns and demographic behavior. By visualizing key metrics like subscription status, age groups, and gender, the dashboard helps businesses identify their most valuable customer segments and understand which product categories drive the most engagement.

📊 Dataset
Source: Customer Shopping Behavior Dataset by Amlan Mohanty.

Key Features: Customer ID, Age, Gender, Category (Clothing, Accessories, etc.), Purchase Amount, Review Rating, and Subscription Status.

🛠 Tools & Technologies
Python (Pandas/Matplotlib): Performing Initial Data Discovery and handling demographic grouping.

SQL: Aggregating total revenue and sales counts by category and gender.

Power BI: Building an interactive demographic profile dashboard.

🚀 Steps Performed
Demographic Binning: Categorized customers into age groups: Young People, Mid-aged, Adult, and Elder to find purchasing trends.

Subscription Analysis: Calculated the ratio of subscribed vs. non-subscribed members (27% vs 73%).

Revenue vs. Volume Mapping: Created dual charts to compare Total Revenue (Value) vs. Sales (Quantity) for each product category.

Gender Impact Study: Visualized the revenue split between Male and Female customers using Donut charts.

📈 Key Results (Insights)
Dominant Category: Clothing is the clear winner, generating the highest revenue ($0.10M) and sales volume (1.7K).

Core Demographic: Young People are the leading revenue contributors ($62K), followed closely by the Mid-aged group.

Gender Spend: Male customers contribute significantly more to total revenue ($68K vs $31K from Females).

Satisfaction Check: The average review rating stands at 3.75, indicating a generally positive but improvable customer experience.

💻 How to Run
Clone this repository.

Open the .pbix files (Customer_Behavior_Dashboard) in Power BI Desktop.

Check the /notebooks folder for Python EDA and /sql folder for data aggregation queries.
