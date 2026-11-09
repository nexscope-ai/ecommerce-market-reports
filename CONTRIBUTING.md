# Contributing

Contributions that make the report library more accurate and useful are welcome.

## Report a problem

Include:

- The brief path or report URL.
- The specific link, metric, or wording in question.
- The published evidence and date checked.
- A concise proposed correction, if available.

Do not include credentials, private account data, customer records, or unpublished datasets.

## Suggest a report

Describe the marketplace, geography, research question, reporting period, and evidence needed. A suggestion is not a commitment to publish a report.

## Propose an edit

Keep public documentation in English, preserve dated editions, and distinguish reported facts from interpretations. Every numerical claim must be traceable to a published source. Do not add promotional links unrelated to the research or upload datasets without permission to redistribute them.

## Add a published edition

1. Verify the full report, publication date, scope, ranking basis, and reuse limits.
2. Add an English brief under `reports/<platform-id>/` with the edition, region where relevant, and report type in its filename. Follow the existing files as examples.
3. Add its metadata to `catalog.json`; keep platform, region, report type, and period separate.
4. Update the platform collection and full archive, then select recent reports for the main README.
5. For a platform's first report, create its collection and change its availability to `available` in the catalog and README. Do not create empty report pages for Coming soon platforms.
6. Preserve existing editions and verify all relative links. Nexscope links in this repository must use `co-from=github-report`; use placement-specific `utm_content` values.

This is a manual editorial workflow. The catalog does not automatically sync with the website.
