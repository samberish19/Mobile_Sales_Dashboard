# Mobile Sales Analytics Dashboard

## Project Overview
An end-to-end Power BI business intelligence solution for analyzing mobile device sales performance. This dashboard transforms raw sales data into actionable insights through interactive visualizations and automated reporting.

## Technical Specifications

### Data Pipeline
- Processed 15,000+ transaction records from multiple sources
- Implemented Power Query transformations for data cleaning
- Built star schema data model with 4 dimension tables
- Configured daily automated refresh cycle

### Core Features
- Sales performance tracking by product category
- Regional sales analysis with geographic mapping
- Customer segmentation by purchase behavior
- Inventory turnover and product margin analysis

### Visualization Components
1. **Sales Overview**
   - Revenue and units sold KPIs
   - YoY comparison metrics
   - Market share analysis

2. **Product Performance**
   - Top/bottom performing products
   - Category/subcategory breakdown
   - Margin analysis

3. **Geographic View**
   - Regional sales heatmap
   - Store performance benchmarking
   - Delivery time analysis

## Setup Instructions

1. **Requirements**
   - Power BI Desktop (latest version)
   - Read access to sales data sources

2. **Installation**
   - Clone this repository
   - Open `MS_Dashboard.pbix` in Power BI Desktop
   - Configure data source credentials if needed
   - Refresh dataset

3. **Usage**
   - Use page navigator to switch between reports
   - Apply filters using the sidebar controls
   - Click visual elements to cross-filter data

## Repository Structure
Mobile_Sales_Dashboard/
├── Data/ # Processed data files
├── Documents/ # Project documentation
├── Exports/ # Report exports
├── Assets/ # Images and screenshots
└── Mobile_Sales.pbix # Main Power BI file


## Key Insights
1. Premium devices generate 65% of revenue from 25% of units sold
2. Northeast region shows 18% higher ASP than national average
3. Sales increase by 40% during holiday weeks

## Technologies Used
- Microsoft Power BI
- Power Query (M language)
- Data modeling (star schema)
- Advanced visualizations

---
