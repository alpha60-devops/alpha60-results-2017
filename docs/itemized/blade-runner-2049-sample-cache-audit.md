---
layout: default
title: "blade-runner-2049 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# blade-runner-2049 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Blade Runner 2049 |
| Collection key | `blade-runner-2049` |
| imdb_id | [tt1856101](https://www.imdb.com/title/tt1856101/) |
| wikipedia_url | [Blade Runner 2049](https://en.wikipedia.org/wiki/Blade_Runner_2049) |
| Sample dates | 2017-12-22-to-2018-03-31 |
| Sample days | 100 |
| BTIH count | 47 |
| Unique BTIH count | 47 |
| Downloaders total | 8,193,457 |
| Uploaders total | 2,336,428 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-08T01:09:42Z
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

![Blade Runner 2049 collection size histogram](figures/blade-runner-2049-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/blade-runner-2049-downloads-by-week-blade-runner-2049-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![blade-runner-2049 downloads by day](figures/blade-runner-2049-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.47 | 19.64 | 21.88 | 34.57 | 1.83 | 0.83 |

### Cumulative network infrastructure

[![Blade Runner 2049 cumulative map](figures/blade-runner-2049-carto.png)](figures/blade-runner-2049-carto-4k.webp){:target="_blank" rel="noopener"}

UNAVAILABLE — no cumulative data maps were rendered.
