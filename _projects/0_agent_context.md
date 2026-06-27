---
layout: page
title: Context Management
description: Context engineering for long-horizon, multi-step agents.
img: assets/img/agent_context.png
importance: 3
category: agent systems
related_publications: false
---

Techniques for keeping an agent's **working context** small, relevant, and cheap across long tool-use trajectories.

- Layered loading so only task-relevant references and history enter the prompt.
- Summarization and selective recall to bound context growth over many steps.
- Tight coupling with the memory layer, so retrieval and context selection reinforce each other.

*Developed during my AI research internship at TikTok (ByteDance).*
