# Job-Worker Spatial Dynamics In Beijing: Insights From Smart Card Data

## Contribution

This paper develops a smart-card method for estimating and tracking station-area job–worker balance among regular transit commuters. Applied longitudinally in Beijing, it identifies temporary local balance, a broader tendency toward steeper job–worker imbalances, and the polycentric pattern of emerging employment centers.

## Bibliographic Information

- Row ID: `paper-2019-10`
- Year: 2019
- Authors: Jie Huang, David Levinson, Jiaoe Wang, Haitao Jin
- Venue: Cities, 86, 89-93
- DOI: https://doi.org/10.1016/j.cities.2018.11.021

## Package Status

This package is ready for public upload review as a partial, non-sensitive support package. The paper uses Beijing subway smart-card records with card-level travel traces and SQL/rule-based commuter identification. Those raw data and processing scripts were not found locally and are not included here.

The only data-like local file found was `AWR.xlsx`, a five-row aggregate/formula-check workbook. It has been staged as non-sensitive derived support in both original XLSX and CSV forms. It does not contain card IDs, station-level traces, or raw smart-card records, and it is not sufficient to reproduce the paper.

## Included Files

- `paper/Job-worker-spatial-dynamics-in-Beijing_Insights-from-Smart-Card-Data.pdf`: final article reference copy.
- `data/derived_non_sensitive/job_worker_awr_formula_check.xlsx`: small aggregate/formula workbook copied from `AWR.xlsx`.
- `data/derived_non_sensitive/job_worker_awr_formula_check.csv`: CSV conversion of the workbook.
- `metadata/SOURCE_FILE_DECISIONS.csv`: file-by-file decision log for the local source folder.
- `metadata/SEARCH_LOG.csv`: local search and workbook inspection summary.
- `metadata/PUBLIC_REFERENCE_LINKS.csv`: public article/preprint pointers.
- `metadata/PACKAGE_FILE_MANIFEST.csv`: current package file list with checksums.

## Excluded Material

Draft manuscripts, preprints, conference versions, reviewer responses, and editorial materials are excluded. Raw smart-card data and SQL/analysis scripts were not present in the inspected folder.

## Remaining Request

No further local search is queued for this package. The staged AWR workbook/CSV is the available local support artifact; raw smart-card data and SQL scripts remain absent and are not part of this package.

Last updated: 2026-05-17 23:46:57 Australia/Sydney.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-21 20:19:00 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
