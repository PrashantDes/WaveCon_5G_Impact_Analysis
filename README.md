# WaveCon 5G Impact Analysis

> A Power BI business analysis of whether WaveCon's 5G launch improved revenue, customer retention, market share, and prepaid-plan performance.

## Overview

WaveCon launched 5G in May 2022 across 15 cities. This project compares the four months before launch (January-April) with the four months after launch (June-September), excluding the launch month. It translates dashboard findings into a clear performance review and a set of actions for improving growth after the rollout.

The analysis covers 13 prepaid plans, five competing operators, and eight months of monthly data.

## Business questions

- Did 5G improve WaveCon's revenue?
- What changed in ARPU, active users, and unsubscribes?
- How did WaveCon's market share change relative to competitors?
- Which prepaid plans gained or lost traction after the launch?
- Which cities need retention, win-back, or network-experience action?

## Key findings

| Metric | Before 5G | After 5G | Change |
| --- | ---: | ---: | ---: |
| Total revenue | ₹1,597.7 Cr | ₹1,589.7 Cr | -0.5% |
| ARPU | ₹190 | ₹211 | +11.0% |
| Average monthly active users | 210.9 L | 193.4 L | -8.3% |
| Average monthly unsubscribed users | 14.1 L | 17.4 L | +23.5% |
| Market share | 20.2% | 18.9% | -1.35 pp |

- 5G increased value per customer, but the loss of active users offset that improvement and left revenue essentially flat.
- WaveCon lost market share in all 15 cities while the overall market grew 6.8%. Holding its pre-launch share would have added about ₹116 Cr in revenue.
- `p1` Smart Recharge grew 31.7%, while new 5G plans `p11` and `p12` generated ₹302.1 Cr after launch.
- Low-data and legacy plans underperformed. `p7`, a 25 GB 3G/4G combo plan, lost 73% of its revenue across every city.
- Delhi is the top win-back priority; Lucknow, Pune, and Jaipur require churn investigation. Mumbai provides the strongest retention benchmark.

## Recommendations

1. Target win-back and retention offers in Delhi, Mumbai, Bangalore, and Ahmedabad.
2. Investigate the churn spikes in Lucknow, Pune, and Jaipur, including network experience, device readiness, and pricing.
3. Put marketing behind `p1`, `p11`, and `p12`; migrate users from declining low-data plans to data-heavy 5G packs.
4. Retire `p7` and offer affected users an upgrade path to a 5G-ready bulk-data plan.
5. Compete for lost share with stronger 5G coverage and value propositions against PIO and Britel.

## Methodology

- **Comparison window:** January-April 2022 vs. June-September 2022. May is excluded as the launch month.
- **Matched months:** January vs. June, February vs. July, March vs. August, and April vs. September.
- **Measures:** revenue, ARPU, active users, unsubscribed users, market value, market share, and plan revenue.
- **Scope:** 15 cities, 13 prepaid plans, and WaveCon's main competitors.
- **Important note:** plan revenue covers tracked plans only, so it does not exactly equal total company revenue. ARPU uses the dashboard's city-month average calculation.

## Deliverables

| File | Description |
| --- | --- |
| [Power BI dashboard](Wavecon_dashboard_analysis1.pbix) | Interactive dashboard for exploring KPIs, city trends, market share, and plan performance. Requires Power BI Desktop. |
| [Analysis report](WaveCon_5G_Impact_Analysis.pdf) | Complete written performance review and recommendations. |
| [Presentation](WaveCon_5G_Impact_Analysis.pptx) | Stakeholder-ready summary of the analysis. |

## Tools used

- Power BI Desktop
- Power Query for data preparation
- DAX for calculated measures and KPI analysis
- Microsoft PowerPoint for communicating findings

## How to explore the project

1. Download or clone this repository.
2. Open `Wavecon_dashboard_analysis1.pbix` in Power BI Desktop.
3. Use the report pages and filters to examine performance by city, plan, period, and operator.
4. Read the PDF or presentation for the full narrative and recommended actions.

> The source dataset is not included in this repository. The `.pbix` file contains the analysis deliverable.

## License

This project is available under the [MIT License](LICENSE).
