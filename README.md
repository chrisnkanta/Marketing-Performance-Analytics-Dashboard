# Marketing Performance Analytics Dashboard | Power BI

## Dashboard Preview

![Marketing Performance Analytics Dashboard]([images/marketing-dashboard.png](https://github.com/chrisnkanta/Marketing-Performance-Analytics-Dashboard/blob/main/Screenshot%202026-10-26%20131018.png))

## Project Overview

This project uses Microsoft Power BI to analyze a simulated marketing campaign dataset covering four regions, four products, and four marketing channels from January 2023 to November 2024.

The interactive dashboard evaluates marketing engagement, advertising expenditure, revenue generation, conversion activity, and return on investment (ROI). It transforms campaign data into visual insights designed to support marketing performance monitoring and budget optimization.

**Project type:** Business Intelligence & Marketing Analytics  
**Tool:** Microsoft Power BI  
**Dataset:** Simulated marketing campaign data  
**Analysis period:** January 2023 – November 2024

## Business Objectives

- Evaluate marketing campaign effectiveness using CTR, CPC, and ROI.
- Compare revenue and advertising expenditure across marketing channels.
- Identify leading products by revenue contribution.
- Assess regional marketing performance.
- Explore quarterly and year-over-year trends.
- Develop data-driven recommendations for campaign optimization.

## Key Performance Indicators

| KPI | Dashboard Value |
|---|---:|
| Total Revenue | 1.04M |
| Total Marketing Spend | 0.26M |
| Total Clicks | 56K |
| Total Impressions | 570K |
| Total Conversions | 2,531 |
| Average CPC | 6.57 |
| Average CTR | 13.86% |
| Average ROI | 4.48 |

*Note: These figures are the values displayed in the dashboard. Currency is USD according to the dataset specification. Average KPI values may differ from ratios calculated using overall totals.*

## Dataset Overview

The dataset contains weekly marketing observations with the following dimensions:

- **Date:** Marketing activity date.
- **Region:** North, South, East, and West.
- **Product:** Products A, B, C, and D.
- **Marketing Channel:** Email, Social Media, Search Engine, and Direct Mail.
- **Quarter:** Q1, Q2, Q3, and Q4.

Numerical fields include Spend, Impressions, Clicks, Conversions, and Revenue.

## KPI Formulas

The derived metrics can be calculated using the following definitions:

- **Click-Through Rate (CTR):** Clicks / Impressions × 100
- **Cost Per Click (CPC):** Spend / Clicks
- **Return on Investment (ROI):** (Revenue − Spend) / Spend × 100

These definitions should be confirmed against the actual calculated columns and measures in the Power BI file. ROI expressed as a percentage is different from a revenue-to-spend ratio.

## Key Findings from the Dashboard

### 1. Marketing Channel Performance

Email and Social Media each generate approximately 0.30M in revenue. Search Engine contributes approximately 0.27M, while Direct Mail generates approximately 0.18M.

Email records the highest conversion volume, with 693 conversions, followed by Social Media at 638, Search Engine at 606, and Direct Mail at 594.

### 2. Product Revenue Analysis

Product C contributes the largest share of product revenue, generating 345.18K (33.11%). Product B contributes 263.44K (25.27%), Product A contributes 219.97K (21.10%), and Product D contributes 213.89K (20.52%).

### 3. Regional Performance

East and West each generate approximately 0.31M in revenue, followed by North at 0.27M and South at 0.16M. Further analysis of regional spending and ROI could help determine whether these differences reflect marketing efficiency or variations in demand.

### 4. Quarterly and Annual Trends

The dashboard provides quarterly revenue comparisons across regions and a year-over-year regional comparison. The displayed annual trend suggests lower revenue in 2024 than in 2023 for the represented regions.

These patterns can be investigated further to understand potential seasonality and differences in campaign performance.

### 5. Conversion Analysis

Conversions are distributed relatively evenly across the four channels. This highlights the importance of comparing conversion efficiency and acquisition costs rather than relying solely on conversion volume when evaluating channel effectiveness.

## Power BI Features Demonstrated

- Interactive date-range filtering.
- Region and marketing-channel slicers.
- KPI cards for performance monitoring.
- Revenue and spend comparisons.
- Waterfall analysis of revenue changes.
- Product revenue distribution.
- Regional and quarterly trend analysis.
- Conversion analysis by channel, region, and product.
- Matrix-based comparisons across business dimensions.

## Business Recommendations

1. Evaluate channel-level ROI and acquisition costs before reallocating advertising budgets.
2. Investigate the drivers of Product C's revenue contribution.
3. Review regional performance to identify opportunities for improving marketing efficiency.
4. Analyze quarterly and annual trends to identify areas requiring further investigation.
5. Validate KPI definitions and ensure consistent aggregation across report visuals.

## Tools and Skills

- Microsoft Power BI
- Data visualization and dashboard design
- Marketing KPI analysis
- Business intelligence reporting
- Data interpretation and storytelling
- DAX and Power Query, where implemented

## Limitations

The dataset is randomly generated and is intended for analytical practice and demonstration. Its patterns should not be interpreted as evidence of actual market behavior or used to make real-world budget decisions without validation against business data.

## Conclusion

This project demonstrates how Power BI can transform structured marketing data into an interactive analytical dashboard. It showcases KPI reporting, channel and product comparisons, regional analysis, and trend visualization while emphasizing the importance of accurate metric definitions and evidence-based business recommendations.
