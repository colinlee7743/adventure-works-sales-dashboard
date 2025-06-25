# Adventure Works Sales Dashboard Using Excel

## 📌 Project Overview
A comprehensive Excel-based sales analytics dashboard analysing Adventure Works' business performance from 2022-2024, revealing a successful strategic transformation from premium niche to mass-market leader with 189% growth across all key financial metrics.

## 🔍 Key Business Insights
- **189% Growth**: Revenue, profit, and costs all increased by approximately 189% 
- **Maintained Profitability**: Profit margins remained robust at 41.3% despite massive scaling
- **16x Volume Growth**: Unit sales increased from 33.5K to 552.5K units
- **Strategic Pivot**: Successfully transformed from premium ($18K AOV) to mass-market ($3K AOV) without sacrificing profit margin

## 📊 Dashboard Features
**Main Dashboard Tab**
- **Financial KPIs**: Total revenue, profit margin, total profit, total cost, AOV (Average Order Value), units sold with year-over-year changes
- **Interactive Filtering**: Financial year slicer (2022-2024) for dynamic analysis
- **Multi-Metric Charts**: Radio button selection for revenue, profit and cost by year, month and day of week pattern
- **Temporal Analysis**: Revenue, profit and profit margin by quarter and country

![Sales Dashboard](images/sales_dashboard.png)

**Product Analysis Tab**
- **Repeated KPIs**: Core financial metrics for quick reference
- **Product Performance**:
  - Profit by product category analysis
  - Product pricing type segmentation (Low <$100, Medium $100-$1000, High >$1000)
  - Unit sales distribution by pricing tiers

![Customer Dashboard](images/customer_dashboard.png)

## 🛠️ Technical Skills Demonstrated
- **Pivot Tables**: Multi-dimensional data aggregation with calculated fields and automated chart generation for comprehensive sales analysis
- **Power Pivot**: Data model management with custom DAX measures for KPI calculations and advanced analytics
- **Power Query (ETL)**: Data transformation and cleansing workflows for consistent reporting and analysis
- **Advanced Formulas**: INDEX-MATCH, VLOOKUP and IF statements for data retrieval and conditional logic
- **KPI & Visualisation**: Performance metric tracking with year-over-year comparisons and dynamic visualisations with trend analysis
- **Interactive Slicers**: Cross-filtering functionality enabling dynamic dashboard filtering across multiple visualisations

## 📦 Repository Structure
```
adventure-works-sales-dashboard/
│
├── datasets/                      # Raw datasets used for the project 
│   ├── AdventureWorks.xlsx        # FactInternetSales, DimProduct, DimSalesTerritory, DimDate, DimCustomer, DimGeography
|
├── images/                        # Dashboard images
│   ├── main_dashboard.png         # Main dashboard image
│   ├── product_dashboard.png      # Product dashboard image
│
├── LICENSE                        # License information for the repository
├── README.md                      # Project overview and information
├── Sales_Dashboards.xlsm          # Excel dashboard
```
