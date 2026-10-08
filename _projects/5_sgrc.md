---
layout: page
title: SGRC — Selective Partition Repair
description:
  Recovering useful group-relative training signals from verifier false
  negatives.
importance: 5
category: research
related_publications: false
---

**Selective Partition Repair for Group-Relative Policy Optimization** studies hidden correctness partitions in all-rejected rollout groups. **Under review at ICLR 2027.**

- Score complete correctness masks jointly, rather than treating verdicts as independent decisions.
- Apply a frozen predictor and confidence gate to selectively repair group partitions.
- Retain uncertain rewards and leave the GRPO normalizer and policy objective unchanged.

The research distinguishes full-system training gains from held-out partition-recovery diagnostics.
