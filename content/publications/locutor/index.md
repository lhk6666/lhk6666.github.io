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
---

The demo above replays one HM3D episode at 4× speed: the same planned route to
the goal "find the plant", executed with two kinds of intents. At a fork, the
direction-only intent "walk forward" lets the robot veer off the route, and it
reaches the goal in 61.2&nbsp;s after two DWA takeovers. The landmark intent "enter
the dining room" keeps it on the route, and it reaches the goal in 16.6&nbsp;s.

The paper will be available on arXiv soon.
