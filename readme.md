# Meta Ads Campaign Performance Analysis

## Project Overview

An interactive **Meta Ads Performance Dashboard** built using Power BI and Excel to analyze Facebook and Instagram advertising campaigns. The project evaluates campaign performance across audience demographics, geography, time, platforms, and ad formats to identify optimization opportunities and support data-driven marketing decisions.

## Tools & Technologies

- **Power BI:** Interactive dashboards, DAX measures, data modeling, and visualization.
- **Microsoft Excel:** Data cleaning, validation, and data structuring.
- **Data Modeling:** Star schema with one fact table and three dimension tables.

## Data Model

The project follows a star schema to support efficient analysis across campaign, advertisement, and audience dimensions.

| Table | Type | Description |
|---|---|---|
| `ad_events` | Fact | User interactions, including impressions, clicks, comments, and purchases. |
| `ads` | Dimension | Ad formats, platforms, targeting, and campaign associations. |
| `campaigns` | Dimension | Campaign objectives, budgets, and durations. |
| `users` | Dimension | Audience demographics, locations, and interests. |

**Relationships:** `ad_events` connects to `ads` and `users`, while `ads` connects to `campaigns`. This enables cross-dimensional analysis of campaign and audience performance.

## Key Performance Indicators (KPIs)

The dashboard tracks key marketing funnel and financial metrics:

- **Impressions & Clicks:** Measure ad exposure and traffic generation.
- **Engagements:** Track interactions such as clicks, shares, and comments.
- **CTR (Click-Through Rate):** Percentage of impressions that generate clicks.
- **Engagement Rate:** Percentage of impressions resulting in engagements.
- **Conversion Rate:** Percentage of clicks that result in purchases.
- **Purchase Rate:** Percentage of impressions resulting in purchases.
- **ROAS (Return on Ad Spend):** Revenue generated relative to advertising spend.

## Dashboard Features

- **Marketing Funnel:** Tracks the journey from impressions to clicks, engagement, and purchases to identify conversion drop-offs.
- **Audience Analysis:** Uses demographic visuals to compare engagement by gender and age group.
- **Geographic Analysis:** Maps campaign performance by country to identify high-engagement and high-value markets.
- **Time & Seasonality:** Analyzes hourly engagement patterns and calendar-based activity to identify potential high-performing periods.
- **Ad Format Performance:** Compares video, story, image, and carousel ads across impressions, CTR, conversion rate, and engagement rate.
- **Platform & Campaign Analysis:** Supports performance comparisons across Facebook and Instagram campaigns.

## Key Insights

- **Overall Performance:** CTR of approximately **11.76%** and engagement rate of **13.56%**.
- **Conversion Funnel:** Purchase rate of approximately **0.61%**, highlighting an opportunity to improve conversion efficiency.
- **Audience:** Female users and the **18–30 age group** account for the strongest engagement.
- **Ad Formats:** Video and story ads show comparatively strong performance across engagement and conversion metrics.
- **Timing:** Engagement peaks during afternoon and evening hours, particularly between **15:00 and 20:00**.
- **Geography:** India and Brazil lead in engagement volume, while Germany and the UK represent high-value markets.

## Recommendations

1. Optimize landing pages and conversion journeys to reduce funnel drop-offs.
2. Improve retargeting to convert users who have already engaged with ads.
3. Personalize campaigns for high-engagement audience segments.
4. Evaluate allocating more budget to video and story ads based on performance.
5. Test scheduling strategies around high-engagement time windows.
6. Tailor campaign objectives to regional differences in engagement and value.

## Business Objectives

- Monitor advertising performance through key marketing KPIs.
- Identify effective audience segments and ad formats.
- Compare campaign performance across platforms and regions.
- Identify conversion bottlenecks and opportunities to improve advertising efficiency.
- Support data-driven campaign optimization and budget allocation.

## Visualizations

| Visualization | Purpose |
|---|---|
| Funnel Chart | Track progression through the marketing funnel. |
| Donut Chart | Compare engagement by gender. |
| Bar Chart | Analyze performance across age groups. |
| Map | Compare campaign performance geographically. |
| Calendar Heatmap | Identify daily activity patterns and potential campaign spikes. |
| Stacked Column Chart | Compare weekly performance by ad type. |
| Area Chart | Analyze hourly engagement trends. |
| Matrix | Compare ad formats and platform performance. |

## Conclusion

This project demonstrates how Power BI and Excel can be used to transform advertising interaction data into actionable marketing insights. By combining KPI tracking, audience segmentation, geographic analysis, and funnel monitoring, the dashboard supports better-informed decisions around ad creative, targeting, campaign timing, and advertising spend.