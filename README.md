# Manufacturing-Downtime-Analysis


## Overview
This project provides a comprehensive analysis of manufacturing downtime, enabling stakeholders to identify inefficiencies, reduce bottlenecks, and improve overall productivity. The analysis leverages Power BI for interactive visualizations and data modeling, with features like Pareto analysis and conditional formatting to highlight critical insights.

## Features
- 📊 **Interactive Dashboards**: Visualize downtime trends, causes, and patterns across production lines.
- 📈 **Pareto Analysis**: Highlight the 80/20 rule to identify the most significant downtime causes contributing to overall inefficiencies.
- 🎨 **Conditional Formatting**: Automatically highlight critical metrics and thresholds for improved decision-making.

## Dataset Description
The analysis is based on manufacturing production and downtime data, including:
- **Line productivity**: Production metrics for each manufacturing line.
- **Products**: Details about products, such as batch times and specifications.
- **Downtime logs**: Records of downtime events, including causes, durations, and timestamps.

## Key Metrics
- Total downtime duration.
- Average downtime per shift/line.
- Most frequent downtime causes.
- Productivity loss due to downtime.
- **Pareto Insight**: The most significant causes contributing to 80% of downtime.
- Conditional visual cues to indicate critical metrics.

## Technical Details
- **Tool**: Microsoft Power BI
- **New Features**:
  - **Pareto Analysis**: Visualize cumulative impact for identifying top contributors.
  - **Conditional Formatting**: Highlight top contributors in the Pareto Analysis.
- **DAX Functions Used**: 
  - `SUMX`
  - `RELATED`
  - Custom calculations for Pareto ranking and cumulative percentage.
- **Relationships**: Star schema with fact and dimension tables.

## File Contents
- `Manufacturing Downtime Analysis.pbix`: The main Power BI report file.
- `README.md`: Documentation and project details.




- <img width="611" alt="image" src="https://github.com/user-attachments/assets/cf4cfa39-5076-4f11-b2b5-33f3c976e28f" />

