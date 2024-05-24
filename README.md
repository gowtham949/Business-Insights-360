
# Business Insights 360 Report

## Overview

The "Business Insights 360 Report" is a comprehensive Power BI report designed to provide an in-depth analysis of key business metrics and performance indicators. This report aims to offer a 360-degree view of the business, facilitating data-driven decision-making and strategic planning.

Live Report: [Business Insights 360](https://app.powerbi.com/links/9lMnN7XlPp?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare)

## Contents

The report contains several pages, each focusing on different aspects of business performance:

1. **Executive Summary**
   - Key performance indicators (KPIs)
   - High-level business insights
   - Trends and forecasts

2. **Sales Analysis**
   - Sales performance by region, product, and time period
   - Sales trends and seasonality
   - Top performing products and services

3. **Financial Overview**
   - Revenue and expense breakdown
   - Profit and loss statement
   - Financial ratios and metrics

4. **Customer Insights**
   - Customer demographics and segmentation
   - Customer acquisition and retention metrics
   - Customer satisfaction and feedback

5. **Operational Efficiency**
   - Process performance metrics
   - Resource utilization
   - Supply chain and logistics analysis

6. **Marketing Performance**
   - Campaign performance and ROI
   - Digital marketing metrics
   - Lead generation and conversion rates

## Getting Started

### Prerequisites

- Power BI Desktop installed on your computer
- Access to the relevant data sources (e.g., databases, Excel files, cloud services)
- Proper permissions to access and refresh the data

### Data manuplation
Dataset Understanding
We are pulling data from 2 sources : MySQL and Excel

We have 2 databases containing the following tables:

gdb041:
dim_customer
27 distinct markets (ex India, USA, Spain)
75 distinct customers throughout the market
2 types of platforms
Brick & Motors - Physical/offline store
E-commerce - Online Store (Amazon, Flipkart)
Three channels
Retailer
Direct
Distributors
dim_market
27 distinct markets (ex India, USA, Spain)
7 sub-zones
4 regions
dim_product
Divisions
P & A
PC
N & S
fact_forecast_monthly
This table is used to forecast the customer’s needs in advance
fact_sales_monthly
This table contains the sold quantity.
gdb056
freight_cost
gross_price
manufacturing_cost
Pre_invoice_dedutions
Post_invoice_deductions
We are importing 3 Excel files as well:

MarketShare: AtliQ and its competitors market share
Operational Expenses: Ads & promotions and other expenses percentage per market
targets: AtliQ's NS, GM, NP target data

### Tech stacks
Tools used in this project:
SQL
PowerBi Desktop
Excel
DAX language
DAX studio (for optimizing the report)
Project charter file

### Using the Report

- **Navigating the Report**: Use the navigation pane on the left to switch between different report pages.
- **Interacting with Visuals**: Click on charts, graphs, and tables to filter data and drill down into specific details.
- **Exporting Data**: You can export the data and visuals by right-clicking on the visual and selecting the export option.

## Customization

The report is designed to be easily customizable to fit your specific needs:

- **Adding New Data Sources**: Go to `Home > Transform data` to add or modify data sources.
- **Creating New Visuals**: Use the `Visualizations` pane to create new charts and graphs.
- **Updating Filters**: Adjust the filters in the `Filters` pane to refine the data displayed.

## Support

If you encounter any issues or have any questions about the report, please contact:

- **Email**: support@yourcompany.com
- **Phone**: +1-800-123-4567

## Version History

- **v1.0** - Initial release
- **v1.1** - Minor bug fixes and performance improvements
- **v1.2** - Added new page for marketing performance

## License

This report is licensed under the [Your License Here].

## Acknowledgements

We would like to thank the data analysis and IT teams for their support in creating this report.

---

Feel free to modify the content to better suit your specific report and organizational details.
