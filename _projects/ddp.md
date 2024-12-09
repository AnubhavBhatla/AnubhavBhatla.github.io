---
layout: page
title: "Understanding the Security of Secure Randomized Caches"
description: "Proposed the Oasis cache: A randomized cache design with minimal design complexity and ultra-low cost"
img: assets/img/hardware-security.png
importance: 4
category: research
related_publications: maya, mirage
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

_Guides:[Prof. Biswabandan Panda](https://www.cse.iitb.ac.in/~biswa/), [Prof. Sayandeep Saha](https://sites.google.com/view/sayandeepsaha/home)_  

_Funded by the Intel India Research Fellowship_

MIRAGE and MAYA are state-of-the-art secure randomized cache designs that offer strong security guarantees against conflict-based attacks. However, they introduce various modifications to a traditional set-associative cache. These changes, though provide complete security, are not completely understood and it's not completely clear as to when and how these "security knobs" work. We are currently working on identifying these "knobs" in modern secure randomized cache designs and explaining their inner workings. We are also looking at complex combinations of these knobs and how they interact with one another with the goal of identifying the minimal set of these knobs to secure a traditional set-associative cache.

