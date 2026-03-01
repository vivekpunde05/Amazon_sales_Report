# Amazon Sales Dashboard

A comprehensive Power BI dashboard for analyzing global e-commerce sales data across multiple markets, providing insights into sales performance, profitability, and key business metrics.

## Project Overview

This project contains an interactive Power BI dashboard that visualizes e-commerce sales data spanning 4 years (2011-2014) with over 51,000 orders across global markets. The dashboard helps stakeholders make data-driven decisions by providing clear insights into sales performance across time periods, product categories, geographic regions, and customer segments.

### Key Metrics at a Glance

- **Total Orders**: 51,290
- **Total Sales**: $12.64M
- **Total Profit**: $1.47M
- **Unique Customers**: 1,590
- **Unique Products**: 10,292
- **Date Range**: January 2011 - December 2014
- **Markets Covered**: APAC, LATAM, EU, US, EMEA

## Files in This Project

- `Amazon Sales Report.pbix` - Main Power BI dashboard file
- `ECOMM DATA.xlsx` - Source data file containing 51,290 sales records
- `Amazon Sales Report.png` - Dashboard preview/screenshot

## Features

The dashboard provides comprehensive analysis across multiple dimensions:

### Sales Performance Metrics
- Total revenue tracking: $12.64M across 4 years
- Profit analysis: $1.47M total profit with margin insights
- Order volume trends: 51,290 orders analyzed

### Time-based Analysis
- 4-year historical data (2011-2014)
- Trends by year, quarter, month, and day
- Seasonal pattern identification

### Product Analysis
- **3 Main Categories**: Office Supplies (61%), Technology (20%), Furniture (19%)
- 10,292 unique products tracked
- Sub-category performance breakdown
- Top-selling products identification

### Geographic Insights
- **5 Global Markets**: APAC, LATAM, EU, US, EMEA
- **Regional Distribution**: Central, South, EMEA, North, Africa, and more
- Country and city-level analysis
- Market share and performance comparison

### Customer Analytics
- **3 Customer Segments**: Consumer (52%), Corporate (30%), Home Office (18%)
- 1,590 unique customers tracked
- Customer behavior and purchasing patterns
- Repeat customer analysis

### Shipping & Operations
- **4 Ship Modes**: Standard Class, Second Class, First Class, Same Day
- Shipping cost analysis
- Delivery performance metrics
- Order priority tracking (Critical, High, Medium, Low)

### Interactive Filters
- Dynamic filtering by date range, product category, region, market, and customer segment
- Cross-filtering across all visualizations
- Drill-down capabilities for detailed analysis

## Requirements

To view and interact with this dashboard, you need:

- **Microsoft Power BI Desktop** (latest version recommended)
  - Download from: https://powerbi.microsoft.com/desktop/
- **Microsoft Excel** (to view/edit the source data file)

## Getting Started

### Opening the Dashboard

1. Install Power BI Desktop if you haven't already
2. Open `Amazon Sales Report.pbix` (double-click or open through Power BI Desktop)
3. The dashboard will load with the data from `ECOMM DATA.xlsx`

### Refreshing Data

1. Open the Power BI file
2. Click on "Refresh" in the Home ribbon
3. Ensure the `ECOMM DATA.xlsx` file is in the same directory or update the data source path

### Updating Data Source Path

If you move the files to a different location:

1. Open Power BI Desktop
2. Go to **Home** → **Transform Data** → **Data Source Settings**
3. Select the Excel data source
4. Click **Change Source** and browse to the new location of `ECOMM DATA.xlsx`
5. Click **OK** and close the settings

## Data Source

The dashboard uses data from `ECOMM DATA.xlsx`, which contains 51,290 e-commerce transaction records from 2011-2014. The dataset includes 24 columns:

### Data Fields

**Order Information**
- ROW ID, Order ID, Order Date, Ship Date
- Ship Mode (Standard Class, Second Class, First Class, Same Day)
- Order Priority (Critical, High, Medium, Low)

**Customer Information**
- Customer ID, Customer Name
- Segment (Consumer, Corporate, Home Office)

**Geographic Data**
- City, State, Country
- Market (APAC, LATAM, EU, US, EMEA)
- Region (Central, South, EMEA, North, Africa, etc.)
- Postal Code

**Product Information**
- Product ID, Product Name
- Category (Office Supplies, Technology, Furniture)
- Sub-Category

**Financial Metrics**
- Sales (Total: $12.64M)
- Quantity
- Discount
- Shipping Cost
- Profit (Total: $1.47M)

## Key Insights from the Data

Based on the 51,290 orders analyzed:

- **Office Supplies dominate** with 61% of all orders, followed by Technology (20%) and Furniture (19%)
- **APAC is the largest market** with 21% of orders, closely followed by LATAM (20%) and EU (19%)
- **Consumer segment leads** with 52% of orders, while Corporate accounts for 30%
- **Standard Class shipping** is most popular (60% of orders)
- **Average profit margin**: 11.6% across all transactions
- **Geographic spread**: Orders from multiple continents with strong presence in Asia-Pacific, Latin America, Europe, and North America

## Dashboard Preview

![Amazon Sales Dashboard](Amazon%20Sales%20Report.png)

## Usage Tips

- Use the built-in filters to drill down into specific time periods, products, or regions
- Hover over visualizations for detailed tooltips
- Click on chart elements to cross-filter other visuals on the page
- Export data or visuals using the "..." menu on each visualization

## Customization

To customize the dashboard:

1. Open the `.pbix` file in Power BI Desktop
2. Enter **Edit** mode
3. Modify visualizations, add new charts, or adjust filters as needed
4. Save your changes

## Best Practices

- **Regular Updates**: Refresh the data regularly to keep insights current
- **Data Backup**: Keep backups of both the `.pbix` and `.xlsx` files
- **Version Control**: Save versions with dates when making significant changes
- **Documentation**: Document any custom measures or calculated columns you add

## Troubleshooting

### Dashboard Won't Open
- Ensure you have Power BI Desktop installed
- Check that the file isn't corrupted
- Try opening Power BI Desktop first, then opening the file from within the application

### Data Not Refreshing
- Verify the Excel file path is correct
- Check that the Excel file isn't open in another application
- Ensure you have read permissions for the data file

### Performance Issues
- Reduce the date range being analyzed
- Consider aggregating data at a higher level
- Optimize DAX measures if custom calculations are slow

## Future Enhancements

Potential improvements for this dashboard:

- **Predictive Analytics**: Sales forecasting using historical trends (2011-2014 data)
- **Profitability Analysis**: Deep dive into profit margins by category and region
- **Customer Segmentation**: Advanced RFM (Recency, Frequency, Monetary) analysis
- **Market Comparison**: Benchmark performance across the 5 global markets
- **Product Performance**: Identify top and bottom performers across 10,292 products
- **Shipping Optimization**: Analyze shipping costs vs. delivery speed trade-offs
- **Time Series Analysis**: Seasonal trends and year-over-year growth patterns
- **Mobile Optimization**: Create mobile-friendly views for on-the-go access
- **Real-time Updates**: Connect to live data sources for current insights
- **What-if Analysis**: Scenario planning for pricing and discount strategies

## Contributing

If you'd like to enhance this dashboard:

1. Create a copy of the `.pbix` file
2. Make your modifications
3. Document changes in the commit/file name
4. Share your improvements with the team

## License

[Specify your license here]

## Contact

For questions or support regarding this dashboard, please contact [Your Contact Information]

---

**Last Updated**: March 2026
