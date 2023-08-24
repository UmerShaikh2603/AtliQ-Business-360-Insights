# AtliQ-Business-360-Insights
The "AtliQ-Business-360-Insights" project provides meaningful business insights and also hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain. 
## About AtliQ Hardware
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel
- Retailers: An entity that purchases products from manufacturers or wholesalers and sells them to consumers, often through physical or online stores.
- Direct:  A sales channel where products are sold directly from the manufacturer or company to the end consumer without intermediaries.
- Distributors: Entities that purchase products in bulk from manufacturers and then sell them to retailers or other businesses. They help bridge the gap between manufacturers and retailers.


Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry. 

### Dataset **Understanding.**
### `gdb0`
### `dim_customer`
- Contains details of customers across markets and platforms.
- 27 distinct markets.
- 75 distinct customers.
- 2 types of platforms: Brick & Mortar (Physical/offline store), E-commerce (Online Store).
- Three channels: Retailer, Direct, and Distributors.

### `dim_market`
- Contains details of markets, sub-zones, and regions.
- 27 distinct markets.
- 7 sub-zones.
- 4 regions: APAC, EU, NA, LATAM.

### `dim_product`
- Contains details of product divisions, categories, and variants.
- Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage.
- 14 different categories (e.g., Internal HDD, keyboard).
- Different variants available for the same product.

### Fact Tables

### `fact_forecast_monthly`
- Used for forecasting customer needs in advance.
- Helps improve customer satisfaction and reduce warehouse storage costs.
- Denormalized for analytical use.
- Date of the month replaced by start date.
- Columns include forecast quantity needed by the customer.

### `fact_sales_monthly`
- Similar to `fact_forecast_monthly` with actual sold quantities.

### `gdb056`
- `freight_cost`: Details of travel and other costs for each market by fiscal year.
- `gross_price`: Details of gross prices with product code.
- `manufacturing_cost`: Details of manufacturing costs with product code and year.
- `Pre_invoice_dedutions`: Details of pre-invoice deduction percentages for each customer by year.
- `Post_invoice_deductions`: Details of post-invoice and other deductions.


## Data Model
- Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- In this project, we have followed Snowfall data modeling method.

## Dashboard 
To find the interactive dashboard [** click here**](https://app.powerbi.com/view?r=eyJrIjoiZGJjNTgyMzktZGZjNi00ZjM4LWI5NmMtZmRmM2YzZWI5M2FmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

The dashboard contains following views :

## Home View
![Home](https://github.com/UmerShaikh2603/AtliQ-Business-360-Insights/assets/113358829/5b08bf2d-0215-44ae-9395-b93907a43319)

## Finance View
![Finance view](https://github.com/UmerShaikh2603/AtliQ-Business-360-Insights/assets/113358829/76d8d8d5-e7b1-4f33-b0d8-e27e7929adf2)

## Sales View
![Sales view](https://github.com/UmerShaikh2603/AtliQ-Business-360-Insights/assets/113358829/68da6395-090c-4903-beee-1025b5d4f2dc)

## Marketing View
![Marketing view](https://github.com/UmerShaikh2603/AtliQ-Business-360-Insights/assets/113358829/01669ce5-f6bf-4651-ae52-fb2bbba7c21f)

## Supply Chain View
![Supply Chain view](https://github.com/UmerShaikh2603/AtliQ-Business-360-Insights/assets/113358829/af0aa80e-a5dc-46f9-b62e-4aa3838b5ad8)

## Executive View
![Executive view](https://github.com/UmerShaikh2603/AtliQ-Business-360-Insights/assets/113358829/516c85c3-d022-4044-b481-9fe42df96e7d)




