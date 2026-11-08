# Tableau source and data setup

`Lan_Part2_Survival_by_Category.twb` is Lan's original Part 2 worksheet source, with local absolute data directories replaced by `data`. Its chart calculations are preserved. It is a `.twb`, not a packaged `.twbx`, so it does not embed data.

To open the original worksheet interactively, place the team's prepared files in a `data/` folder beside the workbook:

- `businesses_summary.csv`
- `businesses_by_year.csv`
- `local-area-boundary.geojson`

Open the workbook in Tableau Desktop and reconnect the three sources if prompted. The prepared CSVs and original cleaning pipeline are not included in this portfolio release. Downloading current raw City data alone will not recreate the team's transformed tables or the historical snapshot.

The public PDF and chart previews can be viewed without Tableau. The supplied workbook contains the worksheet “5-Year Survival Rate by Category”; it is not the complete five-chart team dashboard. Native Tableau opening/reconnection has not been verified for this public copy.

## Source datasets

- [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/): historical Business Licences datasets, 1997-2026.
- [Local area boundary](https://opendata.vancouver.ca/explore/dataset/local-area-boundary/): Vancouver's neighbourhood boundaries.

The report documents deduplication, business-name/address matching, industry grouping, cohort definitions and exclusions. Raw licensing records and the team's prepared row-level data are not redistributed here.
