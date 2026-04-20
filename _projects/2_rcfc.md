---
layout: page
title: RCFC — Lifelong Robot Imitation Learning
description: Prototype replay and coarse-to-fine compatibility for lifelong imitation learning.
img: assets/img/prcfc.png
importance: 2
category: research
related_publications: false
---

**RCFC** is a lightweight framework for lifelong imitation learning that combines compact **prototype replay** with **coarse-to-fine compatibility regularization** to reduce catastrophic forgetting and improve cross-task transfer.

- Maintains a small set of per-task prototypes instead of full trajectory buffers.
- A two-stage compatibility loss aligns new policies with previous ones at both coarse (task-level) and fine (step-level) granularities.
- Evaluated on the **LIBERO** benchmark across sequential task streams, with consistent gains over replay- and regularization-based baselines. Currently under review at **ICML 2026**.
