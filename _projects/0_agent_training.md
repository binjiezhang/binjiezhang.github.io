---
layout: page
title: Search Agent Training — Ongoing
description:
  Faithful trajectory data, aligned training objectives, and independent
  evaluation.
importance: 7
category: agent systems
related_publications: false
---

I am adapting existing Tako data and training components to Agentic Search. This is **ongoing design and integration work**.

**Data.** Preserve the evidence the agent actually observed, its original actions, runtime repairs, and final rendered outcomes. Refinement proposals should retain provenance and use a clear repair owner.

**Training.** Compare supervised fine-tuning, reinforcement learning, and on-policy distillation according to the behavior each objective should improve. Model-visible inputs and trainable token boundaries require separate validation for each backend.

**Evaluation.** Assess both native agent behavior and the delivered product: grounded decisions, tool-call validity, usable results, safety, latency, and cost. Use independent cases and regression checks.

Existing infrastructure is reused; measured Search model-training gains are not yet claimed.
