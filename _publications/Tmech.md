---
title: "BRAM-ED: Vehicle Trajectory Prediction Considering the Change of Driving Behavior"
collection: publications
category: manuscripts
permalink: /publication/2022-12-01-bram-ed-vehicle-trajectory-prediction-considering-the-change-of-driving-behavior
excerpt: 'BRAM-ED: vehicle trajectory prediction considering the change of driving behavior.'
date: 2022-12-01
venue: 'IEEE/ASME Transactions on Mechatronics'
paperurl: 'https://ieeexplore.ieee.org/document/9834049'
citation: 'L. Li, W. Zhao, C. Wang. (2022). "BRAM-ED: Vehicle Trajectory Prediction Considering the Change of Driving Behavior." <i>IEEE/ASME Transactions on Mechatronics</i>.'
---

Trajectory prediction plays a key role in the decision-making system of autonomous vehicles. The existing trajectory prediction models have the problem of accuracy deterioration when driving behavior change. To solve this problem, a novel BRAM-ED trajectory prediction framework is proposed, which mainly consists of driving behavior recognition model, behavior attention mechanism (BAM) trajectory encoder, and behavior adaptive future trajectory decoder. First, a Bi-GLSTM network is designed to recognize real-time driving behavior. The graph structure is used to describe the complex dependencies among vehicles and recurrent cell is to capture temporal correlation. Subsequently, in contrast to traditional models, directly concatenate historical trajectories and interactive information as the input of prediction model, BAM is proposed to integrated trajectory and interaction features in this article. The BAM is designed to generate attention weights according to the change of driving behavior, and guide trajectory decoder to predict the future trajectories. Then, the proposed model is trained and validated on various public datasets, including HighD and NGSIM. Compared with existing optimal models, our prediction error has been reduced 44.66% at most. Furthermore, a typical cut-in scenario is designed based on hardware-in-loop platform. The experiment results show that the proposed model could recognize the change of driving behavior timely, and predict accurate trajectory.
