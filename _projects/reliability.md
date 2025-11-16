---
layout: page
title: "Reliability of Accelerators against SDCs"
description: "Working on understanding the reliability of SoTA accelerators against silent data corruptions, and exploring the design space of mitigations"
img: assets/img/sdc.png
importance: 2
category: research
related_publications:
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/sdc.png" title="Silent Data Corruptions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Silent Data Corruptions in hardware
</div>
</center>

_Guide:[Prof. Mengjia Yan](https://www.cse.iitb.ac.in/~biswa/)_  

_In collaboration with AMD and [Prof. Joel Emer](https://people.csail.mit.edu/emer/)_

We have studied the effects of SDCs on CNN accelerators by analyzing faulty model weights and accuracy. We are also analyzing various fault models for systolic array-based LLM attention accelerators and studying the performance-hardware tradeoffs of various mitigation techniques. Finally, we also developing an in-house simulator to model the effects of hardware faults in LLM attention.

