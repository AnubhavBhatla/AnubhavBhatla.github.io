---
layout: page
title: High-Performance and Energy-Efficient In-Order Cores
description: "Implementing the Freeflow and Freeway in-order core designs which help increase performance and energy efficiency"
img: assets/img/freeway.png
importance: 3
category: research
related_publications: freeflow, freeway
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/freeway.png" title="Freeway Core" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    An overview of the Freeway microarchitecture
</div>

_Guide: [Prof. Virendra Singh](https://www.ee.iitb.ac.in/~viren/)_  

Slice Out-of-Order processors propose an energy-efficient architecture which add just enough OoO support for MLP extraction. The state of the art sOoO core, Load-Slice Core increase energy efficiency by 43% over in-order cores and 4.7x over out-of-order cores. Freeway uses a new dependence-aware slice execution policy that tracks dependent slices and keeps them out of the way of MLP extraction. This helps it perform 12% faster than traditional sOoO cores and with minimal hardware/energy overheads. Freeflow core also proposes modifications on top of traditional sOoO cores which help extract the inherent ILP in the program, rather than focusing on MLP extraction in the case of Freeway. I have finished the literature survey, trying to understand the various developments made in the study of sOoO cores, and am currently going through the source code for the Gem5 multicore simulator. This goal is to implement various sOoO core designs and compare them.
