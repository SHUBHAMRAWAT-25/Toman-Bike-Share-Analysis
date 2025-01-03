# Toman Bike Shares Analysis

This project showcases an analysis of Toman Bike sales data using SQL and Power BI. By combining and conditioning data from multiple datasets, we generated actionable insights and recommendations to optimize pricing strategies and market positioning.

## Problem Statement

The Toman Bike Shares program seeks the development of a comprehensive dashboard to enhance decision-making by visualizing key performance metrics. The dashboard must include:
- Hourly revenue analysis
- Profit and revenue trends
- Seasonal revenue insights
- Rider demographics

The dashboard should:
- Follow the company's color scheme
- Be user-friendly

Access to the company's databases will be provided; if no database exists, one must be created. A preliminary version of the dashboard is needed as soon as possible. Additionally, recommendations on whether to raise prices next year should be included based on the data analysis. The objective is to create an effective dashboard that aids Toman Bike Share in strategic planning and operational improvements.

## Project Overview

The project involves:
- **Data Integration**: Joining and analyzing three datasets using SQL in Microsoft SQL Server Management Studio (SSMS).
- **Data Conditioning**: Applying calculations such as `SUM` and `IF-ELSE` to transform and prepare the data.
- **Visualization**: Creating dynamic and interactive Power BI dashboards to present insights, with condition formatting for enhanced clarity.
- **Data Transformation**: Using DAX functions in Power BI to manipulate and analyze data.
- **Database Connection**: Connecting the company's database directly to Power BI for real-time data analysis.
- **Recommendations**: Providing actionable strategies based on the analysis.

## Objectives

1. Analyze historical sales trends and pricing data.
2. Evaluate the impact of price changes on customer demand.
3. Recommend optimal pricing strategies to maximize revenue without significantly reducing customer base.

## Key Insights and Recommendations

### Conservative Price Increase
- Based on the data, a **conservative price increase** is advisable to avoid hitting a price ceiling where demand begins to drop.
- A recommended increase of **10-15%** can test market response without risking a significant loss in customers.

### Price Setting
- If the price in 2021 was $4.99:
  - A **10% increase** would set the new price to approximately **$5.49**.
  - A **15% increase** would set the new price to approximately **$5.74**.

### Recommended Strategy
1. Conduct a detailed **market analysis** to understand customer sensitivity to price changes.
2. Implement a **segmented pricing strategy** based on customer demographics and buying behavior.
3. Continuously **monitor and adjust prices** based on market feedback and sales trends.

## Technologies Used

1. **Microsoft SQL Server Management Studio (SSMS)**
   - Used for querying and joining the datasets.
   - Key techniques: `JOIN`, `SUM`, `CTEs`.

2. **Power BI**
   - Used for creating interactive dashboards and visualizing data.
   - Key features: dynamic charts, slicers, data modeling, condition formatting, and DAX functions.
   - Direct database connection for real-time data analysis.

## Project Files

- `Toman Bike Analysis.pbix`: Power BI file containing the interactive dashboard.
- `SQL Scripts`: SQL queries used to prepare and condition the data (available in the repository).
- `README.md`: Documentation for the project.

## Getting Started

1. Clone the repository:
   ```bash https://github.com/SHUBHAMRAWAT-25/Toman-Bike-Share-Analysis
   git clone
   ```

2. Open the SQL scripts in Microsoft SQL Server Management Studio to explore the data preparation steps.

3. Open the `Toman Bike Analysis.pbix` file in Power BI Desktop to view the interactive dashboard.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

