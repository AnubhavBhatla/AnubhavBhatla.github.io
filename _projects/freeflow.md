---
layout: page
title: High-Performance and Energy-Efficient In-Order Cores
description: "Implemented the Freeflow and Load-Slice in-order core designs which help increase performance and energy efficiency"
img: assets/img/freeway.png
importance: 3
category: research
related_publications: freeflow, freeway, load_slice
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

Sliced-Out-of-Order processors propose an energy-efficient architecture which add just enough OoO support for MLP extraction. The state of the art sOoO core, Load-Slice Core increase energy efficiency by 43% over in-order cores and 4.7x over out-of-order cores. Freeway uses a new dependence-aware slice execution policy that tracks dependent slices and keeps them out of the way of MLP extraction. This helps it perform 12% faster than traditional sOoO cores and with minimal hardware/energy overheads. Freeflow core also proposes modifications on top of traditional sOoO cores which help extract the inherent ILP in the program, rather than focusing on MLP extraction in the case of Freeway. I have sucessfully implemented the Load-Slice and Freeflow core architectures using the Gem5 multicore simulator.

&nbsp;&nbsp;&nbsp;&nbsp; [Report](https://anubhavbhatla.github.io/assets/pdf/EE748_report.pdf){: .btn--report} &nbsp;&nbsp;&nbsp;&nbsp; [Slides](https://anubhavbhatla.github.io/assets/pptx/EE748_presentation.pptx){: .btn--slides} &nbsp;&nbsp;&nbsp;&nbsp; [GitHub](https://github.com/AnubhavBhatla/Freeflow-Core/tree/main){: .btn--github}
