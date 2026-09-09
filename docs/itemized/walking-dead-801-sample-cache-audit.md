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

## 2. Sample coverage report

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

## 3. Media objects file size histogram

![The Walking Dead collection size histogram](figures/walking-dead-801-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

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

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.13 | 27.28 | 14.46 | 27.47 | 2.79 | 0.69 |

### Cumulative network infrastructure

[![The Walking Dead cumulative map](figures/walking-dead-801-carto.png)](figures/walking-dead-801-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/walking-dead-801-data-ge-1080p.webp)](figures/walking-dead-801-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/walking-dead-801-data-lt-1080p.webp)](figures/walking-dead-801-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
