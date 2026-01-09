📊 Customer Churn Analysis (EDA & Insights)
📌 Project Overview
Customer churn is a critical business problem where customers stop using a company’s services. This project focuses on analyzing customer churn patterns using exploratory data analysis (EDA) to identify key factors influencing churn and provide data-driven business insights.
The analysis is performed on a telecom customer dataset containing demographic details, service usage, contract information, and payment behavior.

🎯 Objectives

Understand the overall churn rate
Identify high-risk customer segments
Analyze churn impact based on:
Contract type
Internet service
Payment methods
Customer demographics
Provide actionable insights for reducing churn
🗂 Dataset Description
Total Customers: 7,043
Target Variable: Churn (Yes / No)
Key Features:
Customer demographics (Gender, Senior Citizen)
Service details (Internet Service, Streaming, Tech Support)
Contract information (Month-to-Month, One-Year, Two-Year)
Payment methods and billing details

🔍 Key Insights & Findings
🔹 Overall Churn

26.5% customers churned

73.5% customers retained

Indicates that 1 in every 4 customers leaves, making churn reduction a priority.

🔹 Contract Type & Churn
Contract Type	Churn Rate
Month-to-Month	42.7%
One-Year	11.3%
Two-Year	2.8%

📌 Customers on long-term contracts are significantly more loyal.

🔹 Internet Service Analysis
Internet Service	Churn Rate
Fiber Optic	41.9%
DSL	19.0%
No Internet	7.4%

📌 Fiber Optic customers show the highest churn despite premium pricing.

🔹 Payment Method Impact
Payment Method	Churn Rate
Electronic Check	45.3%
Credit Card (Auto)	15.2%
Bank Transfer (Auto)	16.7%

📌 Automatic payment users are more stable and less likely to churn.

📊 Visualizations Used
Countplots with churn distribution
Stacked bar charts showing percentage churn
Subplots for service-based feature comparison
These visualizations help identify patterns and risk segments quickly.

💡 Business Recommendations
Promote long-term contracts with incentives
Improve service quality and pricing transparency for Fiber Optic users
Encourage automatic payment methods to increase customer retention
Target high-risk segments with personalized retention campaigns

🛠 Tools & Technologies
Python
Pandas & NumPy
Matplotlib & Seaborn
Jupyter Notebook
