---
layout: default
title: "star-wars-last-jedi Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# star-wars-last-jedi sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Star Wars The Last Jedi |
| Collection key | `star-wars-last-jedi` |
| imdb_id | [tt2527336](https://www.imdb.com/title/tt2527336/) |
| wikipedia_url | [Star Wars: The Last Jedi](https://en.wikipedia.org/wiki/Star_Wars:_The_Last_Jedi) |
| Sample dates | 2017-12-29-to-2018-03-31 |
| Sample days | 93 |
| BTIH count | 82 |
| Unique BTIH count | 77 |
| Downloaders total | 7,088,172 |
| Uploaders total | 1,593,581 |
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

![Star Wars The Last Jedi collection size histogram](figures/star-wars-last-jedi-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/star-wars-last-jedi-downloads-by-week-star-wars-last-jedi-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![star-wars-last-jedi downloads by day](figures/star-wars-last-jedi-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.16 | 25.62 | 22.42 | 29.08 | 2.98 | 0.55 |

### Cumulative network infrastructure

[![Star Wars The Last Jedi cumulative map](figures/star-wars-last-jedi-carto.png)](figures/star-wars-last-jedi-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/star-wars-last-jedi-data-ge-1080p.webp)](figures/star-wars-last-jedi-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/star-wars-last-jedi-data-lt-1080p.webp)](figures/star-wars-last-jedi-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
