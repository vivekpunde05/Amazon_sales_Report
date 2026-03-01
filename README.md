# Amazon Sales Dashboard

A comprehensive Power BI dashboard for analyzing Amazon e-commerce sales data, providing insights into sales performance, trends, and key business metrics.

## Project Overview

This project contains an interactive Power BI dashboard that visualizes Amazon sales data to help stakeholders make data-driven decisions. The dashboard provides a clear view of sales performance across various dimensions including time periods, product categories, regions, and customer segments.

## Files in This Project

- `amazon sales dashboard.pbix` - Main Power BI dashboard file
- `ECOMM DATA.xlsx` - Source data file containing Amazon sales records
- `Amazon Sales Report.png` - Dashboard preview/screenshot

## Features

The dashboard likely includes:

- **Sales Performance Metrics**: Total revenue, order volume, and growth trends
- **Time-based Analysis**: Sales trends over time (daily, monthly, quarterly, yearly)
- **Product Analysis**: Top-selling products and category performance
- **Geographic Insights**: Sales distribution across regions/locations
- **Customer Analytics**: Customer behavior and purchasing patterns
- **Interactive Filters**: Dynamic filtering by date, product, region, and other dimensions

## Requirements

To view and interact with this dashboard, you need:

- **Microsoft Power BI Desktop** (latest version recommended)
  - Download from: https://powerbi.microsoft.com/desktop/
- **Microsoft Excel** (to view/edit the source data file)

## Getting Started

### Opening the Dashboard

1. Install Power BI Desktop if you haven't already
2. Double-click `amazon sales dashboard.pbix` or open it through Power BI Desktop
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

The dashboard uses data from `ECOMM DATA.xlsx`, which contains Amazon sales transaction records. The dataset typically includes:

- Order details (Order ID, Date, Status)
- Product information (Name, Category, SKU)
- Customer data (Customer ID, Location)
- Financial metrics (Price, Quantity, Revenue)
- Shipping and fulfillment information

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

- Add predictive analytics for sales forecasting
- Integrate additional data sources (inventory, marketing spend)
- Create mobile-optimized views
- Implement row-level security for multi-user scenarios
- Add automated email reports using Power BI Service

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
