---
layout: page
title: ReGRPO — Reflection-Augmented RL for Tool-Using Agents
description: Group-relative policy optimization with structured self-reflection for long-horizon tool use.
img: assets/img/regrpo.png
importance: 1
category: research
related_publications: false
---

**ReGRPO** is a reflection-augmented variant of **group-relative policy optimization** for tool-using agents.

- Injects **structured self-reflection** into the agent's multi-modal chain-of-thought during training.
- The group-relative signal stabilizes credit assignment over long tool-use trajectories, while reflection turns failed rollouts into reusable learning signal.
- Improves tool-selection reward and sample efficiency on long-horizon, multi-tool tasks &mdash; accepted at **ECCV 2026**.
