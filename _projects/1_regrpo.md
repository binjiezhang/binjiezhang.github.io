---
layout: page
title: ReGRPO — Grounded Reflection and Recovery
description: Learning structured reflection and corrective tool use; ECCV 2026.
img: assets/img/regrpo.png
importance: 1
category: research
related_publications: false
---

**ReGRPO** learns grounded reflection and recovery for tool-using multimodal agents. **Accepted at ECCV 2026; first author.**

- A reflective data engine executes near-miss actions to collect grounded failure observations.
- Structured **ErrorType / Evidence / FixPlan** reflections pair those failures with corrective tool actions for supervised warm-start training.
- Policy optimization jointly learns reflections and corrective actions within local trajectories, with a cost term discouraging unnecessary reflection.
- The underlying GRPO estimator is retained; the contribution lies in grounded recovery data, trajectory structure, and the training protocol.

[Paper](https://arxiv.org/abs/2606.31392) · [Code](https://github.com/showlab/ReGRPO)
