---
title: Hybrid Physics–Data-Driven Reduced-Order Modeling for Aerodynamic Load Inversion Considering Structural Field Uncertainty
publication_types:
  - "2"
authors:
  - Yaru Liu
  - Lei Wang
  - Xuan Zhou
  - Zeshang Li
  - Yuewu Wang

author_notes:
  - Beihang University
  - Beihang University, Corresponding Author
  - Beihang University
  - Beihang University
  - Beijing University of Technology

doi: 10.1016/j.cma.2025.118504
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Comput. Methods Appl. Mech. Eng.
abstract: Aerodynamic loads are essential for structural safety assessment in aeronautical engineering, yet direct measurement or high-fidelity simulation is often challenging. During service, structural parameters are affected by multi-source uncertainties, leading to limited samples and complex spatial variability. This paper proposes a hybrid physics–data-driven reduced-order modeling (ROM) framework for aerodynamic load inversion under structural field uncertainty. The ROM maps high-dimensional aerodynamic loads into a low-dimensional feature space, transforming the inversion into a feature coefficient prediction problem. A physics-decoded neural network (PDNN) is then established, where the data-driven module captures the mapping between responses and feature coefficients, and the physics-constrained module ensures consistency with physical laws. To characterize field uncertainty, the interval Karhunen–Loève decomposition (IKLD) is employed to represent uncertain fields as a finite set of parameters, while an adaptive Kriging surrogate model (AKSM) propagates uncertainty to yield interval estimates of loads. Numerical and experimental results demonstrate that the proposed method achieves high accuracy, robustness, and practicality under sparse measurement, noise, and uncertain field conditions.
draft: false
featured: false
tags:
  - Aerodynamic Load Inversion
  - Hybrid Physics–Data-Driven Modeling
  - Reduced-Order Modeling
  - Interval Field Uncertainty
  - Adaptive Kriging
categories:
  - Digital Twin
  - Structural Analysis
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: The hybrid physics–data-driven reduced-order modeling framework for aerodynamic load inversion.
summary: "A hybrid physics–data-driven reduced-order modeling framework is proposed for aerodynamic load inversion under structural field uncertainty."
date: 2025-10-24
---