# Data methodology and interpretation

## What this repository contains

This repository contains reading guides and a metadata catalog for a growing collection of Nexscope ecommerce reports. Its initial collection contains four editions published on November 4, 2026. It does not contain a live data feed, raw API responses, or a bundled product dataset. Each brief links to its published source.

## Compare like with like

| Report family | Ranking measure | Time scope | Important distinction |
| --- | --- | --- | --- |
| 1688 best-selling products | Reported orders | October 2026 edition | Orders are not units; later product-detail checks are separate. |
| TikTok Shop best-selling products | Reported units sold | October 2026 saved monthly query | GMV is context, not net revenue or profit. |
| TikTok Shop trending products | Source trend signal | October 2026 edition | The signal is not a verified growth percentage. |
| TikTok Shop top selling creators | Reported GMV | Rolling 30-day snapshot dated November 4, 2026 | Do not treat it as an October calendar-month report. |

## Scope and limits

- Counts such as 41 of 100 describe the saved sample, not the entire marketplace.
- Wholesale and listed prices can differ from actual transaction prices. Variants, minimum orders, fees, shipping, taxes, and later changes can affect comparisons.
- Creator labels describe reported performance. They do not verify availability, audience quality, or commercial suitability.
- Do not compare ranks across editions as growth unless the underlying populations and methods support that calculation.
- Read the source report for field definitions and any edition-specific caveats before reusing a finding.

## Edition handling

Each catalog entry identifies a dated edition and its publication date. The source pages were checked on November 9, 2026. This date records the editorial check; it does not mean the underlying data was refreshed that day.

Corrections should identify the affected edition and evidence. New reporting periods should receive separate entries so historical context remains visible. There is no guaranteed release schedule.

## Citation

Use: Nexscope, report title, reporting period, publication date, full-report URL, and access date. Follow applicable source terms for datasets and third-party assets; this repository does not grant additional rights to them.

## Catalog structure

`platforms` records the platform ID, display name, and availability. Only available collections have an `index_path`. A Coming soon platform has no fabricated report URL or publication date.

`reports` contains published editions only. Each entry separates `platform_id`, `region`, `report_type`, `period_type`, `edition`, and `language`. A null region means that no separate country scope is assigned in the catalog; it does not mean worldwide coverage. The human-readable `reporting_period` preserves the source wording.

Monthly editions use `YYYY-MM`; dated snapshots use `YYYY-MM-DD`. Annual editions, when supported by a published source, use `YYYY` and `period_type: annual`. The publication date remains separate from the reporting period.

## From API data to a report

Nexscope reports use saved results from the source APIs linked in the README and individual reports. The report identifies the ranking measure and reporting period; analysis summarizes the returned sample. Later product-detail lookups remain distinct from the dated ranking. Subsequent API responses are new research, not automatic revisions to the published edition.
