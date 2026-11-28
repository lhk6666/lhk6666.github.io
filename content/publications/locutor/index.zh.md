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
---

上方的演示是 HM3D 中同一个任务片段的 4 倍速回放：目标同为「find the plant」，沿同一条规划路径，分别用两种意图执行。在岔路口，仅含方向的意图「walk forward」让机器人偏离了路径，经过两次 DWA 接管后在 61.2&nbsp;s 到达目标；地标意图「enter the dining room」则让机器人始终沿路径前进，16.6&nbsp;s 即到达目标。

论文即将上线 arXiv。
