---
layout: page
title: Ego-centric Predictive Model
description: Two-stage egocentric video prediction conditioned on hand trajectories.
img: assets/img/egopm.png
importance: 3
category: research
related_publications: false
---

A two-stage model for **egocentric future prediction**:

1. Predict future **hand trajectories** from past frames and recent motion.
2. Use the predicted trajectories to condition a **Latent Diffusion Model** that generates future video.

Trained and evaluated on **Ego4D**, **BridgeData**, and **RLBench**, the approach achieves state-of-the-art egocentric video prediction quality and produces trajectory-consistent futures that can be used as a world model for downstream planning. Currently under review at **ICML 2026** *(top 15%)*.
