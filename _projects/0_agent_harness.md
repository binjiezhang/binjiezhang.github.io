---
layout: page
title: Harness Framework
description: A declarative, skill-based harness for rapidly composing LLM agents.
img: assets/img/agent_harness.png
importance: 1
category: agent systems
related_publications: false
---

A declarative **agent harness** that turns hard-coded multi-agent pipelines into composable, configuration-driven **skills**.

- **LLM semantic routing** selects the right skill from natural-language intent, so new capabilities are added by writing a skill spec rather than new code.
- **Progressive disclosure** loads only the context a task needs, keeping prompts small and routing cheap.
- A unified tool registry, permission interception, and a sandboxed execution layer make skills safe to run in production.
- A conversational *skill studio* lets non-engineers author and validate new skills end-to-end.

*Built during my AI research internship at TikTok (ByteDance) for large-scale e-commerce governance.*
