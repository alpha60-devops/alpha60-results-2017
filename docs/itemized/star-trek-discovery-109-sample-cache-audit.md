---
layout: default
title: "star-trek-discovery-109 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# star-trek-discovery-109 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Star Trek Discovery |
| Collection key | `star-trek-discovery-109` |
| imdb_id | [tt5171438](https://www.imdb.com/title/tt5171438/) |
| wikipedia_url | [Star Trek: Discovery](https://en.wikipedia.org/wiki/Star_Trek:_Discovery) |
| Sample dates | 2017-11-13-to-2017-12-11 |
| Sample days | 29 |
| BTIH count | 100 |
| Unique BTIH count | 78 |
| Downloaders total | 4,840,256 |
| Uploaders total | 927,602 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-09T01:10:36Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/star-trek-discovery-109.xz`
- Hour directories: 681
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 4 (12 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2017-11-22 22:00`, resumed `2017-11-23 00:00` — missing 1 hour(s)
- hourly gap: last `2017-11-25 14:00`, resumed `2017-11-25 23:01` — missing 8 hour(s)
- hourly gap: last `2017-11-26 16:00`, resumed `2017-11-26 18:00` — missing 1 hour(s)
- hourly gap: last `2017-11-28 00:00`, resumed `2017-11-28 03:00` — missing 2 hour(s)

## 3. File sizes histogram *median[lowest, highest]*

![Star Trek Discovery collection size histogram](figures/star-trek-discovery-109-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/star-trek-discovery-109-downloads-by-week-star-trek-discovery-109-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![star-trek-discovery-109 downloads by day](figures/star-trek-discovery-109-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2017/refs/heads/main/data/geojson.cumulative/star-trek-discovery-109-cumulative-aggregate.geojson.gz" data-map-title="Star Trek Discovery — star-trek-discovery-109" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Star Trek Discovery (star-trek-discovery-109) cumulative data map in new window" title="Opens interactive map for Star Trek Discovery (star-trek-discovery-109) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.25 | 36.46 | 17.74 | 24.79 | 2.15 | 10.10 |

### Network infrastructure

[![Star Trek Discovery cumulative map](figures/star-trek-discovery-109-carto.png)](figures/star-trek-discovery-109-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/star-trek-discovery-109-data-ge-1080p.webp)](figures/star-trek-discovery-109-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/star-trek-discovery-109-data-lt-1080p.webp)](figures/star-trek-discovery-109-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
