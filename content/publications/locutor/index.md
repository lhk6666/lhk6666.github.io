---
title: 'What Can Language Intents Contribute to Planned-Route Execution?'
authors:
  - me
date: '2026-11-01T00:00:00Z'
publication_types: ['article']
publication: 'arXiv preprint (coming soon)'
abstract: >-
  Once a semantic map has grounded the goal and planned the route, what can
  vision-and-language navigation (VLN) still contribute to executing it?
  Locutor plans a route on a visual topological map, verbalizes it into a
  sequence of metrically underspecified navigation intents such as "turn left
  to enter the kitchen", and uses coarse visual localization only to decide
  which intent is active. A local language-conditioned policy such as CoFL-S
  then realizes each intent from the current view as a continuous trajectory.
  In preliminary simulation (HM3D, MP3D) and real-robot experiments, geometric
  waypoint tracking performs comparably when poses are accurate, while intent
  execution succeeds more often when poses are only approximate. Compared with
  direction-only intents, landmark-referenced intents also reduce ambiguity at
  turns and improve stopping accuracy.
summary: >-
  Locutor turns map-planned routes into landmark-referenced language intents
  for a VLN policy, tolerating coarser localization than waypoint tracking.
featured: true
# The card thumbnail (featured.png) is a 16:9 crop of the teaser; the full
# teaser is shown in the page body instead. Replace with featured.gif later.
image:
  preview_only: true
---

## Overview

<figure>
  <a href="/publications/locutor/teaser.png" target="_blank" rel="noopener" title="Open the full-resolution figure">
    <img src="/publications/locutor/teaser.png" width="2560" height="840" loading="lazy" alt="Locutor overview: a visual topological map grounds the language goal and plans the route, the route is verbalized into a sequence of language intents executed from the current view, and landmark intents hold up better than waypoint tracking under coarse poses.">
  </a>
  <figcaption>Locutor connects semantic-map-based planning with language-conditioned visual execution. Left: the visual topological map. Middle: the planned route becomes a sequence of language intents. Right: landmark intents tolerate coarse poses better than direction-only intents and waypoint tracking with DWA. Click the figure to open it at full resolution.</figcaption>
</figure>

The paper will be available on arXiv soon, and a demo video will follow.
