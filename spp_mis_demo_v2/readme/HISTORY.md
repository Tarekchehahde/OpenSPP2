### 19.0.2.0.2

- Update demo GIS reports to the new disaggregation model: replace the removed
  `disaggregate_by_gender`/`disaggregate_by_age` boolean flags with
  `dimension_ids` referencing the `gender` and `age_group` demographic
  dimensions, and set `member_expansion` on group-filtered reports
- Remap the Philippine story areas in `STORY_AREA_MAP` to the curated PSGC
  p-code area external IDs; stories referencing barangays or a city absent from
  the curated dataset are assigned distinct municipalities to keep areas spread
  across the demo map
- Add an explicit dependency on `spp_metric_service` for the demographic
  dimension records referenced by the demo GIS reports

### 19.0.2.0.0

- Initial migration to OpenSPP2
