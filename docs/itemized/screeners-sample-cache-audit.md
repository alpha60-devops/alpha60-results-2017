---
layout: default
title: "screeners Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# screeners sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Screeners 2017-2018 |
| Collection key | `screeners` |
| imdb_id | UNAVAILABLE |
| wikipedia_url | UNAVAILABLE — no English Wikipedia page exists |
| Sample dates | 2017-12-22-to-2018-03-31 |
| Sample days | 100 |
| BTIH count | 147 |
| Unique BTIH count | 130 |
| Downloaders total | 15,285,853 |
| Uploaders total | 4,265,104 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-08T01:10:00Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/eoy-2017-2018.xz`
- Hour directories: 3575
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 2 (125 missing hours)
- Missing days: 4

### Sample archive discontinuities

- hourly gap: last `2018-01-12 19:00`, resumed `2018-01-17 01:34` — missing 101 hour(s)
- hourly gap: last `2018-01-28 22:00`, resumed `2018-01-29 23:00` — missing 24 hour(s)
- missing day: `2018-01-13`
- missing day: `2018-01-14`
- missing day: `2018-01-15`
- missing day: `2018-01-16`

## 3. File sizes histogram *median[lowest, highest]*

![Screeners 2017-2018 collection size histogram](figures/screeners-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/screeners-downloads-by-week-eoy-screeners-2017-2018-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![screeners downloads by day](figures/screeners-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/geojson.cumulative/screeners-cumulative-aggregate.geojson.gz" data-map-title="Screeners 2017-2018 — screeners" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Screeners 2017-2018 (screeners) cumulative data map in new window" title="Opens interactive map for Screeners 2017-2018 (screeners) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.27 | 29.49 | 22.71 | 29.53 | 3.33 | 1.08 |

### Network infrastructure

[![Screeners 2017-2018 cumulative map](figures/screeners-carto.png)](figures/screeners-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/screeners-data-ge-1080p.webp)](figures/screeners-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/screeners-data-lt-1080p.webp)](figures/screeners-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
