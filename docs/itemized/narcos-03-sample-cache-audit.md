---
layout: default
title: "narcos-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# narcos-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Narcos |
| Collection key | `narcos-03` |
| imdb_id | [tt2707408](https://www.imdb.com/title/tt2707408/) |
| wikipedia_url | [Narcos](https://en.wikipedia.org/wiki/Narcos) |
| Sample dates | 2017-09-01-to-2017-10-01 |
| Sample days | 31 |
| BTIH count | 204 |
| Unique BTIH count | 193 |
| Downloaders total | 6,686,786 |
| Uploaders total | 3,251,712 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-08T01:09:27Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/narcos-03.xz`
- Hour directories: 657
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (77 missing hours)
- Missing days: 3

### Sample archive discontinuities

- hourly gap: last `2017-09-19 20:00`, resumed `2017-09-23 02:00` — missing 77 hour(s)
- missing day: `2017-09-20`
- missing day: `2017-09-21`
- missing day: `2017-09-22`

## 3. File sizes histogram *median[lowest, highest]*

![Narcos collection size histogram](figures/narcos-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/narcos-03-downloads-by-week-narcos-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![narcos-03 downloads by day](figures/narcos-03-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/geojson.cumulative/narcos-03-cumulative-aggregate.geojson.gz" data-map-title="Narcos — narcos-03" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Narcos (narcos-03) cumulative data map in new window" title="Opens interactive map for Narcos (narcos-03) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.66 | 14.98 | 36.98 | 33.08 | 2.61 | 0.46 |

### Network infrastructure

[![Narcos cumulative map](figures/narcos-03-carto.png)](figures/narcos-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/narcos-03-data-ge-1080p.webp)](figures/narcos-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/narcos-03-data-lt-1080p.webp)](figures/narcos-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
