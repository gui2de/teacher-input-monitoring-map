# Teacher Input Monitoring Map

Static Leaflet choropleths for Teacher Input Monitoring school attendance
submission rates.

District map:

```text
https://gui2de.github.io/teacher-input-monitoring-map/tsa_completeness_district_map.html
```

Sector map:

```text
https://gui2de.github.io/teacher-input-monitoring-map/tsa_completeness_sector_map.html
```

Keep each HTML file and its matching `_files/` folder together. The HTML
files reference assets in those sibling folders.

## Basemap

The maps have no background tiles. CARTO basemaps (previously
`CartoDB.Positron`) now require an API key and render "API KEY REQUIRED"
watermarks without one, so the tile layer was removed and polygons are drawn on
a plain white background. The script that generates these HTML files is not
kept in this repo; if they are regenerated, omit `addProviderTiles()`.
