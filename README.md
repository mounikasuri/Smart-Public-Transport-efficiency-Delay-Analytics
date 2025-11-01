# Smart Public Transport Efficiency & Delay Analytics

Dataset: https://www.kaggle.com/datasets/balasrivatsa/apsrtc-public-transportation-data

## Overview
This project uses APSRTC bus data to create an easy-to-use Power BI dashboard that helps decision-makers improve operations and service. The dashboard highlights trends in ridership, revenue, fuel use, occupancy, and route performance so stakeholders can make clearer, data-driven choices.

## Data preparation
- Source file: `APSRTC_Cleaned.csv`.
- Steps taken:
  - Converted fields to consistent data types (dates, numbers, text).
  - Filled or removed missing values where needed.
  - Removed columns that were not useful for analysis.
  - Organized fields to support clear visual reporting (for example, hierarchies for date and location).

These steps ensure the data is reliable and ready for reporting.

## Visualizations
The Power BI dashboard includes:
- Line charts to show monthly revenue and fuel consumption trends.
- Bar charts to compare occupancy rates by bus type and passenger counts by route.
- Clustered bar charts to compare revenue and occupancy across depots.
- Slicers for month, day of the week, and bus type to let users filter and explore the data interactively.

## Key insights
- Monthly trends reveal when revenue and fuel use rise or fall.
- Occupancy rates vary by bus type, which helps with vehicle assignment and scheduling.
- Certain routes consistently carry more passengers and generate more revenue.
- Depot-level comparisons show where performance and resource use differ, guiding targeted improvements.

## Conclusion
The dashboard turns raw transport data into clear, actionable information. It helps transit managers:
- Identify strong and weak-performing routes,
- Optimize resource allocation based on occupancy and fuel usage,
- Monitor depot performance and revenue patterns,
- Quickly filter by time or vehicle type to investigate issues.

Overall, this project demonstrates how simple, interactive reporting can support better operational and strategic decisions for public transport.

## How to use
1. Open the Power BI report.
2. Use slicers (month, day of week, bus type) to focus on specific views.
3. Explore charts to find trends and outliers.
4. Use insights to plan route adjustments, vehicle allocations, and fuel/resource management.
