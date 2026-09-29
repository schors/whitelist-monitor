# Whitelist Monitor — presentation

A three-slide English briefing about the collection, resolution, and aggregate statistics of official Russian mobile internet whitelist publications.

Open the [published presentation](https://schors.github.io/whitelist-monitor/). Use the arrow keys or scroll between slides.

The page reads `dashboard.json`. The JSON is an exported snapshot generated from the canonical Whitelist Monitor catalog by `tools/aggregate.py`. This public repository contains the presentation and aggregate snapshot only; it does not contain the source catalog or evidence. Its `as_of` field identifies the data date. The canonical aggregate workflow publishes this file when its `PUBLIC_SITE_TOKEN` credential is configured. The scheduled monitor also copies verified current snapshots directly through the connected GitHub tools.

The statistics describe official publication claims and resolved web addresses. They do not establish actual network reachability during restrictions.
