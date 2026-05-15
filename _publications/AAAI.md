---
title: "Guided Distillation and Risk Adaptive Evolution for Multi-Robot Navigation"
collection: publications
category: conferences
permalink: /publication/2026-01-01-guided-distillation-and-risk-adaptive-evolution-for-multi-robot-navigation
excerpt: 'Guided distillation and risk adaptive evolution for multi-robot navigation.'
date: 2026-01-01
venue: '2026 40th Annual AAAI Conference on Artificial Intelligence'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/37036'
citation: 'X. Li, J. Fang, L. Li, B. Chen, G. Li, J. Xue. (2026). "Guided Distillation and Risk Adaptive Evolution for Multi-Robot Navigation." <i>AAAI</i>.'
---

Recent advancements in multi-robot navigation have explored methods that combine Large Language Models (LLMs) for tasks like scene understanding or high-level decision-making. However, these approaches face challenges with high inference latency and potential hallucinations. To address these challenges, we propose a knowledge-driven Reinforcement Learning (RL) framework, GUIDER, that utilizes an LLM in two different offline roles. First, we leverage the LLM as an offline knowledge source. Its expertise is distilled into a compact model, which is applied only when the RL agent is uncertain about its own value estimates and the model itself is confident in its prediction. Additionally, we utilize the LLM as an offline semantic engine. This process translates the LLM's high-level understanding of situational risk into a dynamic adjustment of the RL agent's behavioral style, evolving a function that optimally balances conservative and aggressive actions. We conduct extensive experiments in both terrestrial and maritime settings. Across all maritime scenarios (3–12 robots), GUIDER improves the task success rate and reduces the collision rate significantly compared to the state-of-the-art RL-based multi-robot navigation methods.
