---
layout: page
title: Task-Agnostic Compatible Adapter (TaCA)
description: Upgrade visual foundation models without retraining downstream tasks.
img: assets/img/taca.png
importance: 4
category: research
related_publications: false
---

**TaCA** is a parameter-efficient adapter that enables seamless upgrades between visual foundation models (e.g. across **CLIP** variants) **without retraining downstream tasks**.

- Learns a lightweight alignment between old and new backbones.
- Preserves the downstream heads, so existing retrieval / recognition systems keep working during backbone upgrades.
- Validated on large-scale **video–text retrieval** and **video recognition** benchmarks.

[Paper](https://arxiv.org/pdf/2306.12642)
