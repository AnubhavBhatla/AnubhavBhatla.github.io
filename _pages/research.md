---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 2
---

## Hardware-efficient Secure Cache Design
_Guide: [Prof. Biswabandan Panda](https://www.cse.iitb.ac.in/~biswa/)_  
* Extensively analyzed side-channel attacks and state-of-the-art cache designs which are secure against such attacks
* Proposed modifications to the MIRAGE cache design aiming to reduce hardware overhead while retaining security
* Simulated the proposed cache design to ensure no Set-Associative Eviction occurs in $10^16$ years of system lifetime
* Implementing the proposed cache design on ChampSim simulator to estimate performance overhead compared to a baseline non-secure cache design

## Secure Cache-line Reallocation
_Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/)_ [Report](https://anubhavbhatla.github.io/assets/pdf/R&D_report.pdf){: .btn--report} [Slides](https://anubhavbhatla.github.io/assets/pptx/R&D_presentation.pptx){: .btn--slides}  
* Covered literature on multi-core processors, cache replacement policies, side channel attacks and their mitigation
* Implemented the PASS-P, Utility-based DCP (UCP), and static cache partitioning techniques on the SNIPER multi-core simulator and carefully analyzed results for different cache configurations
* Performed extensive analysis of performance, sensitivity, re-allocated blocks and dead blocks for different benchmarks
* Proposed and implemented a modification to PASS-P using SNIPER simulator to preferentially re-allocate dead blocks with the aim to improve performance