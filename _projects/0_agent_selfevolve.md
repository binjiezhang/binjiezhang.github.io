---
layout: page
title: Self-Evolution
description: Agent-native loops that let models keep improving after deployment.
img: assets/img/agent_selfevolve.png
importance: 4
category: agent systems
related_publications: false
---

An **agent-native** loop where the LLM is the decision-maker that keeps a model improving with minimal human intervention.

- Closed cycle: **diagnose → hypothesize → pilot → gate → train → reflect**.
- Cheap **pilot runs** are gated before committing to full training, so compute is spent only on promising directions.
- An append-only **lesson memory** turns failed runs into reusable knowledge for the next cycle.

*Built during my AI research internship at TikTok (ByteDance) as a self-evolving training platform.*
