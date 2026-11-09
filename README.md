# Ecommerce Market Reports

**Find products to investigate, compare sourcing options, and build creator shortlists with dated ecommerce data.**

A growing library of ecommerce market research from Nexscope, organized by platform, research topic, region, and reporting period. Explore product rankings, sourcing insights, pricing patterns, and creator performance.

Reports for **1688 and TikTok Shop** are available now. More platform collections will be added as reports are published. Each brief connects key findings with the complete report and its supporting data.

[Browse all reports](https://www.nexscope.ai/reports?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_browse) · [How to read the data](METHODOLOGY.md) · [Report catalog](catalog.json)

## Browse by platform

| Platform | Reports |
| --- | --- |
| 1688 | [View 1688 reports](https://www.nexscope.ai/reports/1688?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_platform_1688) |
| TikTok Shop | [View TikTok Shop reports](https://www.nexscope.ai/reports/tiktok?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_platform_tiktok) |
| Amazon | Coming soon |
| Shopee | Coming soon |
| Ozon | Coming soon |
| Temu | Coming soon |
| Walmart | Coming soon |
| Shopify | Coming soon |
| Etsy | Coming soon |
| eBay | Coming soon |
| WooCommerce | Coming soon |
| Mercado Libre | Coming soon |

## What these reports help you do

| Your goal | What you can take away |
| --- | --- |
| Find products worth researching | Use rankings and category patterns to build a focused product shortlist. |
| Compare sourcing options | Review wholesale prices, minimum orders, and supplier context before checking current quotes. |
| Understand sales and momentum | Compare best-selling products with trend signals to decide what deserves a closer look. |
| Plan creator research | Compare reported sales performance and video/live mix, then assess audience and product fit. |
| Build your own analysis | Download report CSVs, explore the source APIs, and investigate questions specific to your business. |

Start with a report to narrow your research, then validate your shortlist with current data and your own costs.

## Latest reports

| Report | Market / scope | Period |
| --- | --- | --- |
| [1688 Best-Selling Products](https://www.nexscope.ai/reports/1688/best-selling-products/2026-10?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_1688-best-selling-2026-10) | 1688 sourcing | October 2026 |
| [TikTok Shop Best-Selling Products](https://www.nexscope.ai/reports/tiktok/best-selling-products/us/2026-10?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_tiktok-best-selling-us-2026-10) | United States | October 2026 |
| [TikTok Shop Trending Products](https://www.nexscope.ai/reports/tiktok/trending-products/us/2026-10?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_tiktok-trending-us-2026-10) | United States | October 2026 |
| [TikTok Shop Top Selling Creators](https://www.nexscope.ai/reports/tiktok/top-selling-creators/us/2026-11-04?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_tiktok-creators-us-2026-11-04) | United States | 30-day snapshot dated November 4, 2026 |

These four editions were published on November 4, 2026. Product reports cover October; the creator report uses the source's rolling 30-day window.

[Browse the full report archive](reports/README.md). New editions will appear here, while platform collections retain earlier reports.

## A few findings to explore

- **1688:** Personal Care & Household represents 41 of 100 listings; 35 listings fall in the CNY 2–4.99 wholesale price band. [Read the brief](reports/1688/2026-10-best-selling-products.md).
- **TikTok Shop sales:** Beauty & Personal Care represents 46 of 100 products. [Read the brief](reports/tiktok/2026-10-us-best-selling-products.md).
- **TikTok Shop trends:** Home Supplies represents 16 of 100 products. [Read the brief](reports/tiktok/2026-10-us-trending-products.md).
- **TikTok Shop creators:** 75 of 100 accounts are video-led by their reported video/live GMV mix. [Read the brief](reports/tiktok/2026-11-04-us-top-selling-creators.md).

These are findings within individual saved rankings, not estimates of marketplace-wide share.

## Use a report in your own research

1. Choose the marketplace, question, and reporting period.
2. Read the brief for findings and interpretation limits.
3. Open the full report and use **Download CSV** to examine the underlying ranking.
4. Filter for your category and compare prices or sales measures within the same period.
5. Verify current product details, economics, and availability before making a decision.

No installation or API key is needed to read these Markdown briefs. CSV files are linked from the published reports and are not bundled in this repository.

## How the reports are made

These reports are built from saved results returned by **Nexscope's ecommerce data APIs**. Each published edition identifies its source, ranking rule, and reporting window.

**Nexscope Data APIs → saved data snapshot → rankings and analysis → dated report and CSV**

1. **Retrieve the relevant data.** Query the source API for the report's marketplace and research question, using the filters supported by that endpoint.
2. **Preserve the reporting context.** Record the snapshot, market, time window, and metric definitions so readers know what the numbers represent.
3. **Analyze the results.** Organize the returned records into rankings and relevant category, price, or sales-channel breakdowns.
4. **Publish the findings.** Present the ranking, charts, methodology, and downloadable CSV in a dated report.

### APIs behind the current reports

| Report | Data source |
| --- | --- |
| 1688 best-selling products | [1688 Product Billboard API](https://www.nexscope.ai/api-docs/1688-product-billboard?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_source_1688) |
| TikTok Shop best-selling and trending products | [TikTok Top Selling Products API](https://www.nexscope.ai/api-docs/tiktok-top-selling-products?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_source_tiktok_products) |
| TikTok Shop top selling creators | [TikTok Creator Analytics API](https://www.nexscope.ai/api-docs/tiktok-creator-analytics?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_source_tiktok_creators) |

Later product-detail lookups are identified separately from the original ranking snapshot. A new API query does not automatically update a published edition.

## Go beyond the report with Nexscope APIs

The report gives you a starting point. Connect Nexscope's data APIs to your own research workflow to explore more products, check current details, or answer a question the published edition does not cover.

1. [Create a Nexscope API key](https://www.nexscope.ai/seller/api-access?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_get_api_key).
2. [Choose an API](https://www.nexscope.ai/api-docs?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_api_docs) and review its supported parameters, response fields, and credit cost.
3. Bring the results into your scripts, dashboards, or research tools to compare candidates and build your own analysis.

Available filters, historical coverage, and data freshness vary by endpoint. API queries require authentication and are subject to the relevant usage terms.

**[Explore Nexscope Data APIs](https://www.nexscope.ai/apis?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_apis)**

For a machine-readable list of published editions, see [`catalog.json`](catalog.json). For local reading guides, browse the [brief archive](reports/README.md).

## Data and interpretation

- The linked report is the source of truth for each edition's data and methodology.
- Orders, units, GMV, and source trend signals are different measures.
- Historical rankings do not establish future demand, profit, or creator partnership suitability.
- Dated editions should be compared only after checking market, time window, ranking method, and field definitions.

See [METHODOLOGY.md](METHODOLOGY.md) for details.

## Corrections and suggestions

Found a broken link, unclear metric, or a discrepancy with the published report? See [CONTRIBUTING.md](CONTRIBUTING.md). Include the report path and evidence so the issue can be checked.

## About Nexscope

Nexscope helps ecommerce sellers, analysts, and developers turn marketplace data into research and decisions.

[Explore the reports](https://www.nexscope.ai/reports?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_footer) · [Research with ecommerce APIs](https://www.nexscope.ai/apis?co-from=github-report&utm_source=github&utm_medium=referral&utm_campaign=ecommerce_market_reports&utm_content=readme_footer_apis)

## Use and attribution

When citing a finding, identify Nexscope, the report title, reporting period, and full-report URL. Public availability does not by itself grant a license to redistribute source datasets or third-party assets. No open-source or open-data license is granted by this draft.
