## Inventory & Stock Performance Dashboard

## Project Overview

This project presents an interactive Power BI Inventory & Stock Performance Dashboard developed to analyze inventory records, sales quantities, stock values, reorder-level conditions, stockouts, supplier lead times and warehouse-level performance.
The dashboard helps identify potential inventory risks, explore stock distribution and support data-driven inventory planning and supply chain decisions.

## Business Objectives

- Monitor inventory quantities and sales activity.
- Identify records where stock is at or below the reorder level.
- Identify records with zero stock.
- Analyze inventory distribution across products, categories, and warehouses.
- Examine monthly stock and sales patterns.
- Evaluate lead times and unit costs to support replenishment planning.

##  Key KPIs

- Total Stock Quantity - 456K
- Total Sales Quantity - 139K
- Inventory Value - 58M
- Reorder- Level Records  - 58
- Average Lead Time(Days) - 6.49
- Stockout Records - 54
- Average Unit Cost - 141.01
  
Values are displayed in rounded form where applicable and reflect the selected dashboard filters.  

##  Dashboard Analysis

The interactive dashboard provides the following analyses,

- Stock quantity by product
- Sales quantity by product
- Stock distribution by warehouse
- Stock quantity by product category
- Monthly stock quantity patterns
- Monthly sales quantity trends
- Sales quantity by category
- Reorder-level monitoring
- Stockout record monitoring
- Inventory value and average unit cost
- Average lead time analysis

##  Key Insights

1. Reorder-Level Monitoring
The dashboard identifies 58 inventory records where stock quantity is less than or equal to the reorder level. These records indicate potential replenishment requirements that should be investigated.

2. Stockout Monitoring
A total of 54 inventory records have zero stock quantity. These observations highlight possible stock availability issues that may require further review.

3. Inventory and Sales Activity
The dashboard summarizes approximately 456K in recorded stock quantity and 139K in recorded sales quantity across the selected period, enabling comparisons of inventory and sales patterns.

4. Warehouse and Category Analysis
Warehouse-level and category-level visualizations help identify differences in recorded inventory distribution and sales activity, supporting more focused inventory planning.

5. Lead Time Analysis
The average recorded lead time is 6.49 days. Monitoring lead times can support replenishment planning and help assess potential supply chain delays.

## Business Recommendations

- Prioritize replenishment reviews- Investigate records where stock is at or below the reorder level.
- Review stockout situations- Examine zero-stock records to identify recurring availability issues and possible corrective actions.
- Improve inventory planning- Compare sales patterns with recorded stock quantities to inform purchasing and replenishment decisions.
- Evaluate warehouse distribution- Review stock distribution across warehouses to identify potential imbalances.
- Monitor supplier lead times- Consider lead-time patterns when planning reorder timing and inventory availability.

## Methodology

- Data Preparation- Used Power Query to prepare inventory data for analysis.
- Data Analysis- Examined stock quantities, sales quantities, unit costs, reorder levels, lead times, product categories and warehouses.
- DAX Measures- Created measures for inventory KPIs, including total stock quantity, total sales quantity, inventory value, reorder-level records, stockout          records, average lead time and average unit cost.
- Dashboard Development- Built interactive Power BI visualizations and date filtering to support inventory performance analysis.
- Business Interpretation- Identified inventory monitoring priorities and developed recommendations based on dashboard findings.

## Important Data Interpretation Notes

- Reorder-Level Records counts inventory rows where Stock Qty <= Reorder Level. It does not represent the number of distinct products requiring replenishment.
- Stockout Records counts inventory rows where Stock Qty = 0. It does not represent the number of distinct products that are out of stock.
- A zero-stock record may also meet the reorder-level condition, so these two KPI groups can overlap.
- Total Stock Qty is calculated by summing stock quantities across the selected records.
- Inventory Value is calculated by summing Stock Qty × Unit Cost across the selected records.
- Because the dataset contains dated inventory records and the stock quantity's snapshot or transaction meaning is not confirmed, aggregated stock quantity and      inventory value should not automatically be interpreted as current physical inventory balances.
- Average Unit Cost represents the arithmetic mean of recorded unit costs, rather than a stock-quantity-weighted average.
  
## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Visualization


## 📷 Dashboard Preview

![Inventory & Stock Performance Dashboard](Screenshot%20(1833).png)

## Skills Demonstrated

- Business Analysis
- Inventory and Stock Analysis
- Supply Chain Analytics
- KPI Development and Interpretation
- DAX Measures
- Data Preparation and Transformation
- Warehouse and Product Performance Analysis
- Data Visualization
- Business Intelligence Reporting
- Business Recommendations

  
## Project Files
- `Inventory & Stock Performance Dashboard.pbix` - Power BI dashboard file
- `Screenshot (1833).png` - Dashboard preview
- `README.md` - Project documentation

## Author
**Samudi Tharusha**


