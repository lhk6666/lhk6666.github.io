---
title: 'CoFL: Continuous Flow Fields for Language-Conditioned Navigation'
authors:
  - me
  - Zhaoqi Ma
  - Yicheng Chen
  - Masaki Kitagawa
  - Wentao Zhang
  - Zicen Xiong
  - Jinjie Li
  - Moju Zhao
date: '2026-03-01T00:00:00Z'
publication_types: ['article']
publication: 'arXiv preprint (under review)'
abstract: >-
  CoFL is an end-to-end policy that maps a bird's-eye-view (BEV) observation
  and a language instruction to a continuous flow field for navigation,
  reformulating navigation as workspace-conditioned field learning rather than
  start-conditioned trajectory prediction. Trajectories are generated from any
  start point by numerically integrating the predicted field, enabling simple
  real-time rollout and closed-loop recovery. We build a dataset of over 500k
  BEV image–instruction pairs, each procedurally annotated with a flow field
  and trajectory derived from semantic maps built on Matterport3D and ScanNet.
  CoFL significantly outperforms modular VLM-based planners and trajectory
  generation policies, and is deployed zero-shot in real-world experiments.
summary: >-
  Reformulates language-conditioned navigation as learning a continuous flow
  field over the workspace: trajectories from any start point by field
  integration, trained on 500k+ procedurally annotated BEV–instruction pairs,
  with zero-shot real-world deployment.
featured: true
url_pdf: 'https://arxiv.org/pdf/2603.02854'
links:
  - name: arXiv
    url: 'https://arxiv.org/abs/2603.02854'
  - name: Video
    url: 'https://youtu.be/gccph7X3fFg'
---

## Video

{{< youtube gccph7X3fFg >}}
