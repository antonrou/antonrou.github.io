---
layout: page
title: Evolutionary RL A-Life Testbed
description: Programmatic, explainable policies for a predator–prey artificial-life world
img: assets/img/3.jpg
importance: 1
category: research
related_publications: true
---

An open-source reimplementation of the classic **Ackley & Littman (1991)** predator–prey
evolutionary reinforcement learning artificial-life testbed, built during a graduate-level
research seminar (CMPUT 497/651) under **Dr. Vadim Bulitko** in the RLAI Lab at the University
of Alberta.

The project replaces opaque, black-box neural-network policies with **explainable, differentiable
decision lists** and rigorously evaluates policy viability across **4,000 independent trials**
using Kaplan–Meier survival curves and restricted mean survival time — metrics absent from the
original study {% cite roupassov2025alife %}.

Programmatic agents significantly outlasted neural networks (log-rank $p \approx 4.1\times10^{-72}$),
surviving on average **201.69 steps longer** (95% CI [180.14, 223.25]).

Code and full specification: [github.com/antonrou/erl](https://github.com/antonrou/erl)
