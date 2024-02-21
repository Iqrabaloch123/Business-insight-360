# Business-insight-360
Project Overview



AtliQ Hardware, experiencing rapid growth, aims to implement Power BI for data-driven decision-making and surpass competitors.
Stakeholders seek answers in finance, sales, marketing, and supply chain.
This project is inspired by the Codebasics Power BI Course (provided link).


Key Technologies:

SQL
Power BI Desktop
Excel
DAX language
DAX Studio (optimization)
Project charter file
Learned Power BI Techniques:

Questions for project initiation


Calculated columns and DAX measures
Data modeling (Snowflake method)
Bookmarks and page navigation
Error prevention (divide function)
Date tables (M language)
Dynamic titles and KPI indicators
Conditional formatting
Data validation
Power BI services
Report publishing, auto-refresh, and app creation
Collaboration in workspaces
Additional Skills:

GitHub usage (large files, LFS, file extensions)
Business-related terms (gross price, deductions, sales, COGS, YTD/YTG, channels)
Company background and challenges
Project Kick-Off Session

Essential Questions:

Objective: What are the specific goals of building this Power BI dashboard?
Success Measurement: How will we determine project success (e.g., metrics, targets)?
Timeline: What is the project deadline?
Stakeholder Previews: Are pre-release previews desired?
Stakeholder Expectations: What benefits and potential concerns do stakeholders have?
Target Users: Who will use the dashboard and for what purposes?
Post-Project Expectations: What outcomes do stakeholders anticipate?
Potential Risks: What challenges or roadblocks could arise?
Resource Needs: What data, resources, and support are required?
Design Inputs: Are there any design preferences or specifications from stakeholders?
Data Exploration

Understanding Datasets:

Dimension Tables: Static data on customers, products, markets, etc.
Fact Tables: Transaction data (forecast/sales) associated with specific periods.
Dataset Details:

gdb041:
dim_customer: Customers across 27 markets, platforms (B&M, e-commerce), and channels.
dim_market: 27 markets with sub-zones and regions.
dim_product: 14 categories, variants, and product codes.
fact_forecast_monthly: Customer forecast quantities per month.
fact_sales_monthly: Actual sales quantities per month.
gdb056:
freight_cost: Travel and market costs by fiscal year.
gross_price: Product codes with associated gross prices.
manufacturing_cost: Product codes with manufacturing costs by year.
Pre_invoice_deductions: Customer pre-invoice deduction percentages by year.
Post_invoice_deductions: Post-invoice and other deductions details.
Data Import:

Import datasets from MySQL using Power BI's connector and credentials.
Data Modeling

Follow the Snowflake method for optimal data relationships and query performance.

![Screenshot (337)](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/08442eac-a5be-40a2-9f21-9840e5a4c1b1)


