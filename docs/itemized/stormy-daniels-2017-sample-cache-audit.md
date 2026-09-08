---
layout: default
title: "stormy-daniels-2017 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# stormy-daniels-2017 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Stormy Daniels |
| Collection key | `stormy-daniels-2017` |
| imdb_id | UNAVAILABLE |
| wikipedia_url | UNAVAILABLE — no English Wikipedia page exists |
| Sample dates | 2018-01-20-to-2018-03-31 |
| Sample days | 71 |
| BTIH count | 50 |
| Unique BTIH count | 46 |
| Downloaders total | 356,252 |
| Uploaders total | 96,566 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

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

## 3. Media objects file size histogram

![Stormy Daniels collection size histogram](figures/stormy-daniels-2017-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/stormy-daniels-2017-downloads-by-week-stormy-daniels-2017-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![stormy-daniels-2017 downloads by day](figures/stormy-daniels-2017-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.38 | 27.04 | 26.40 | 19.92 | 1.62 | 4.41 |

### Cumulative network infrastructure

[![Stormy Daniels cumulative map](figures/stormy-daniels-2017-carto.png)](figures/stormy-daniels-2017-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/stormy-daniels-2017-data-ge-1080p.webp)](figures/stormy-daniels-2017-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/stormy-daniels-2017-data-lt-1080p.webp)](figures/stormy-daniels-2017-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
