# Power BI Financial Report

## Table of Contents:

 - [Project Overview](#project-overview)
 - [Data Sources](#data-sources)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Results](#results-and-findings)
 - [Dashboard](#dashboard)
   
### Project Overview
This financial data analysis project aims to build a comprehensive overview of profit and sales performance across various products and business segments from January 2013 to December 2014. The primary goal was to create an interactive and visually compelling report in Power BI, allowing users to explore key financial metrics such as profit trends, regional performance, and product segmentation. The report helps stakeholders track performance and make data-driven decisions based on insights provided by the visualizations.

### Data Sources
The main dataset used in this analysis is the [Financial_Sample.xlsx](./Financial_Sample.xlsx) file, which contains detailed records of profit, sales, product categories, business segments, and country-based performance.

### Tools
**Power BI Desktop:** Used for data transformation, report creation, and visualization. <br />
**Power BI Service:** Deployed to share the report for collaboration.

### Data Cleaning and Preparation
The [Financial_Sample.xlsx](./Financial_Sample.xlsx) file was imported into Power BI, and key transformations were applied to ensure data consistency. This included formatting columns like **Units Sold** and **Segment**, filtering out discontinued products, and renaming columns for clarity. A **Calendar Table** was created to facilitate time-based analysis, and relationships were established to ensure the data could be properly visualized across different dimensions. These steps set the foundation for building accurate and insightful reports.

### Exploratory Data Analysis
The dashboard allows users to explore key questions related to financial performance:

1) **Profit Trends Over Time:** Which months and years recorded the highest profits?<br />
2) **Regional Success:** Which countries or regions contribute the most to overall profits?<br />
3) **Product & Segment Investment:** Which products and business segments should the company continue to invest in for optimal returns?<br />
4) **Sales Distribution:** How are sales distributed across different products and segments?<br />

These guiding questions enable users to make informed business decisions by filtering and drilling down into the data.

### Results and Findings
The final Finance Report Dashboard contains several interactive visuals, which provide key insights into the financial performance across different dimensions:

1) **Profit by Country (Map Visual):** Displays profit data by geographical region, with larger bubbles indicating higher profits. This visual highlights key regions like Europe (France and Germany) and Canada as strong performers.
2) **Profit by Month and Year (Line Chart):** Shows profit trends over time, clearly indicating that December 2014 was the most profitable month.
3) **Sales by Product and Segment (Stacked Column Chart):** This chart compares the sales performance of various products across different segments (e.g., Channel Partners, Government, Small Business). For instance, the Paseo product and Small Business and Government segments are identified as key drivers of sales.
4) **Year Slicer:** A slicer on the left allows users to filter the report by year and month, providing flexibility to analyze specific time periods.

This Power BI dashboard provides an interactive and user-friendly tool for analyzing financial performance across time, products, and regions. The report helps decision-makers identify high-performing regions and products while also showing trends in profitability over time. By using the dashboard’s filtering capabilities, users can drill down into specific segments and timeframes to make more informed business decisions.

### Dashboard
The dashboard can be reviewed and interacted with through the provided [Financial_data_analysis.pbix](./Financial_data_analysis.pbix) in Power BI. A screenshot of the dashboard is provided below for reference.

![Financial_report_dashboard](https://github.com/user-attachments/assets/c5387cba-fe4d-4a6f-91d5-7860ae4bf079)


