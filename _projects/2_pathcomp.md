---
layout: page
title: PathComp — Lifelong Vision–Language–Action Adaptation
description: Path-anchored compatibility for continually fine-tuning VLA policies.
img: assets/img/prcfc.png
importance: 2
category: research
related_publications: false
---

**PathComp** keeps a pretrained vision–language–action (VLA) policy improving on new skills without breaking the old ones, by anchoring compatibility along the model's **computation path** rather than only at the output head.

- Stores compact **path anchors** at multiple stages of the network to preserve prior behaviors during continual fine-tuning.
- Anchors are small and reliability-weighted, avoiding the cost of full trajectory replay.
- Achieves the best matched-protocol average across the **LIBERO** and **ManiSkill3** lifelong-adaptation benchmarks. Currently under review at **NeurIPS 2026**.
