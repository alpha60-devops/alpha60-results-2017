---
layout: default
title: "stranger-things-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# stranger-things-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Stranger Things |
| Collection key | `stranger-things-02` |
| imdb_id | [tt4574334](https://www.imdb.com/title/tt4574334/) |
| wikipedia_url | [Stranger Things](https://en.wikipedia.org/wiki/Stranger_Things) |
| Sample dates | 2017-10-27-to-2017-12-31 |
| Sample days | 66 |
| BTIH count | 274 |
| Unique BTIH count | 209 |
| Downloaders total | 33,765,789 |
| Uploaders total | 13,814,398 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-08T01:09:32Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/stranger-things-02.xz`
- Hour directories: 1564
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 1 (11 missing hours)
- Missing days: 0

### Sample archive discontinuities

- hourly gap: last `2017-12-30 12:00`, resumed `2017-12-31 00:22` — missing 11 hour(s)

## 3. Media objects file size histogram

![Stranger Things collection size histogram](figures/stranger-things-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/stranger-things-02-downloads-by-week-stranger-things-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![stranger-things-02 downloads by day](figures/stranger-things-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.99 | 24.65 | 30.09 | 31.81 | 2.83 | 2.06 |

### Cumulative network infrastructure

[![Stranger Things cumulative map](figures/stranger-things-02-carto.png)](figures/stranger-things-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/stranger-things-02-data-ge-1080p.webp)](figures/stranger-things-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/stranger-things-02-data-lt-1080p.webp)](figures/stranger-things-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
