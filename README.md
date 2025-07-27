AltiQ-hardware-Powerbi-Dashboard

Problem Statement
AtliQ Hardware, a company that supplies computer hardware and peripherals across India, was facing a major challenge: declining sales and an unclear understanding of business performance. The Sales Director found it difficult to analyze trends and patterns through raw Excel reports, and regional managers often struggled to communicate actionable insights from data-heavy spreadsheets.

✅ Solution
To overcome these challenges, AtliQ Hardware decided to implement a Power BI Sales Dashboard that converts raw sales data into actionable insights through intuitive visualizations. A dedicated data team (myself included) was tasked with building this dashboard to support data-driven decision-making.

🗂 Project Planning: AIMS Grid
Using the AIMS grid project management framework, we defined the following:

Aim: Improve decision-making by visualizing key sales metrics

Involvement: Sales Directors, Regional Managers, Analysts

Means: Power BI, MySQL, DAX, Power Query

Success Criteria: Improved understanding of regional and product-wise performance, actionable insights from visuals

🛠️ Tools & Technologies
Power BI

MySQL (for data retrieval)

Power Query (for data cleaning and transformation)

DAX (for creating calculated columns, measures, and KPIs)

🔄 ETL Process Overview
Data Extraction: Pulled relevant data from MySQL into Power BI

Data Cleaning & Transformation: Used Power Query to clean and normalize data

Currency Standardization: Unified multi-currency records into a single currency

Data Modelling: Established relationships between tables for accurate aggregation

DAX Measures: Created custom KPIs like Revenue, Profit Margin %, Contribution %, etc.

Validation: Ensured accuracy by comparing results with raw data

🔧 Customizations & Fixes
Replaced original products table with a custom one (Prod280–Prod339) with correct categories (‘Own Brand’ and ‘Distribution’)

Merged updated sales_transaction table to include new attributes such as profit margin, cost price, etc.

Resolved “(Blank)” issue in product visual by data restructuring

📈 Key Insights from Dashboard
Overall Revenue (4 years): ₹985M

Total Profit Margin: ₹24.7M (2.5%)

Total Sales Quantity: 2M units

📍 Market-Wise Analysis
Top Market (Revenue): Delhi NCR – ₹520M (52.8% revenue share), but only 2.3% profit margin

Top Market (Profit Margin): Bhubaneshwar – 10.48% (in 2020)

Top Market (Profit Contribution): Mumbai – 23.89% of total profit

Lowest Market: Bengaluru – negative profit margin of -20.8%

👥 Customer & Product Insights
Top Customer: Electricalsara Stores – ₹413M revenue

Top Product: Prod318 – ₹69M revenue

Product Type Revenue: Distribution – ₹494M, Own Brand – ₹494M

📉 Trend Analysis
Revenue dropped significantly in June 2020

April 2020 marked the lowest profit margin

📚 Key Learnings
Understood the structure of real-world sales data

Practiced writing complex MySQL queries for business analysis

Learned Power BI data modeling, data transformation, and visual storytelling

Mastered essential DAX functions and calculations

Developed a practical, business-oriented dashboard with KPIs and actionable insights

🧠 What I Gained
This project enhanced my practical skills in BI development, data storytelling, and end-to-end dashboard creation using industry-relevant tools. It also strengthened my ability to translate messy data into clear business insights.
