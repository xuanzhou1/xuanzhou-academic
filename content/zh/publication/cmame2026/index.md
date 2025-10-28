---
title: 考虑结构场不确定性的气动载荷反演混合物理–数据驱动降阶建模方法
publication_types:
  - "2"
authors:
  - 刘亚儒
  - 王磊
  - 周轩
  - 李泽商
  - 王岳武

author_notes:
  - 北京航空航天大学
  - 北京航空航天大学，通讯作者
  - 北京航空航天大学
  - 北京航空航天大学
  - 北京工业大学

doi: 10.1016/j.cma.2025.118504
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Comput. Methods Appl. Mech. Eng.
abstract: 气动载荷是航空航天器结构安全评估中的关键因素，但直接测量或高保真模拟往往面临挑战。服役过程中，结构参数受到多源不确定性影响，表现为样本有限且空间分布复杂。为此，本文提出一种考虑结构场不确定性的气动载荷反演方法，可从稀疏测量中重构载荷边界。首先，基于空间分布特征的降阶建模（ROM）将高维气动载荷映射至低维特征空间，将载荷反演问题转化为特征系数预测。随后，构建混合物理–数据驱动神经网络（PDNN），通过数据驱动模块学习响应–系数映射关系，并通过物理约束模块确保物理一致性，从而在小样本与高噪声条件下显著提升性能。为描述结构场不确定性，采用区间Karhunen-Loève分解（IKLD）将不确定场转化为有限不确定参数集合，并结合自适应克里金代理模型（AKSM）实现不确定性传播，从而得到气动载荷的区间估计。数值与实验验证结果表明，该方法在稀疏测量、噪声干扰和场不确定条件下均表现出高精度、强鲁棒性和良好实用性。
draft: false
featured: false
tags:
  - 气动载荷反演
  - 混合物理数据驱动方法
  - 降阶建模
  - 区间场不确定性
  - 自适应克里金模型
  - Aerodynamic Load Inversion
  - Hybrid Physics-Data-Driven Modeling
  - Reduced-Order Modeling
  - Interval Field Uncertainty
  - Adaptive Kriging
categories:
  - 数字孪生
  - 结构分析
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: The hybrid physics–data-driven reduced-order modeling framework for aerodynamic load inversion.
summary: "提出了一种结合降阶建模与混合物理–数据驱动神经网络的气动载荷反演方法，可在结构场不确定条件下实现高精度载荷重构。"
date: 2025-10-24
---