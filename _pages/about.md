---
permalink: /
title: "Xinxiong Wu (吴心雄)"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a student at [Peking University](https://www.pku.edu.cn/). My research sits at the intersection of **machine learning theory** and **mathematical structures**, with a focus on building systems that can learn continuously and discover structure in complex domains.

I am broadly interested in:
- **Continual Learning** — How can neural networks learn a growing stream of tasks without forgetting, without replaying all past data, and without architectural bloat? I am developing architectures that use selective plasticity and dynamic topology to achieve this.
- **ML for Algebraic Structures** — Applying machine learning to search and discovery problems in finite algebra, particularly enumerating *simple skew braces* (algebraic objects underlying the Yang-Baxter equation) at scales far beyond brute-force enumeration.
- **Integrable Systems** — Using reinforcement learning to explore integrable dynamical systems and understand reward hacking in structured environments.

---

## News

- **[Jun 2026]** Completed saturation-level enumeration of simple skew braces over 8 non-abelian simple groups (A<sub>5</sub>, PSL(2,7), A<sub>6</sub>, PSL(2,8), PSL(2,11), A<sub>7</sub>, PSL(2,17), PSL(2,23)), confirming a novel multiplicity-2 structural conjecture with zero counterexamples.
- **[Jun 2026]** Running CIFAR-100 class-incremental learning experiments for the Brainformer architecture, benchmarked against CBP (Nature 2024), O-EWC, and LoRA baselines.

---

## Research Projects

**SkewBraceSearch** &nbsp;·&nbsp; *ML-guided discovery in finite algebra*

We develop what we believe to be the first machine learning framework for enumerating *simple skew braces* — algebraic structures that parametrize set-theoretic solutions to the Yang-Baxter equation. Starting from non-abelian simple groups, our mutation-based search finds iso-classes that brute-force enumeration cannot reach at this scale. We confirm a structural **multiplicity-2 conjecture** (each simple additive group admits exactly 2 iso-types of simple skew brace, paired by the Koch–Truman opposite construction) across all 8 tested groups with zero counterexamples.

**Brainformer** &nbsp;·&nbsp; *Continual learning via selective plasticity*

We investigate whether a transformer-based architecture can sustain lifelong learning on a sequence of tasks without catastrophic forgetting, without growing the model size, and without relying on experience replay. Our approach uses *selective write-gating* (triggered by a reducibility-gap signal) to freeze stable knowledge while keeping plastic capacity for new learning. We evaluate on CIFAR-100 class-incremental learning and a custom Continual-MQAR benchmark, targeting results that beat CBP, O-EWC, and adaptive LoRA across average accuracy, maximum forgetting, and backward transfer.

**IntegrableExplorer** &nbsp;·&nbsp; *Reinforcement learning for integrable systems*

We study RL agents navigating structured dynamical environments and characterize five distinct forms of reward hacking that emerge specifically due to integrability constraints. This work aims to understand how reward shaping interacts with conserved quantities in physics-inspired RL benchmarks.

---

## Education

**Peking University**, Beijing, China

---

## Misc

I can be reached at [xinxiong@stu.pku.edu.cn](mailto:xinxiong@stu.pku.edu.cn).
