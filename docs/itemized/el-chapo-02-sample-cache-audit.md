---
layout: default
title: "el-chapo-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# el-chapo-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | El Chapo |
| Collection key | `el-chapo-02` |
| imdb_id | [tt6692188](https://www.imdb.com/title/tt6692188/) |
| wikipedia_url | [El Chapo (TV series)](https://en.wikipedia.org/wiki/El_Chapo_(TV_series)) |
| Sample dates | 2017-12-16-to-2017-12-23 |
| Sample days | 8 |
| BTIH count | 246 |
| Unique BTIH count | 234 |
| Downloaders total | 705,862 |
| Uploaders total | 153,326 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-08T01:09:20Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/el-chapo-02.xz`
- Hour directories: 497
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![El Chapo collection size histogram](figures/el-chapo-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/el-chapo-02-downloads-by-week-el-chapo-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![el-chapo-02 downloads by day](figures/el-chapo-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.89 | 33.51 | 19.02 | 27.11 | 1.66 | 8.76 |

### Cumulative network infrastructure

[![El Chapo cumulative map](figures/el-chapo-02-carto.png)](figures/el-chapo-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/el-chapo-02-data-ge-1080p.webp)](figures/el-chapo-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/el-chapo-02-data-lt-1080p.webp)](figures/el-chapo-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
