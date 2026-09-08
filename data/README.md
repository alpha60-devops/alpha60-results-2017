# Alpha60 results: year 2017 campaign

This directory holds the in-progress year-2017 Alpha60 results dataset. The
frozen campaign inventory contains 14 media objects at SHA-256
`93790aaf31bbe3cf4faf8ae2b249f71f83859022bb221daa24e8862518ff7a8c`.

## Campaign inputs

- `txt/year-2017-0-media-objects.txt`: canonical ordered inventory.
- `txt/year-2017-cache-aliases.tsv`: empty alias receipt; every canonical
  key maps directly to its same-named gold cache directory and member key.
- `txt/year-2017-cache-archive-overrides.json`: explicitly reviewed archive
  endpoint selections, if any.
- `txt/year-2017-cache-archive-map.json`: exact archive paths, sizes,
  SHA-256 identities, canonical sample contracts, sparse intervals, and
  byte-balanced ord/eureka ownership.

Cache archives and raw samples are immutable external campaign inputs and are
never committed to this repository. Generated data, figures, audit pages, and
the final checksum/release manifests are added only by the verified campaign
pipeline.
