Supply Chain Performance Analysis Dashboard

Overview:
This project analyzes supply chain operations to uncover insights related to delivery delays, profitability,
and regional performance. The data was cleaned and processed using Python, 
and an interactive dashboard was built in Tableau to support business decision-making.

Objectives:
- Analyze delivery performance across shipping modes
- Identify factors impacting profitability and delays
- Evaluate regional and product category performance
- Build an interactive dashboard for stakeholders

Tech Stack:
- Python (Pandas, NumPy) – Data cleaning & preprocessing
- Tableau – Data visualization & dashboarding
- Excel/CSV – Data source

Data Processing:
- Handled missing values and inconsistent data
- Converted date columns and created time-based features
Engineered new features:
   - Order Processing Time
   - Delay (Actual vs Scheduled shipping)
   - Is Delayed (True/False)
   - Profitability Flag (Profit / Loss / Breakeven)

Dashboard Features:
- KPI Cards: Total Orders, Total Profit, Avg Delivery Delay
- Profit vs Delay Analysis (Scatter Plot)
- Top Product Categories by Profit (Bar Chart)
- Average Delivery Delay by Shipping Mode
- Regional Order Volume Analysis
- Order Trends & Delay Over Time

Key Insights:
- Second Class shipping recorded the highest number of delayed orders
- Delivery delays have a direct negative impact on profitability
- A few product categories contribute disproportionately to total profit
- Certain regions show high order volume but higher delays, indicating operational inefficiencies
