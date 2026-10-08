---
layout: page
title: StateTrackBench — Executable State
description: Locating failures in message interpretation and evolving-state maintenance.
importance: 6
category: research
related_publications: false
---

**StateTrackBench: Executable Trajectories for Locating Where Language Models Lose Track of Evolving State**. **Under review at ICLR 2027.**

- Pair messages with typed intended updates and deterministic transitions.
- Replay gold state after each message to identify the first divergence.
- Separate parsing errors from state-execution and serialization errors.
- Use replay-time checks to localize failures and support targeted re-parsing.

The benchmark exposes incorrect internal state even when a final answer happens to be correct.
