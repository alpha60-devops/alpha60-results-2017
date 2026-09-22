---
layout: default
title: "walking-dead-807 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# walking-dead-807 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Walking Dead |
| Collection key | `walking-dead-807` |
| imdb_id | [tt1520211](https://www.imdb.com/title/tt1520211/) |
| wikipedia_url | [The Walking Dead (TV series)](https://en.wikipedia.org/wiki/The_Walking_Dead_(TV_series)) |
| Sample dates | 2017-12-04-to-2017-12-18 |
| Sample days | 15 |
| BTIH count | 89 |
| Unique BTIH count | 78 |
| Downloaders total | 4,475,596 |
| Uploaders total | 962,812 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-08T01:09:32Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/walking-dead-807.xz`
- Hour directories: 352
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![The Walking Dead collection size histogram](figures/walking-dead-807-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/walking-dead-807-downloads-by-week-walking-dead-807-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![walking-dead-807 downloads by day](figures/walking-dead-807-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/geojson.cumulative/walking-dead-807-cumulative-aggregate.geojson.gz" data-map-title="The Walking Dead — walking-dead-807" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Walking Dead (walking-dead-807) cumulative data map in new window" title="Opens interactive map for The Walking Dead (walking-dead-807) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.20 | 36.30 | 18.56 | 23.15 | 2.31 | 6.89 |

### Network infrastructure

[![The Walking Dead cumulative map](figures/walking-dead-807-carto.png)](figures/walking-dead-807-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/walking-dead-807-data-ge-1080p.webp)](figures/walking-dead-807-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/walking-dead-807-data-lt-1080p.webp)](figures/walking-dead-807-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
