# Spotify Operations Dashboard (Power BI)

A one-page Power BI dashboard giving Spotify's management a quarterly view of revenue, subscribers, profitability and content performance.

**MSc Data Analytics, De Montfort University (2025)** · Business Intelligence module · Group project

![Spotify Operations Dashboard](spotify_dashboard.jpg)

## My role
This was a five-person group assignment on Spotify's business intelligence: decision types, BI architecture, value proposition, BI strategy and dashboard design. **I designed and built this Power BI dashboard**, including the data tables, DAX measures and layout. I also wrote the report section on day-to-day operational decisions.

## What it shows (Q4 2024 overview)
| Visual | Purpose |
|---|---|
| **KPI cards:** Total revenue, Premium subscribers, Average revenue per user (ARPU), Churn rate | Headline numbers, each with quarter-on-quarter change and a direction arrow |
| **Revenue trend 2024** (line) | Quarterly revenue across the year, highlighting the Q4 jump |
| **Gross margin %** (gauge) | Margin against a 32% target |
| **Regional revenue** (column) | Revenue by North America, Europe, Latin America and MENA |
| **Top 5 artists by listeners** (bar) | Content performance by monthly listeners |
| **Subscriber mix** (donut) | Premium vs ad-supported users |

## How it's built
- **Data tables:** `Revenue_Data` (quarterly revenue), `Regional_Data`, `Top_Artists`, `Subscriber_Mix`
- **DAX measures:** Q4 and Q3 revenue, Premium subscribers, ARPU, churn and churn change, used to calculate the quarter-on-quarter comparisons, plus Q4 gross margin for the gauge
- **Power KPI custom visual** for the headline cards
- Dark theme with Spotify green for positive movement, so performance can be read at a glance

## Design approach
Based on established dashboard design principles (Moriarty, *10 Principles for Building Effective Dashboards*; Geckoboard): the most important KPIs sit in the top row, trends and comparisons follow below, every chart answers one question, and colour is used to signal good or bad movement rather than for decoration.

## Data note
Figures are based on Spotify's public 2024 reporting, with some values approximated for the coursework. They should not be treated as official financial data.

## Files
| File | Description |
|---|---|
| `Spotify_final.pbix` | Power BI dashboard (open in Power BI Desktop) |
| `spotify_dashboard.jpg` | Dashboard screenshot |

## Author
**Affan Ahmad Khan** · [LinkedIn](https://www.linkedin.com/in/affanahmad66/) · [Other projects](https://github.com/affanahmad66)
