---
layout: default
title: "walking-dead-801 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# walking-dead-801 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Walking Dead |
| Collection key | `walking-dead-801` |
| imdb_id | [tt1520211](https://www.imdb.com/title/tt1520211/) |
| wikipedia_url | [The Walking Dead (TV series)](https://en.wikipedia.org/wiki/The_Walking_Dead_(TV_series)) |
| Sample dates | 2017-10-23-to-2017-11-07 |
| Sample days | 16 |
| BTIH count | 110 |
| Unique BTIH count | 91 |
| Downloaders total | 4,294,781 |
| Uploaders total | 1,381,997 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-09T01:10:36Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/walking-dead-801.xz`
- Hour directories: 355
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 4 (25 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2017-10-29 04:00`, resumed `2017-10-29 06:00` — missing 1 hour(s)
- hourly gap: last `2017-11-01 12:00`, resumed `2017-11-02 04:00` — missing 15 hour(s)
- hourly gap: last `2017-11-02 07:00`, resumed `2017-11-02 10:00` — missing 2 hour(s)
- hourly gap: last `2017-11-03 11:00`, resumed `2017-11-03 19:00` — missing 7 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![The Walking Dead collection size histogram](figures/walking-dead-801-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/walking-dead-801-downloads-by-week-walking-dead-801-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![walking-dead-801 downloads by day](figures/walking-dead-801-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/geojson.cumulative/walking-dead-801-cumulative-aggregate.geojson.gz" data-map-title="The Walking Dead — walking-dead-801" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Walking Dead (walking-dead-801) cumulative data map in new window" title="Opens interactive map for The Walking Dead (walking-dead-801) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.13 | 27.28 | 14.46 | 27.47 | 2.79 | 0.69 |

### Network infrastructure

[![The Walking Dead cumulative map](figures/walking-dead-801-carto.png)](figures/walking-dead-801-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/walking-dead-801-data-ge-1080p.webp)](figures/walking-dead-801-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/walking-dead-801-data-lt-1080p.webp)](figures/walking-dead-801-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
