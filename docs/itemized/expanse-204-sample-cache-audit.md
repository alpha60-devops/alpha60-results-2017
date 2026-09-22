---
layout: default
title: "expanse-204 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# expanse-204 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Expanse |
| Collection key | `expanse-204` |
| imdb_id | [tt3230854](https://www.imdb.com/title/tt3230854/) |
| wikipedia_url | [The Expanse (TV series)](https://en.wikipedia.org/wiki/The_Expanse_(TV_series)) |
| Sample dates | 2017-02-16-to-2017-02-19 |
| Sample days | 4 |
| BTIH count | 19 |
| Unique BTIH count | 19 |
| Downloaders total | 134,036 |
| Uploaders total | 84,830 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-09T01:10:35Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/expanse-204.xz`
- Hour directories: 24
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 23 (69 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2017-02-16 00:00`, resumed `2017-02-16 04:00` — missing 3 hour(s)
- hourly gap: last `2017-02-16 04:00`, resumed `2017-02-16 08:00` — missing 3 hour(s)
- hourly gap: last `2017-02-16 08:00`, resumed `2017-02-16 12:00` — missing 3 hour(s)
- hourly gap: last `2017-02-16 12:00`, resumed `2017-02-16 16:00` — missing 3 hour(s)
- hourly gap: last `2017-02-16 16:00`, resumed `2017-02-16 20:00` — missing 3 hour(s)
- hourly gap: last `2017-02-16 20:00`, resumed `2017-02-17 00:00` — missing 3 hour(s)
- hourly gap: last `2017-02-17 00:00`, resumed `2017-02-17 04:00` — missing 3 hour(s)
- hourly gap: last `2017-02-17 04:00`, resumed `2017-02-17 08:00` — missing 3 hour(s)
- hourly gap: last `2017-02-17 08:00`, resumed `2017-02-17 12:00` — missing 3 hour(s)
- hourly gap: last `2017-02-17 12:00`, resumed `2017-02-17 16:00` — missing 3 hour(s)
- hourly gap: last `2017-02-17 16:00`, resumed `2017-02-17 20:00` — missing 3 hour(s)
- hourly gap: last `2017-02-17 20:00`, resumed `2017-02-18 00:00` — missing 3 hour(s)
- hourly gap: last `2017-02-18 00:00`, resumed `2017-02-18 04:00` — missing 3 hour(s)
- hourly gap: last `2017-02-18 04:00`, resumed `2017-02-18 08:00` — missing 3 hour(s)
- hourly gap: last `2017-02-18 08:00`, resumed `2017-02-18 12:00` — missing 3 hour(s)
- hourly gap: last `2017-02-18 12:00`, resumed `2017-02-18 16:00` — missing 3 hour(s)
- hourly gap: last `2017-02-18 16:00`, resumed `2017-02-18 20:00` — missing 3 hour(s)
- hourly gap: last `2017-02-18 20:00`, resumed `2017-02-19 00:00` — missing 3 hour(s)
- hourly gap: last `2017-02-19 00:00`, resumed `2017-02-19 04:00` — missing 3 hour(s)
- hourly gap: last `2017-02-19 04:00`, resumed `2017-02-19 08:00` — missing 3 hour(s)
- hourly gap: last `2017-02-19 08:00`, resumed `2017-02-19 12:00` — missing 3 hour(s)
- hourly gap: last `2017-02-19 12:00`, resumed `2017-02-19 16:00` — missing 3 hour(s)
- hourly gap: last `2017-02-19 16:00`, resumed `2017-02-19 20:00` — missing 3 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![The Expanse collection size histogram](figures/expanse-204-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/expanse-204-downloads-by-week-expanse-204-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![expanse-204 downloads by day](figures/expanse-204-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/geojson.cumulative/expanse-204-cumulative-aggregate.geojson.gz" data-map-title="The Expanse — expanse-204" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Expanse (expanse-204) cumulative data map in new window" title="Opens interactive map for The Expanse (expanse-204) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.97 | 20.12 | 7.95 | 31.30 | 5.10 | 0.29 |

### Network infrastructure

[![The Expanse cumulative map](figures/expanse-204-carto.png)](figures/expanse-204-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/expanse-204-data-ge-1080p.webp)](figures/expanse-204-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/expanse-204-data-lt-1080p.webp)](figures/expanse-204-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
