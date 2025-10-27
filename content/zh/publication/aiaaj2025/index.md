---
title: 面向机体数字孪生的实时在役载荷跟踪方法
publication_types:
  - "2"
authors:
  - 周轩
  - 董雷霆
  - Michal Dziendzikowski
  - Krzysztof Dragan
  - Marco Giglio
  - Claudio Sbarufatti

author_notes:
  - 北京航空航天大学
  - 北京航空航天大学，通讯作者
  - 空军技术研究所，波兰
  - 空军技术研究所，波兰
  - 米兰理工大学，意大利
  - 米兰理工大学，意大利，通讯作者

doi: 10.2514/1.J064671
publication: AIAA Journal
publication_short: AIAA J
abstract: 精确的载荷监测对于构建可靠的载荷谱和推动机体数字孪生在服役过程中的演化至关重要。然而，受限于传感器数量、重量与成本，许多机型缺乏足够的应变测点，导致载荷跟踪困难。本文提出一种结合深度学习应变预测与改进逆–直接法的实时载荷跟踪方法，用于传感器受限飞机的机体载荷评估。首先，基于飞行试验数据训练引入时序特征的深度学习模型，以飞行参数为输入高精度预测离散应变点，应变预测性能显著优于传统回归方法。其次，采用基于降阶气动模态的改进逆–直接方法，提高有限测点条件下的载荷反演精度。两者结合后，系统可在仅使用飞行参数输入的情况下实时预测全场载荷与变形，实现传感器自由的机体健康监测。基于3.2米翼展无人机的实验验证结果表明，该方法具有高精度、强泛化性和良好可实施性，为现役机群数字孪生化改造提供了可行途径。
draft: false
featured: false
tags:
  - 数字孪生
  - 实时载荷监测
  - 深度学习
  - 逆–直接法
  - 降阶建模
  - Digital Twin
  - Real-Time Load Tracking
  - Deep Learning
  - Inverse-Direct Method
  - Reduced-Order Modeling
categories:
  - 数字孪生
  - 结构健康监测
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Real-time in-service load tracking framework for airframe digital twins.
summary: "提出了一种基于深度学习与逆–直接法结合的实时载荷跟踪方法，可实现无传感器条件下的机体载荷监测。"
date: 2025-08-01
---
