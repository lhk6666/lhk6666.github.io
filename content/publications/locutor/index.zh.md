---
title: 'What Can Language Intents Contribute to Planned-Route Execution?'
authors:
  - Haokun Liu
date: '2026-11-01T00:00:00Z'
publication_types: ['article']
publication: 'arXiv 预印本（即将上线）'
# 摘要与简介写成单行：YAML 折行会在中文之间插入多余空格。
abstract: '当语义地图已经完成目标定位与路径规划之后，视觉语言导航（VLN）还能为路径的执行贡献什么？Locutor 在视觉拓扑地图上规划路径，将其转述为一串不含精确度量信息的语言导航意图（例如「左转进入厨房」），并且只用粗略的视觉定位来判断当前该执行哪一条意图；随后由局部语言条件策略（如 CoFL-S）根据当前视觉观测，把每条意图落实为连续轨迹。仿真（HM3D、MP3D）与真机的初步实验表明：位姿精确时，几何航点跟踪与意图执行表现相当；位姿只是粗略估计时，意图执行的成功率更高。与仅含方向的意图相比，引用可见地标的意图还能减少转弯处的歧义，并提高停止位置的准确性。'
summary: 'Locutor 将地图规划出的路径转述为引用地标的语言意图，交由 VLN 策略执行；相比几何航点跟踪，对粗略定位的容忍度更高。'
featured: true
# 卡片缩略图（featured.png）是 teaser 的 16:9 裁剪版；完整 teaser 放在正文中。
# 之后有演示动图时替换为 featured.gif。
image:
  preview_only: true
---

## 概览

<figure>
  <a href="/publications/locutor/teaser.png" target="_blank" rel="noopener" title="查看原图">
    <img src="/publications/locutor/teaser.png" width="2560" height="840" loading="lazy" alt="Locutor 概览：视觉拓扑地图负责定位语言目标并规划路径，路径被转述为一串语言意图并根据当前视野执行；在位姿粗略时，地标意图比航点跟踪更稳健。">
  </a>
  <figcaption>Locutor 将基于语义地图的规划与语言条件化的视觉执行连接起来。左：视觉拓扑地图；中：规划出的路径被转述为语言意图序列；右：在位姿粗略时，地标意图优于仅含方向的意图和航点 + DWA 跟踪。点击图片可查看原图。</figcaption>
</figure>

论文即将上线 arXiv，演示视频随后发布。
