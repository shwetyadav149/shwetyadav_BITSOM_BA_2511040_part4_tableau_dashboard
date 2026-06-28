# Retail Executive Performance Dashboard

## Business Problem
The objective of this project is to develop an executive Tableau dashboard that enables retail leadership to monitor sales performance, profitability, customer behavior, shipping performance, discount impact, and return patterns for better business decision making.

## Dataset Description
The dataset contains retail transaction information including sales, profit, discounts, customer segments, shipping details, regions, categories, and return information.

## Tableau Workbook
The dashboard was developed using Tableau and saved as a Tableau Packaged Workbook (.twbx) containing all data sources and visualizations.

Workbook:
tableau/executive_dashboard.twbx

## Calculated Fields
The following calculated fields were created:

- Profit Margin = Profit / Sales
- Cost = Sales - Profit
- Average Order Value = Sales / Number of Orders
- Return Rate = Returned Orders / Total Orders
- Shipping Delay Bucket
- Discount Bucket
- Delivery Status

## Dashboard Components
The dashboard includes:

- Sales Trend Analysis
- Regional Performance Analysis
- Category Profitability Analysis
- Customer Segment Analysis
- Shipping Performance Analysis
- Discount vs Profit Analysis
- Return Pattern Analysis

## KPI Cards
- Total Sales
- Total Profit
- Profit Margin
- Return Rate
- Average Order Value

## Filters and Interactions
The dashboard includes the following interactive filters:

- Region
- Category
- Customer Segment
- Date
- Ship Mode
- Campaign Channel

Dashboard actions allow users to filter multiple visualizations by selecting a specific region or category.

## Key Business Insights
- Sales increase during seasonal periods.
- Certain regions outperform others in profitability.
- High discounts negatively impact profit margins.
- Delivery delays vary by shipping method.
- Return patterns differ across customer segments.

## Dashboard Story Summary
The dashboard identifies business strengths, operational risks, and growth opportunities across the retail business.

## Assumptions and Limitations
- Historical data may not represent future performance.
- External market factors are not included.
- Customer satisfaction metrics were unavailable.

## Screenshots Included
- full_dashboard.png
- sales_trend_view.png
- regional_performance_view.png
- category_profitability_view.png
- filter_interaction_view.png