# Plant Co. Quantity Performance Dashboard (2023)

## **Overview**  
This project analyzes Plant Co.'s quantity performance metrics using Power BI. The interactive dashboard highlights YTD vs. PYTD trends, GP%, and account profitability. It enables stakeholders to monitor performance across regions, months, and product types.

## **Key Features**  
- **KPIs**:
  - **S_YTD**: Year-to-Date quantity.
  - **S_PYTD**: Prior Year-to-Date quantity.
  - **YTD vs. PYTD**: Variance between YTD and PYTD quantities.
  - **GP%**: Gross Profit Percentage.
- **Visualizations**:
  - Tree map for underperforming regions.
  - Waterfall chart for monthly performance changes.
  - Scatter plot for account profitability segmentation.
  - Combined bar and line chart for monthly trends by product type.
- **Dynamic Filters**:
  - Filter data by year, product type, and country.

## **Technical Details**  
- **Tools Used**: Power BI, DAX, Power Query.
- **Data Transformation**:
  - Extracted and transformed raw data using Power Query.
  - Created custom measures in DAX for KPIs like YTD vs. PYTD and GP%.
- **Data Source**: Simulated business dataset (CSV).

## **Screenshots**  
### Bottom 10 YTD vs. PYTD | Country  
![Tree Map]([Tree Map.png](https://github.com/VandanaJada/Plant-Co.-Quantity-Performance-Dashboard/blob/main/Scatter%20Plot.png))

### Monthly YTD vs. PYTD Performance  
![Waterfall Chart](images/monthly_performance.png)

### Account Profitability Segmentation  
![Scatter Plot]([images/account_profitability.png](https://github.com/VandanaJada/Plant-Co.-Quantity-Performance-Dashboard/blob/main/Scatter%20Plot.png))

## **How to Use**  
1. Download the `.pbix` file from this repository.
2. Open the file in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Explore the interactive dashboards by using the slicers and filters.

## **Future Enhancements**  
- Adding additional metrics like customer churn rate and profitability trends.
- Automating data refresh through Power BI Service.

## **License**  
This project is licensed under the MIT License. See the `LICENSE` file for details.
