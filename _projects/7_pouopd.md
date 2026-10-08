---
layout: page
title: POU-OPD — Update Utility
description:
  Measuring whether keeping or resetting executable state provides useful
  supervision.
importance: 7
category: research
related_publications: false
---

**Keep or Reset? Measuring Update Utility for On-Policy Distillation of Coding Agents**. **Under review at AAAI.**

- Construct paired Keep / Reset supervision from the same student-reached state.
- Compare matched temporary student updates using executable checks.
- Restore the base snapshot before committing one utility-weighted update, or skip when neither branch helps.

The contribution is local, checkpoint-dependent measurement of post-update learning utility. It does not change the deployment policy.
