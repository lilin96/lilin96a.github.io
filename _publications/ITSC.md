---
title: "COVLM-RL: Critical Object-Oriented Reasoning for Autonomous Driving Using VLM-Guided Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2025-01-01-covlm-rl-critical-object-oriented-reasoning-for-autonomous-driving-using-vlm-guided-reinforcement-learning
excerpt: 'COVLM-RL: critical object-oriented reasoning for autonomous driving using VLM-guided reinforcement learning.'
date: 2025-01-01
venue: '2025 28th IEEE International Conference on Intelligent Transportation Systems (ITSC)'
slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/11423557'
citation: 'L. Li, Y. Cai, J. Fang, J. Xue, C. Lv. (2025). "COVLM-RL: Critical Object-Oriented Reasoning for Autonomous Driving Using VLM-Guided Reinforcement Learning." <i>ITSC</i>.'
---

End-to-end autonomous driving frameworks face persistent challenges in generalization, training efficiency, and interpretability. While recent methods leverage VisionLanguage Models (VLMs) through supervised learning on large-scale datasets to improve reasoning, they often lack robustness in novel scenarios. Conversely, reinforcement learning (RL)-based approaches enhance adaptability but remain datainefficient and lack transparent decision-making. To address these limitations, we propose COVLM-RL, a novel end-toend driving framework that integrates Critical Object-oriented (CO) reasoning with VLM-guided RL. Specifically, we design a Chain-of-Thought (CoT) prompting strategy that enables the VLM to reason over critical traffic elements and generate high-level semantic decisions, effectively transforming multiview visual inputs into structured semantic decision priors. These priors reduce the input dimensionality and inject taskrelevant knowledge into the RL loop, accelerating training and improving policy interpretability. However, bridging high-level semantic guidance with continuous low-level control remains non-trivial. To this end, we introduce a consistency loss that encourages alignment between the VLM's semantic plans and the RL agent's control outputs, enhancing interpretability and training stability. Experiments conducted in the CARLA simulator demonstrate that COVLM-RL significantly improves the success rate by 30% in trained driving environments and by 50% in previously unseen environments, highlighting its strong generalization capability.
