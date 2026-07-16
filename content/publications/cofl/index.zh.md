---
title: 'CoFL: Continuous Flow Fields for Language-Conditioned Navigation'
authors:
  - Haokun Liu
  - Zhaoqi Ma
  - Yicheng Chen
  - Masaki Kitagawa
  - Wentao Zhang
  - Zicen Xiong
  - Jinjie Li
  - Moju Zhao
date: '2026-03-01T00:00:00Z'
publication_types: ['article']
publication: 'arXiv 预印本（审稿中）'
abstract: >-
  CoFL 是一个端到端策略：将鸟瞰图（BEV）观测与语言指令映射为用于导航的连续
  流场，把导航问题重新表述为「以工作空间为条件的场学习」，而非「以起点为条件
  的轨迹预测」。轨迹可从任意起点通过对预测流场数值积分生成，从而实现简单的
  实时展开与闭环恢复。我们基于 Matterport3D 和 ScanNet 的语义地图程序化标注，
  构建了超过 50 万对 BEV 图像-指令数据集。CoFL 显著优于模块化 VLM 规划器和
  轨迹生成策略，并已零样本部署于真实环境实验。
summary: >-
  将语言条件导航重构为工作空间上的连续流场学习：任意起点经场积分生成轨迹，
  基于 50 万+ 程序化标注的 BEV-指令数据训练，可零样本部署到真实机器人。
featured: true
url_pdf: 'https://arxiv.org/pdf/2603.02854'
links:
  - name: arXiv
    url: 'https://arxiv.org/abs/2603.02854'
  - name: 视频
    url: 'https://youtu.be/gccph7X3fFg'
---

## 演示视频

{{< youtube gccph7X3fFg >}}
