---
layout: page
title: Memory Optimization
description: Training-free optimization of agent memory for long-horizon tool use.
img: assets/img/agent_memory.png
importance: 2
category: agent systems
related_publications: false
---

**Training-free** optimization of an agent's memory &mdash; deciding what to **retrieve**, **write**, and **evict** &mdash; without any gradient updates.

- Treats memory policy as a search / optimization problem over read–write–evict decisions.
- Targets long-horizon, multi-step tool-use agents, where naïve context growth becomes the bottleneck.
- Complements context management to keep the working set small and relevant.

*Research line from my AI research internship at TikTok (ByteDance); paper in preparation.*
