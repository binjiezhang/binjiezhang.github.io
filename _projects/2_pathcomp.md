---
layout: page
title: PathComp — Persistent VLA Anchors
description: Preserving acquisition-time interfaces during continual VLA fine-tuning.
importance: 2
category: research
related_publications: false
---

**Path Compatibility (PathComp)** preserves acquisition-time input–response relations during continual fine-tuning of vision–language–action policies. **Under review at ICLR 2027.**

- Record modal tokens together with the fused latents and action distributions they produced when a task was acquired.
- Train current fusion and action modules to preserve those persistent responses from cached inputs.
- Use a separate modal anchor to constrain encoder drift on stored observations.

The study evaluates held-out action error under its continual-learning protocol. It does not equate offline action error with rollout success, and does not claim matched storage or total training compute.
