---
title: "G-solver: Gaussian Belief Propagation and Gaussian Processes for Continuous-Time SLAM"
collection: publications
category: conferences
permalink: /publication/2025-G-solver
excerpt: 'This extended abstract is about G-solver, a fully probabilistic framework for continuous-time SLAM that integrates Gaussian Processes (GP) within a distributed Gaussian Belief Propagation (GBP) inference scheme.'
date: 20-10-2025
venue: 'CroCoDL - ICCV 2025 Workshop on Large Scale Cross Device Localization'
paperurl: 'https://academicpages.github.io/files/paper1.pdf'
citation: 'D Ceriola and S Ferrari, et al. &quot;G-solver: Gaussian Belief Propagation and Gaussian Processes for Continuous-Time SLAM; Extended abstract at <i>CroCoDL - ICCV 2025</i>.'
---
This work was presented as an extended abstract at the ICCV 2025 Workshop on Large Scale Cross Device Localization (CroCoDL). It introduces the foundational architecture of G-solver, a decentralized framework that integrates Gaussian Processes (GP) within a distributed Gaussian Belief Propagation (GBP) scheme. The resulting system provides a high-performance solver for decentralized continuous-time SLAM, designed to maintain trajectory smoothness and consistency across asynchronous sensor streams while mitigating the computational bottlenecks of centralized approaches.

*Abstract*
Continuous-time Simultaneous Localization and Mapping (CT-SLAM) offers a natural way to integrate data from diverse and asynchronous sensors. Most existing approaches rely on centralized Nonlinear Least Squares (NLLS) solvers, which are hard to scale. In contrast, distributed Gaussian Belief Propagation (GBP) offers a scalable, decentralized approach that naturally manages uncertainty. However, existing GBP methods for continuous SLAM rely on spline-based interpolation, which is hard to tune and do not offers easy uncertainty extraction. Gaussian Processes (GPs) provide a robust alternative by modeling dynamics and their uncertainty. In this paper, we introduce a distributed GBP solver that uses GP priors for continuous-time trajectory estimation, resulting in improved accuracy and efficiency without compromising execution times, fundamental for real-world applications. We release an open-source implementation at TBA.
