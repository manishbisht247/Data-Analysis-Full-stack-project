\# Global Electronics Retailer — Business Intelligence \& Analytics



An end-to-end data analytics project exploring sales performance, product profitability, customer behavior, geographic trends, and delivery operations using \*\*Python, Pandas, and Power BI\*\*.



\## Project Overview



This project analyzes the Global Electronics Retailer dataset from Maven Analytics, representing a fictional global electronics retailer. The objective is to transform raw data into meaningful business insights through data cleaning, data modeling, DAX measures, interactive dashboards, and business recommendations.



\## Business Objectives



\- Analyze overall sales, profit, and profit margins.

\- Identify top-performing products, categories, and brands.

\- Compare performance across countries and sales channels.

\- Understand customer purchasing patterns by age and gender.

\- Investigate monthly sales trends and year-over-year growth.

\- Examine delivery-time trends for online orders with available delivery dates.

\- Develop actionable business recommendations.



\## Tools \& Technologies



\- \*\*Python\*\* — Data auditing, cleaning, transformation, and validation

\- \*\*Pandas\*\* — Data manipulation and preparation

\- \*\*Power BI\*\* — Data modeling, visualization, and interactive dashboards

\- \*\*DAX\*\* — KPI calculations and time-intelligence measures

\- \*\*CSV\*\* — Cleaned dataset storage and transfer



\## Project Workflow



1\. \*\*Business Understanding:\*\* Defined business objectives and analytical questions in the Business Requirements Document (BRD).

2\. \*\*Data Auditing:\*\* Checked dataset dimensions, data types, missing values, duplicates, key uniqueness, and data consistency.

3\. \*\*Data Cleaning:\*\* Used Python and Pandas to clean, transform, and validate the datasets.

4\. \*\*Data Modeling:\*\* Imported cleaned data into Power BI and established relationships between tables.

5\. \*\*DAX Analysis:\*\* Created measures for sales, cost, profit, profit margin, orders, average order value, growth rates, and product rankings.

6\. \*\*Dashboard Development:\*\* Built interactive Power BI report pages with KPI cards, charts, and slicers.

7\. \*\*Business Insights:\*\* Interpreted findings and developed recommendations.



\## Dataset



The project uses the Maven Analytics \*\*Global Electronics Retailer\*\* dataset, which contains multiple related tables:



\- Customers

\- Sales

\- Products

\- Stores

\- Exchange Rates

\- Data Dictionary



The sales table contains \*\*62,884 records\*\*.



Dataset source: \[Maven Analytics — Global Electronics Retailer](https://mavenanalytics.io/data-playground)



\*Refer to the dataset publisher's license and terms before redistributing source or cleaned data.\*



\## Dashboard Previews



\### 1. Executive Sales Overview



Provides a high-level view of sales, profit, profit margin, orders, monthly sales trends, country performance, and category performance.



!\[Executive Sales Overview](screenshots/executive-overview.png)



\### 2. Product \& Customer Analysis



Explores top products by sales, category-level profit margins, sales by gender, and sales by customer age group.



!\[Product and Customer Analysis](screenshots/product-customer-analysis.png)



\## Key Business Insights



\- \*\*Product performance:\*\* Computers lead in total sales and profit, while Music, Movies and Audio Books has the highest reported category-level profit margin.

\- \*\*Geographic performance:\*\* The United States leads in total sales and profit, while Canada has the highest reported profit margin.

\- \*\*Sales channels:\*\* Offline stores generate higher total sales and profit than the online store.

\- \*\*Customer behavior:\*\* Male and female customers contribute almost equally to sales and profit. Customers aged 75+ generate the highest total sales and profit among age groups.

\- \*\*Sales trends:\*\* Sales generally decline toward April and recover afterward; this pattern requires further validation before being treated as confirmed seasonality.

\- \*\*Delivery performance:\*\* Recorded online-order delivery times suggest an improvement from approximately seven days in 2016 to four days in 2021. Results must be interpreted in light of incomplete delivery-date coverage.



\## Key DAX Measures



\- Total Sales

\- Total Cost

\- Profit

\- Profit Margin %

\- Total Orders

\- Total Customers

\- Average Order Value

\- Average Units per Order

\- Sales Previous Year

\- YoY Sales Growth %

\- Sales Previous Month

\- MoM Sales Growth %

\- MTD Sales

\- YTD Sales

\- Profit per Order

\- Product Sales Rank



\## Data Limitations



\- Approximately 79% of sales records have no delivery date. Delivery-time analysis is therefore restricted to eligible online orders with recorded delivery dates, and results may not represent every online order.

\- Product unit prices and costs are treated as USD-denominated in the current model.

\- Observed trends show associations and patterns, not necessarily causal relationships.

\- Reported findings should be validated against the underlying model before being used for operational decisions.



\## Project Documentation



The `docs/` folder contains the Business Requirements Document and final project report.



\## Repository Structure



```text

Global-Electronics-Retailer/

├── data/

├── python/

├── powerbi/

├── screenshots/

├── docs/

└── README.md

```



\## Conclusion



This project demonstrates an end-to-end analytics workflow, from Python-based data preparation to Power BI modeling, DAX analysis, interactive reporting, and business recommendations. It highlights how data analytics can help organizations understand performance and identify areas for further investigation.



\---



\*\*Project Type:\*\* Data Analytics / Business Intelligence  

\*\*Tools:\*\* Python, Pandas, Power BI, DAX  

\*\*Dataset:\*\* Maven Analytics — Global Electronics Retailer



