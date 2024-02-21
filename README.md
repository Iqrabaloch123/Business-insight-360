# Business-insight-360
-- Project Overview --



AtliQ Hardware, experiencing rapid growth, aims to implement Power BI for data-driven decision-making and surpass competitors.
Stakeholders seek answers in finance, sales, marketing, and supply chain.
This project is inspired by the Codebasics Power BI Course (provided link).


-- Key Technologies: --

SQL
Power BI Desktop
Excel
DAX language
DAX Studio (optimization)
Project charter file
Learned Power BI Techniques:

** Questions for project initiation **


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

** Essential Questions: **

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

** Understanding Datasets: **

Dimension Tables: Static data on customers, products, markets, etc.
Fact Tables: Transaction data (forecast/sales) associated with specific periods.
Dataset Details:

** gdb041:**
dim_customer: Customers across 27 markets, platforms (B&M, e-commerce), and channels.
dim_market: 27 markets with sub-zones and regions.
dim_product: 14 categories, variants, and product codes.
fact_forecast_monthly: Customer forecast quantities per month.
fact_sales_monthly: Actual sales quantities per month.
** gdb056:**
freight_cost: Travel and market costs by fiscal year.
gross_price: Product codes with associated gross prices.
manufacturing_cost: Product codes with manufacturing costs by year.
Pre_invoice_deductions: Customer pre-invoice deduction percentages by year.
Post_invoice_deductions: Post-invoice and other deductions details.
**Data Import:**

Import datasets from MySQL using Power BI's connector and credentials.
Data Modeling

Follow the Snowflake method for optimal data relationships and query performance.
![data model](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/588cf6c5-ecd0-4385-92b9-aec7c0e85d38)

** Dashboard designing **
Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

** Home view **
In Home view, all the views button will be available. User will land on specific view page by clicking the button

Info
Finance View
Sales View
Marketing View
Supply chain View
Executive View
Support



** Overall Report **
C:\Users\GB\Downloads\Resources\overall-veiw.gif



** Supply chian **
![supply-chian-veiw](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/7aad4341-fbb7-4730-9534-080087996231)

** finance-Veiw **
![finance-veiw](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/97a2db14-a8b5-438c-a302-8f699f4dbcec)

** Marketing-Veiw **
![Marketing-veiw](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/73ec88b6-2541-4213-bd1c-f04fa4529a47)

** Exceutive-veiw **
![Exceutive-veiw](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/85e4f50a-8ff0-4faa-b8ca-208d27e1ece6)

** Sales Veiw **
![Sales-veiw_1](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/311d382b-dd5b-425e-b216-a89f551a70b0)

** info veiw **
![info-veiw](https://github.com/Iqrabaloch123/Business-insight-360/assets/130351579/42235974-368c-4714-875e-da6d0224b229)

you can find the full report file here : Report

** Project Outcome **
By using this report, decisions can be taken based on the data. Further it will help in answering n number of why questions based on the situations.


