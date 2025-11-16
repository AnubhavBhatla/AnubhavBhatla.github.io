---
layout: page
title: "Reliability of Accelerators against SDCs"
description: "Working on understanding the reliability of SoTA accelerators against silent data corruptions, and exploring the design space of mitigations"
img: assets/img/sdc.png
importance: 2
category: research
related_publications: sok, maya, mirage
---

<center>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/maya.png" title="MAYA cache design" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An overview of the MAYA cache design
</div>
</center>

_Guide:[Prof. Mengjia Yan](https://www.cse.iitb.ac.in/~biswa/)_  

_In collaboration with AMD_

MIRAGE and MAYA are state-of-the-art secure randomized cache designs that offer strong security guarantees against conflict-based attacks. However, they introduce various modifications to a traditional set-associative cache. These changes, though provide complete security, are not completely understood and it's not completely clear as to when and how these "security knobs" work. Our work identifies these "knobs" in modern secure randomized cache designs and explains their inner workings. We also look at complex combinations of these knobs and how they interact with one another with the goal of identifying the minimal set of these knobs to secure a traditional set-associative cache.

